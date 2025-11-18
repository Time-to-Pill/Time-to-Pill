## 프로젝트 받기 및 실행 방법

### 1. 사전 준비

- Git 설치
- 웹 브라우저 (Chrome 권장)
- (선택) Python 3 – 간단한 로컬 서버로 띄울 때 사용

---

### 2. 저장소 클론(처음 실행하는 경우)

터미널에서 다음 명령을 입력합니다.

```bash
git clone https://github.com/Time-to-Pill/Time-to-Pill.git
cd Time-to-Pill
```

---

3. 최신 코드로 업데이트(이미 클론한 폴더가 있을 때)

이미 Time-to-Pill 폴더가 있다면, 해당 폴더로 이동한 뒤 다음 명령으로 최신 코드를 가져옵니다.

```bash
cd Time-to-Pill
git pull origin main
```
---

## 4. 로컬에서 실행하는 방법

이 프로젝트는 현재 **정적 웹 페이지(HTML/CSS)** 로 구성되어 있습니다.  
아래 두 가지 방법 중 편한 방법을 사용하면 됩니다.

---

### 방법 A. HTML 파일을 직접 열기

1. 파일 탐색기(Finder / Explorer)에서  
   `Time-to-Pill/src/main/resources/static/` 폴더로 이동합니다.
2. `index.html` 파일을 더블클릭하여 브라우저로 엽니다.

> 이 방법은 단순히 화면을 확인할 때 가장 간단한 방법입니다.

---

### 방법 B. 간단한 로컬 서버에서 실행하기

정적 파일을 서버 환경과 비슷하게 보고 싶다면, 터미널에서 다음을 실행합니다.

```bash
cd Time-to-Pill/src/main/resources/static
python3 -m http.server 8000
```

이후 브라우저에서 아래 주소로 접속합니다.

http://localhost:8000/index.html

서버를 종료할 때는 터미널에서 Ctrl + C를 누릅니다.
