# 스토리보드 프롬프트 메이커

장면을 쉬운 말로 고르면 Gemini 영상 프롬프트(영어 + 한국어)로 바꿔 주는 연수용 홈페이지입니다.
`index.html` 파일 하나로 동작하며, 인터넷 연결, API 키, 설치가 필요 없습니다.

## 배포 방법 1: HTML 파일로 나눠 주기
`index.html`을 메일이나 메신저로 보내면, 선생님들이 파일을 더블클릭해 브라우저(크롬, 엣지)로 열면 됩니다.

## 배포 방법 2: GitHub Pages로 링크 만들기
1. github.com에 로그인해서 **New repository**를 만듭니다. (예: `storyboard`, Public)
2. **Add file → Upload files**로 `index.html`을 올리고 **Commit changes**를 누릅니다.
3. 저장소의 **Settings → Pages**에서 Source를 **Deploy from a branch**, Branch를 **main / (root)**로 정하고 **Save**를 누릅니다.
4. 1~2분 뒤 `https://<깃허브아이디>.github.io/storyboard/` 주소가 생깁니다. 이 링크나 QR코드를 나눠 주세요.

## 참고
- 입력한 내용은 각자 브라우저에만 저장됩니다.
- 예시(빈 교실의 노을, 졸업식 날)와 선택지는 `index.html` 안의 `EXAMPLES`, `SHOTS`, `MOVES` 등에서 고칠 수 있습니다.
- Gemini가 한 번에 만드는 길이가 8초라면, '한 장면 길이'를 8초로 바꾸세요.
