# blog_lisa

학습 기록을 남기는 GitHub Pages 블로그 (Jekyll + minima 테마)

- 사이트 주소: https://rubilisa08.github.io/blog_lisa/
- 새 글 작성: `_posts/YYYY-MM-DD-제목.md` 형식으로 파일 생성 후 front matter(layout, title, date, categories, tags) 작성
- 로컬 미리보기 (Ruby/Bundler 설치 후):

  ```bash
  bundle install
  bundle exec jekyll serve
  ```

## GitHub Pages 배포 설정

1. GitHub 저장소 → Settings → Pages
2. Source를 `Deploy from a branch`로 설정
3. Branch를 `main` / `/(root)`로 설정 후 저장
4. 몇 분 후 https://rubilisa08.github.io/blog_lisa/ 에서 확인
