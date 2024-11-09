<img src="./images/langualee_cover.png" />

<div align="center">
  <div>
    <img src="https://img.shields.io/badge/Next.js-000?style=for-the-badge&logoColor=fff&logo=nextdotjs" alt="Next.js" />
    <img src="https://img.shields.io/badge/Vercel-000.svg?style=for-the-badge&logo=vercel&logoColor=fff" alt="Vercel" />
    <img src="https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=fff" alt="TypeScript" />
    <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=fff" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/shadcn%2Fui-000?style=for-the-badge&logo=shadcnui&logoColor=fff" alt="shadcn/ui" />
    <img src="https://img.shields.io/badge/ESLint-4b32c3?style=for-the-badge&logo=eslint&logoColor=fff" alt="ESLint" />
    <img src="https://img.shields.io/badge/Prettier-f7b93e?style=for-the-badge&logo=prettier&logoColor=fff" alt="Prettier" />
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=fff" alt="PostgreSQL" />
    <img src="https://img.shields.io/badge/Neon%20Serverless-3FCF8E?style=for-the-badge&logo=neon&logoColor=fff" alt="Neon" />
    <img src="https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=000" alt="Drizzle" />
    <img src="https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=fff" alt="Clerk" />
    <img src="https://img.shields.io/badge/Stripe-008CDD?style=for-the-badge&logo=stripe&logoColor=fff" alt="Stripe" />
    <img src="https://img.shields.io/badge/Zustand-423c36?style=for-the-badge&logo=zustand&logoColor=fff" alt="Zustand" />
  </div>

  <h3 align="center">Real Estate Search Platform</h3>

  <div align="center">
    ゲームのように学習を旅する語学アプリ
  </div>
</div>

## 📋 <a name="table">もくじ</a>

