#firebase를 이용한 웹사이트 배포
##fire설치
[nodejs.org](https://nodejs.org)에 접속하여 **LTS**버전의 프로그램을 다운로드 설치한다(기본값)
설치가 완료되면 nodejs프로그램에서 제공하는 **npm**(node package manager)를 사용하게 된다
npm명령으로 firebase를 설치한다(vscode)

``bash
npm i 

설치가 완료되면 firebase명령을 수행할 수 있다. 그 후 사용자등록을 위해 터미널 창에서 아래의 명령을 수행하고 y선택에서 엔터를 하면 브라우저가 뜨면서 본인의 구글계정과 연동
##firebase프로젝트 만들기
##firebas.com에서 할일
[firebase.com](https//firebase.com)에 접속하여 구글계정으로 로그인한다.
로그인 이후 우측 상단의 **콘솔로 이동**버튼을 클릭하여, 나의 콘솔로 이동
프로젝트 만들기를 클릭하요 새로운 프로젝트를 생성한다
-1p:사이트 주소 생성
-2p:사이트 애널리틱스 사용으로 체크
-3p:애널리틱스 사용계정으로 선택, 혹시 국가선택이 뜨면 대한민국을 선택
##vscode에서 할일
포스팅할 프로젝트 폴더를 연다.
 좀 전에 생성한 firebase프로젝트와 본인의 프로젝트를 연동
다음과 같은 명령을 터미널창에서 수행
아래의 설명처럼 호스팅한다
생성된 public폴더에 html,css,img,js폴더를 이동
생성된 index.html파일을 열고 아래의 내용으로 교체

```html
<mata http-equiv ="refresh" content=0;url=./html/index.html">
```