# Tailwind_practice

## ** Tailwind 적용해서 반응형 작업하기 **

#### (동영상 강의의 도움을 받아 작업 - 약 2시간 소요)

#### https://dllys.github.io/Tailwind_practice/

---

##### 반응형 작업시 화면 크기

| Breakpoint prefix | Minimum width | CSS                                |
| ----------------- | ------------- | ---------------------------------- |
| sm                | 640px         | @media (min-width: 640px) { ... }  |
| md                | 768px         | @media (min-width: 768px) { ... }  |
| lg                | 1024px        | @media (min-width: 1024px) { ... } |
| xl                | 1280px        | @media (min-width: 1280px) { ... } |
| 2xl               | 1536px        | @media (min-width: 1536px) { ... } |

---

##### 헷갈렸던 부분

- 반응형 작업시 변경하고자 하는 css를 어떻게 수정할지

  --> 기본 lg 화면 크기로 작업 (변경되는 부분 앞에 'lg:' 넣기)

- reset.css 파일을 넣었을 때 tailwind가 적용이 안 되는 경우

  --> 충돌되는 부분만 reset.css 수정

  --> 궁금한 점? 다른 분들은 tailwind 적용할 때 reset.css 파일 사용하시는지..

- 여러 개의 코드에 같은 css를 중복해서 넣어야 할 경우 일일이 입력해야 하는지

  (ex - ul > li \* 5 이 경우처럼 li 여러 개에 공통으로 css를 넣어야 할 경우)

  --> Tailwind CLI 설치 , input.css 파일 만들고 공통 css 넣기

  ***

##### 느낀 점

- html이 지저분해진다는 단점이 있음
- 간단한 css(padding, margin 등등...)는 기존 css 방식보다 훨씬 쓰기 편했음
- 앞으로 계속 사용하게 될지는 잘 모르겠음

  (편한 부분은 있지만 html이 복잡해지고 필요한 css코드를 사이트에서 직접 찾아야 해서 조금 귀찮음..)
