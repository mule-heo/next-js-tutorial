## Next.js tutorial - dashboard

- [course curriculum](https://nextjs.org/learn)

### placeholder data

- DB 세팅 이전에 더미 데이터로 활용 가능

### 2. Styling

- css 파일을 컴포넌트에 import하는 것만으로 css에 작성된 스타일 적용 가능
- 관습적으로 최상위 컴포넌트에서 import하는 것이 권장됨
- tailwind 클래스명을 JSX 스크립트 안에 작성하기
- module.css를 import하여 변수 형태로 클래스 지정하기 - 이 방법을 사용하면 고유한 클래스명이 생성되므로 클래스명 충돌 가능성을 피할 수 있음
- clsx를 이용한 클래스명 토글

### Fonts

- 폰트는 빌드 타임에 빌드되어 정적 에셋과 함께 업로드: 외부 요청 필요없음

### Images

- breakpoint를 파악하여 hidden과 block을 동시에 변환하는 식으로 반응형 디자인에 활용 가능


