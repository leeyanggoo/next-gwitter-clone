# TWITTER clone
![twitter](https://github.com/leeyanggoo/next-gwitter-clone/assets/125417787/2fe6bc89-cb27-4a52-be47-f4bddf932e8d)

>  _애플리케이션 'Twitter'를 클론 코딩한 사이트입니다._
> + Live Demo : https://win98-game.web.app/
> + Refer to : https://www.youtube.com/watch?v=ytkG7RT6SvU / https://github.com/antonioerdeljac/twitter-clone

# 사용 스택 / 라이브러리
+ **Next**
+ **TypeScript**
+ **React**
+ **Zustand**
+ **Prisma**
+ **Mongo**
+ **NextAuth**
+ **Tailwind**
+ /* netlify */
  + Bcrypt - 암호화 해시 함수
  + SWR - data fetching
  + Axios
  + react-dropzone
  + react-hot-toast
  + react-icons
  + react-spinners

# 구현 내역
+ MongoDB를 사용한 Prisma ORM
  + Bcrypt 라이브러리를 사용한 비밀번호 암호화
  + SWR 라이브러리를 사용한 데이터 최신화
+ Zustand를 이용한 Modal 상태관리
+ NextAuth를 이용한 jwt session 사용
+ Tailwind css를 이용한 반응형 레이아웃 구성
+ Base64 문자열을 사용한 이미지 업로드
+ 게시글 / 댓글 / 좋아요 / 알림 기능 구현

## 미구현 / 오류
+ ! 배포 시 DB 미연결
+ ! server와 netlify 오류
+ ! `[next-auth][error][CLIENT_FETCH_ERROR]`
+ 비로그인 시 발생하는 `Error: Not signed in` 오류 (로컬)
+ 알림 상세 내역 미포함 / 링크 기능 X
+ 게시글 및 댓글 삭제 기능 X

# 프로젝트 목적
+ Next.js 및 TypeScript 실습
+ DB 연결 및 axios 연동 실습
+ 환경 변수 설정 및 배포 실습
+ 커스텀 훅 이해 및 실습
