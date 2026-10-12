# 패밀리 퀘스트: 행복의 비밀

앤서니 브라운 『돼지책』 독후 가족 갈등 탐색·나 전달법·공익광고 활동을 위한 학생용 웹앱입니다.

## GitHub Pages 배포

1. GitHub에서 새 **Public** 저장소를 만듭니다. 예: `family-quest`
2. 이 폴더의 `index.html`, `.nojekyll` 파일을 저장소 **최상위 폴더**에 업로드하고 커밋합니다.
3. 저장소의 **Settings → Pages**에서 **Build and deployment → Deploy from a branch**를 선택합니다.
4. Branch를 `main`, Folder를 `/(root)`로 선택하고 **Save**를 누릅니다.
5. 게시가 완료되면 `https://<사용자명>.github.io/<저장소명>/`에서 접속합니다.

## 실행 및 데이터

- 모든 그림이 `index.html`에 내장돼 있어 정적 웹호스팅만으로 기본 게임이 동작합니다.
- 학생 답변과 미션 도장은 **브라우저의 localStorage**에 저장됩니다. 다른 기기 또는 브라우저로 자동 동기화되지 않습니다.
- 생성형 AI 이미지를 만들려면 별도 HTTPS 백엔드 API가 필요합니다. GitHub Pages 자체는 서버 측 AI API를 실행하지 못합니다.
- OpenAI 등의 **비밀 API 키를 HTML/JavaScript 또는 공개 GitHub 저장소에 넣지 마세요.**
- 백엔드를 연결할 경우 GitHub Pages 사이트의 Origin을 허용하도록 **CORS**를 설정해야 합니다.
- 기본 장면 그림 만들기는 생성형 AI가 아니라 간단한 브라우저 자체 일러스트 생성입니다.
