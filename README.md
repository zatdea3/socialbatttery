# 사회성 배터리

이 폴더의 파일은 GitHub Pages에 바로 올릴 수 있는 전체 웹사이트 코드입니다.
HTML·CSS·JavaScript가 index.html 안에 들어 있고, 질문 이미지는 assets 폴더에 있습니다.
설치나 빌드 명령은 필요하지 않습니다.

## GitHub에 올리기

1. https://github.com/new 에서 저장소 이름을 social-battery로 입력합니다.
2. Public을 선택하고 Add README를 켜서 Create repository를 누릅니다. 이미 저장소가 있다면 그 저장소를 사용하세요.
3. 저장소의 Code 탭에서 Add file → Upload files를 누릅니다.
4. 이 ZIP을 압축 해제한 뒤, index.html이 보이는 폴더 안의 파일과 assets·licenses 폴더를 모두 끌어 넣습니다. ZIP 자체나 바깥 폴더를 통째로 넣지 마세요.
5. Commit directly to the main branch를 선택하고 Commit changes로 저장합니다. 같은 위치에 파일이 있으면 업로드한 최신 파일로 교체됩니다.
6. 저장소 첫 화면에 index.html과 assets 폴더가 보이는지 확인하세요.

## 웹사이트 주소 만들기

1. 저장소 상단 Settings → 왼쪽 Pages로 들어갑니다.
2. Source: Deploy from a branch
3. Branch: main, 폴더: /(root)
4. Save를 누릅니다.
5. 배포가 끝나면 Pages 화면에 표시된 Visit site로 접속합니다.

기본 주소 형식: https://깃허브아이디.github.io/social-battery/
실제 주소는 Pages 화면에서 확인해주세요.

## 공유 링크와 저장

공유 버튼은 현재 공개된 HTTPS 주소를 기준으로 결과 URL을 복사합니다.
따라서 GitHub Pages에 올리면 새 GitHub 주소가 자동으로 사용됩니다.
문항, 닉네임, 기록은 이용자의 브라우저에 저장되며 서버로 전송되지 않습니다.
새 주소로 이동하면 기존 사이트 주소에 저장된 기록은 자동 이전되지 않습니다.
파일을 직접 열면 일부 브라우저에서 저장·복사가 제한될 수 있으니 공개 주소에서 확인해주세요.

## 코드 수정

index.html: 화면, 스타일, 질문과 결과 계산, 공유·이미지 저장 기능
assets/: 질문용 이미지 5종
about.html / privacy.html / contact.html: 안내 페이지
ads.txt: 광고 설정용 파일. 현재 광고는 비활성화 상태입니다.
licenses/: 포함된 이미지 저장 도구의 라이선스

수정한 파일을 같은 위치에 다시 업로드하면 Pages가 변경 내용을 배포합니다.

공식 안내:
https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
