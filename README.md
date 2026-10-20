# 띵타이쿤 스마트 세공 계산기 (웹 버전)

Python Tkinter 프로그램을 HTML/CSS/JavaScript 웹페이지로 옮긴 버전입니다.

## GitHub Pages로 공개하기

1. GitHub에 로그인한 뒤 새 저장소(repository)를 만듭니다.
2. 저장소 이름은 예를 들어 `gem-calculator`로 지정합니다.
3. 이 폴더 안의 `index.html`과 `README.md`를 저장소 최상위(root)에 업로드합니다.
4. 저장소의 **Settings → Pages**로 이동합니다.
5. **Build and deployment**에서 Source를 `Deploy from a branch`로 선택합니다.
6. Branch를 `main`, 폴더를 `/(root)`로 선택하고 **Save**를 누릅니다.
7. 배포가 끝나면 같은 Pages 화면에 표시되는 웹 주소로 접속합니다. 보통 `https://깃허브아이디.github.io/gem-calculator/` 형태입니다.

## 기능

- 커먼/노멀/레어 등급별 상한선
- 바이올렛, 오팔, 아다만티움 재고와 초기 수치 입력
- 기존 Python 코드의 세공 횟수 배분 계산 방식 적용
- 계산 후 남은 재고 자동 이월
- 계산 후 초기 수치 입력칸 자동 비우기
- 모바일 화면 대응

참고: GitHub Pages는 정적 웹사이트 호스팅이므로 Python 파일을 직접 실행하지 않습니다. 계산 로직을 브라우저에서 동작하는 JavaScript로 변환했습니다.