1. 🤖 [はじめに](#intro)
2. 🔗 [URL](#url)
3. 💻 [画面一覧](#screen_list)
4. 🚀 [アプリの利用サンプル](#example)
5. 🤸 [終わりに](#outro)

## <a name="intro">🤖 はじめに</a>

あなたの学習をパワフルにする語学アプリ、Langualee を紹介します。

ゲーム感覚で繰り返し、単語や文章、発音になじんでいくことで、外国語を身に着けていくことができるアプリです。

## <a name="url">🔗 URL</a>

Langualee | Language Learning Adventures   
https://langualee.vercel.app

## <a name="screen_list">💻 画面一覧</a>

```
Langualee  
　│     
　├─　ランディングページ  
　│  
　├─　ログイン関連  
　│　　　　ログインモーダル  
　│　　　　アカウント作成モーダル  
　│　　　　ログアウト  
　│  
　├─　語学コース選択ページ  
　│  
　├─　学習ページ（学習の道のり） 
　│   　├─　プロフィール更新ページ 
　│     └─　レッスンクリアページ  
　│  
　├─　成績表ページ
　│  
　├─　クエスト一覧ページ
　│  
　├─　ショップページ 
　│  
　└─　管理画面  
```

### ログイン不要画面

#### ランディングページ 

##### 未ログインの場合

<img src="./images/landing_page_before_login.png" width="360px" />

##### ログイン済みの場合

<img src="./images/landing_page_after_login.png" width="360px" />

### ログイン関連

```
ログイン関連  
　　ログインモーダル  
　　アカウント作成モーダル  
    ログアウト  
```

#### ログインモーダル 

<img src="./images/login_modal.png" width="360px" />

#### アカウント作成モーダル 

<img src="./images/create_account_modal.png" width="360px" />

#### ログアウト

##### ユーザアバターをクリックしてメニューからログアウト

<img src="./images/logout.png" width="360px" />

### 各ページ（ログイン後）

```
語学コース選択ページ 

学習ページ（学習の道のり） 
  │  
  └─　レッスンページ  
　    　├─　退出モーダル
　      └─　練習モードモーダル 

成績表ページ

クエスト一覧ページ

ショップページ 
```

##### 語学コース選択ページ  

<img src="./images/courses_page.png" width="360px" />

#### 学習ページ（学習の道のり）  

<img src="./images/learn_page.png" width="360px" />

#### レッスンページ  

<img src="./images/lesson_page.png" width="360px" />

##### 退出モーダル 

<img src="./images/exit_modal.png" width="240px" />

##### 練習モードモーダル 

<img src="./images/practice_modal.png" width="240px" />

#### 成績表ページ 

<img src="./images/leaderboard_page.png" width="360px" />

##### クエスト一覧ページ

<img src="./images/quest_page.png" width="360px" />

#### ショップページ  

<img src="./images/shop_page.png" width="360px" />

### 管理画面

```
管理画面 
  ├─　語学コース一覧
　│   　├─　語学コース更新・削除
　│     └─　語学コース登録 
  │  
  ├─　単位一覧
　│   　├─　単位更新・削除
　│     └─　単位登録 
  │  
  ├─　レッスン一覧
　│   　├─　レッスン更新・削除
　│     └─　レッスン登録 
  │  
  ├─　問題一覧
　│   　├─　問題更新・削除
　│     └─　問題登録 
  │  
  ├─　選択肢一覧
　│   　├─　選択肢更新・削除
　│     └─　選択肢登録 
  │  
  └─　管理画面を退出  
```

#### 語学コースの管理  

<div style="display: flex; justify-content: space-between; align-items: flex-start;">
  <div style="flex: 1; margin: 0 10px;">
    <h5>語学コース一覧</h5>
    <img src="./images/admin/01_courses/course_list.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>

  <div style="flex: 1; margin: 0 10px;">
    <h5>語学コース更新・削除</h5>
    <img src="./images/admin/01_courses/course_edit_and_delete.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>

  <div style="flex: 1; margin: 0 10px;">
    <h5>語学コース登録</h5>
    <img src="./images/admin/01_courses/course_register.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>
</div>

#### 単位の管理 

<div style="display: flex; justify-content: space-between; align-items: flex-start;">
  <div style="flex: 1; margin: 0 10px;">
    <h5>単位一覧</h5>
    <img src="./images/admin/02_units/unit_list.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>

  <div style="flex: 1; margin: 0 10px;">
    <h5>単位更新・削除</h5>
    <img src="./images/admin/02_units/unit_edit_and_delete.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>

  <div style="flex: 1; margin: 0 10px;">
    <h5>単位更新・削除</h5>
    <img src="./images/admin/02_units/unit_register.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>
</div>

#### レッスンの管理  

<div style="display: flex; justify-content: space-between; align-items: flex-start;">
  <div style="flex: 1; margin: 0 10px;">
    <h5>単位一覧</h5>
    <img src="./images/admin/03_lessons/lesson_list.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>

  <div style="flex: 1; margin: 0 10px;">
    <h5>単位更新・削除</h5>
    <img src="./images/admin/03_lessons/lesson_edit_and_delete.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>

  <div style="flex: 1; margin: 0 10px;">
    <h5>単位更新・削除</h5>
    <img src="./images/admin/03_lessons/lesson_register.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>
</div>

#### 問題の管理  

##### 問題一覧

<div style="display: flex; justify-content: space-between; align-items: flex-start;">
  <div style="flex: 1; margin: 0 10px;">
    <h5>単位一覧</h5>
    <img src="./images/admin/04_challenges/challenge_list.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>

  <div style="flex: 1; margin: 0 10px;">
    <h5>単位更新・削除</h5>
    <img src="./images/admin/04_challenges/challenge_edit_and_delete.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>

  <div style="flex: 1; margin: 0 10px;">
    <h5>単位更新・削除</h5>
    <img src="./images/admin/04_challenges/challenge_register.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>
</div>

#### 選択肢の管理 

##### 選択肢一覧

<div style="display: flex; justify-content: space-between; align-items: flex-start;">
  <div style="flex: 1; margin: 0 10px;">
    <h5>単位一覧</h5>
    <img src="./images/admin/05_challenge_options/challenge_option_list.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>

  <div style="flex: 1; margin: 0 10px;">
    <h5>単位更新・削除</h5>
    <img src="./images/admin/05_challenge_options/challenge_option_edit_and_delete.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>

  <div style="flex: 1; margin: 0 10px;">
    <h5>単位更新・削除</h5>
    <img src="./images/admin/05_challenge_options/challenge_option_register.png" width="240px" style="max-width: 100%; height: auto;" />
  </div>
</div>

## <a name="example">アプリの利用サンプル</a>

##### Langualee 操作デモ

###### 基本ルール

最初に与えられるハートは５、経験値（XP）は０。問題を間違えるとハートが１つ減り、正解すると XP が１０ポイント増える。

ハートは5以上には増えない。

###### コースの選択

ログイン、コースの選択、学習ページの確認、ログアウトを行なう。

初めてログインした時は、コースが選択されていないので、学習ページは見られず、コースの選択画面に飛ばされる。

<!-- ./movies/langualee_select_course.mp4 -->
<video src="movies/langualee_select_course.mp4" controls="true"></video>

###### レッスン実行

表示されている、学習の道のりの１つの丸が１つのレッスンです。

レッスンをクリックすると、レッスンが始まります。１つのレッスンには、いくつかの出題（チャレンジ）があります。
レッスン内のすべての出題をクリアすると、そのレッスンは終了です。

出題中でも、レッスンは途中退出することができ、
退出した後、学習の道のりで途中退出したレッスンを見ると、学習進捗が円グラフの状態で確認することができます。

<!-- ./movies/langualee_select_course.mp4 -->
<video src="movies/langualee_select_course.mp4" controls="true"></video>

###### XP によるハートの回復

出題に対して不正解を続きハートが０になると、出題に回答できなくなります。

しかし、出題を正解して XP のポイントがあると、ハートの回復ができます。XP１０ポイントでハートが最高の５に回復できます。

###### 練習モード

###### 練習モード

## <a name="outro">🤸 おわりに</a>

ゲーム感覚で習慣化して外国語を訓練する、語学アプリ Langualee を紹介しました。

管理者の機能も揃えているので、実際に出題データを登録していけば、実際に語学訓練ができるアプリになります。
