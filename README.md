# 🐝 Spelling Bee Shooting Game

초등학교 4·5·6학년용 영어 스펠링 슈팅 게임입니다.  
단어와 스펠링 음성을 듣고, 화면에 나타난 여러 단어 중 정답을 찾아 슈팅합니다.

## 🎮 Game Features

- 초등 4·5·6학년 학년별 모드
- 학년별 200개 단어 수록
- 선택한 학년의 단어가 매 라운드 랜덤 출제
- 영어 단어 음성 자동 재생
- 알파벳 스펠링 음성 연속 재생
- 정답 단어 풍선 슈팅
- 점수, 콤보, 생명, 제한 시간 시스템
- 폭발, 미사일, 화면 흔들림 효과
- 다시 듣기 기능
- MEGA SHOT 기능
- PC 마우스 클릭 및 모바일 터치 지원

## 🕹️ How to Play

1. 4학년, 5학년, 6학년 중 하나를 선택합니다.
2. 영어 단어와 알파벳 스펠링 음성을 듣습니다.
3. 화면에 나타난 여러 단어 풍선 중 정답을 찾습니다.
4. 정답 풍선을 클릭하거나 터치하여 격추합니다.
5. 연속 정답으로 콤보 점수를 올립니다.

### Controls

- 마우스 클릭: 슈팅
- 모바일 터치: 슈팅
- `SPACEBAR`: MEGA SHOT
- `다시 듣기`: 단어와 스펠링 음성 반복

## 📚 Word Levels

- Grade 4: 200 words
- Grade 5: 200 words
- Grade 6: 200 words

총 600개의 단어가 포함되어 있습니다.

## 🚀 Run Locally

별도의 설치 없이 HTML 파일을 브라우저에서 실행하면 됩니다.

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY
```

그다음 `Spelling_Bee_Shooting_Game_456.html` 파일을 실행하세요.

또는 VS Code의 Live Server를 사용할 수 있습니다.

## 🌐 GitHub Pages

1. GitHub 저장소의 `Settings`로 이동합니다.
2. `Pages` 메뉴를 선택합니다.
3. `Deploy from a branch`를 선택합니다.
4. Branch를 `main`, Folder를 `/root`로 설정합니다.
5. 저장 후 생성된 주소로 게임을 실행합니다.

메인 페이지로 바로 실행하려면 파일명을 아래처럼 변경하세요.

```text
Spelling_Bee_Shooting_Game_456.html
↓
index.html
```

## 🗂️ Recommended Repository Structure

```text
spelling-bee-shooting-game/
├── index.html
├── README.md
└── screenshot.png
```

현재 게임은 배경 이미지와 단어 데이터가 HTML 파일 안에 포함된 단일 파일 방식입니다.

## 🔊 Voice Support

게임 음성은 브라우저의 Web Speech API를 사용합니다.

브라우저와 운영체제에 따라 영어 음성이 다르게 들릴 수 있습니다.  
Chrome 또는 Edge 최신 버전 사용을 권장합니다.

## 💻 Recommended Environment

- Google Chrome
- Microsoft Edge
- Desktop, tablet, mobile
- Internet connection is not required after loading the file

## ⚠️ Notes

- 일부 모바일 브라우저에서는 첫 화면 터치 후 음성이 재생될 수 있습니다.
- 음성이 들리지 않으면 기기 음량과 브라우저 음성 권한을 확인하세요.
- 브라우저에 설치된 영어 음성에 따라 발음과 속도가 달라질 수 있습니다.

## 🏆 Learning Goals

- 영어 단어 듣기
- 알파벳 순서 인식
- 스펠링 정확도 향상
- 어휘 반복 학습
- 빠른 단어 인식
- 게임 기반 영어 학습

## 📸 Screenshot

```markdown
![Spelling Bee Shooting Game](screenshot.png)
```

저장소에 게임 화면 이미지를 `screenshot.png` 이름으로 추가하면 README에 미리보기가 표시됩니다.

## 📄 License

Educational use only.

단어 목록, 이미지, 음성 및 디자인 요소의 사용 권한을 확인한 후 배포하세요.
