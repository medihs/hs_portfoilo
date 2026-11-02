# 정현서 포트폴리오

`index.html` 한 장과 `assets/` 폴더로 이루어진 정적 웹사이트예요. 빌드 과정 없이 그대로 배포돼요.

## 처음 배포하기 (GitHub + Vercel)
1. GitHub에서 새 저장소(Repository)를 만들어요.
2. 이 폴더 안의 `index.html`, `assets/`, `README.md`를 저장소 맨 위(루트)에 올려요. (Add file → Upload files)
3. Vercel에서 Add New → Project로 그 저장소를 연결해요.
4. Framework Preset은 `Other`, Build Command와 Output Directory는 비워 두고 Deploy를 눌러요.

## 수정사항 반영하기
Claude에게 수정을 요청한 뒤 새 `index.html`(이미지가 바뀌었다면 `assets/`도)을 받아서, GitHub 저장소에 같은 이름으로 덮어써서 올려요. Vercel이 자동으로 다시 배포해요.
