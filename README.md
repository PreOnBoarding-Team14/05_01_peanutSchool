## 팀원
[양성호 , 김영길 , 이나원]

## 배포 주소

<a href=https://05-01-peanut-school-lam3z4as6-preonboarding-team14.vercel.app/>땅콩스쿨 페이지</a>

## 💻 설치 방법

    npm install
    npm run dev

## 📂 파일 구조

components     
 ┣ AnyTime         
 ┃ ┣ AnyTime.module.scss       
 ┃ ┗ AnyTime.tsx       
 ┣ Bookmarks       
 ┃ ┣ Bookmarks.module.scss       
 ┃ ┗ Bookmarks.tsx          
 ┣ CheckedBook       
 ┃ ┣ CheckedBook.module.scss      
 ┃ ┗ CheckedBook.tsx      
 ┣ DownloadButton           
 ┃ ┣ DownLoadButton.module.scss     
 ┃ ┗ DownloadButton.tsx       
 ┣ DownloadNow       
 ┃ ┣ DownloadNow.module.scss      
 ┃ ┗ DownloadNow.tsx      
 ┣ ErrorPage      
 ┃ ┣ ErrorPage.module.scss             
 ┃ ┗ ErrorPage.tsx         
 ┣ Footer      
 ┃ ┣ Footer.module.scss        
 ┃ ┗ Footer.tsx      
 ┣ InfiniteScrollBooks        
 ┃ ┣ InfiniteScrollBooks.module.scss    
 ┃ ┗ InfiniteScrollBooks.tsx     
 ┣ Introduction       
 ┃ ┣ Introduction.module.scss         
 ┃ ┗ Introduction.tsx       
 ┣ Layout     
 ┃ ┗ Layout.tsx           
 ┣ LiveVideo             
 ┃ ┣ LiveVideo.module.scss       
 ┃ ┗ LiveVideo.tsx      
 ┣ MainImage       
 ┃ ┣ MainImage.module.scss       
 ┃ ┗ MainImage.tsx      
 ┣ NavBar       
 ┃ ┣ NavBar.module.scss      
 ┃ ┗ NavBar.tsx      
 ┣ ReadingDiary      
 ┃ ┣ ReadingDiary.module.scss    
 ┃ ┗ ReadingDiary.tsx       
 ┗ SlideComments      
 ┃ ┣ SlideComments.module.scss      
 ┃ ┗ SlideComments.tsx     
 constants    
 ┗ constants.ts     
 hooks      
 ┗ useScroll.tsx
 pages   
 ┣ api      
 ┃ ┗ hello.ts      
 ┣ _app.tsx     
 ┗ index.tsx     
 styles    
 ┣ Home.module.css     
 ┣ globals.css      
 ┗ variables.module.scss    
 styles
 ┣ Home.module.css     
 ┣ globals.css     
 ┗ variables.module.scss     
## 📋개발 진행 상황 공유
<img width="876" alt="스크린샷 2022-02-16 오전 2 18 02" src="https://user-images.githubusercontent.com/91244500/154114463-226e49ce-5126-4f4f-8c0f-ecfc768f6a7e.png">


### 프로젝트 과정 소개

| 슬랙을 이용한 소통                                                                                                             |                                                       게더를 활용한 소통                                                       |
| :----------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------: |
| <img width="auto" src="https://user-images.githubusercontent.com/80146176/153052997-f2ca6637-40f8-4e7f-9609-f4885577706a.png"> | <img width="auto" src="https://user-images.githubusercontent.com/80146176/153053947-7be40938-62f8-4dd9-a54b-7328ea550546.png"> |
| 노션에서의 소통                                                                                                                |                                                     화면공유를 활용한 소통                                                     |
| <img width="auto" src="https://user-images.githubusercontent.com/80146176/153054588-6194940a-a76d-4fde-a164-2efb3989d6e8.png"> | <img width="auto" src="https://user-images.githubusercontent.com/80146176/153054110-d7c4169e-3824-4903-8ca5-fc4aec044055.png"> |

## 📝 기능

### 고정 navigation bar

- 내비게이션 바는 고정되게 만들고 스크롤 시 배경 색과 글자 색이 변경된다.

### 마우스 이미지 무한 애니메이션

- keyframe과 animation을 이용해 마우스 이미지가 위아래로 무한(infinite)으로 움직이도록 구현하였다.

### 스크롤 시 글자 애니메이션

- 화면을 스크롤 할 때 각 컴포넌트 별로 영역에 진입 시 글자가 아래에서 위로 올라오는 애니메이션이 동작한다.

### 북 체크

- 화면 진입 시 책 이미지 상단의 체크 이미지를 overflow : hidden 을 사용하여 가려져 있던 이미지가 노출되도록 구현하였다.
- transform , transition 속성을 사용하여 애니메이션 효과를 부여했다.

### 스크롤 북 이미지

- 화면 진입 시 나열되어 있는 책 이미지들이 우에서 좌로 무한히 흐르는 로직 구현. animation: slide 14s linear infinite; 와 같은 속성 사용하였다.

### 스크롤 시 책갈피가 차례로 꽂히는 애니메이션

- window의 스크롤을 감지해 해당 컴포넌트 영역 진입 시 책갈피 이미지가 좌에서 우로 차례대로 나타난다.

### 다운로드 나우 버튼

- 화면 진입 시 두 개의 이미지가 setTimeOut 함수에 의해 시간차를 두고 애니메이션 효과가 실행되도록 구현하였다.

### 라이브 비디오

- video 태그의 속성을 활용하여, 음소거, 컨트롤 요소 삭제, 반복 재생 화면 진입 시 자동 재생 구현하였다.


