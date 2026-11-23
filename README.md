# IBM Bob 실습 가이드

`index.html`에서 세 실습 가이드로 이동하는 정적 사이트입니다. 기존 가이드 HTML 세 개는 수정하지 않았습니다. 설치나 빌드 과정 없이 배포할 수 있습니다.

```text
website/
├── index.html             메인 페이지
├── guide_p01.html         운영 자료 분석
├── guide_p02.html         Db2 SQL 작성·개선
├── guide_bobathon.html    Bobathon
├── .nojekyll              HTML을 그대로 배포
├── .gitignore
└── README.md
```

## GitHub Pages 배포

1. `https://github.com/jjjhk999/bobathon` 저장소의 **최상위**에 이 폴더의 내용을 올립니다. `index.html`과 가이드 HTML 세 개가 같은 위치에 있어야 합니다. `website` 폴더를 통째로 한 단계 아래에 넣지 않습니다.
2. 저장소의 **Settings → Pages**를 엽니다.
3. **Source**에서 **Deploy from a branch**를 선택합니다.
4. 업로드한 브랜치와 **/(root)**를 선택하고 **Save**를 누릅니다.
5. 배포가 끝나면 Pages에 표시되는 주소로 접속합니다. 기본 예상 주소는 `https://jjjhk999.github.io/bobathon/`입니다.

실습 링크는 상대 경로를 사용하므로 `/bobathon/` 하위에서도 동작합니다. Git 로그인과 업로드는 직접 진행합니다.

설정 기준: [GitHub Pages 공식 문서](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## 로컬 미리보기

`index.html`을 브라우저로 열면 메인 화면과 세 가이드의 이동을 확인할 수 있습니다.
