# vite를 이용한 포트폴리오 사이트 만들기

## vite를 사용하는 이유

1. [vite](https://kovitejs.dev/guide/)

Vite는 현대적인 프론트엔드 개발을 위한 빠른 도구입니다. 다음은 Vite를 사용하는 이유 중 일부입니다:

    1. 빠른 개발 서버: Vite는 빠른 개발 서버를 제공하여 코드 변경 시 즉각적으로 반영되어 빠른 개발 속도를 유지합니다.

    2. ES 모듈 (ESM) 기반 번들링: Vite는 ES 모듈 기반의 번들링을 지원하여 빌드 시간을 최소화하고 성능을 향상시킵니다. 이는 코드를 작은 단위로 번들링하고, 필요할 때 동적으로 로드하여 초기 페이지 로딩 시간을 줄여줍니다.

    3. 개발환경 최적화: Vite는 HMR(Hot Module Replacement)을 지원하여 코드 변경 시 즉각적으로 브라우저에 반영하여 개발자가 빠르게 피드백을 받을 수 있습니다.

    4. 플러그인 시스템: Vite는 다양한 플러그인을 통해 개발환경을 확장할 수 있도록 지원합니다. 이를 통해 사용자 정의 설정 및 기능을 추가할 수 있습니다.

    6. 성능: Vite는 빠른 번들링 속도와 작은 번들 크기를 제공하여 웹 애플리케이션의 초기로딩 속도를 개선합니다.

    7. Vue 및 React 등 프레임워크 지원: Vue나 React와 같은 인기 있는 프레임워크를 지원하여 이러한 프레임워크로 개발할 때 최적의 도구로 활용됩니다.

## 구현 기능
- 구글 폰트 적용


## 트러블 슈팅 
<details>
<summary>git 업로드 버그</summary>
git 명령 불가 
git 환경변수 설정

권한으로 업로드 버그생김
자격증명 확인
git remote set-url origin https://elese0821@github.com/elese0821/vite-project.git

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/elese0821/vite-project.git
git push -u origin main
</details>

# 순서
- 깃 연동 
- css setting 
