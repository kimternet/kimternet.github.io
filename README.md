## 설치 및 시작하기
### 1. 필수 사전 준비:
Node.js 설치 (brew install node)
Jekyll 설치 (gem install bundler jekyll)
Yarn 설치 (npm install -g yarn)
### 2. 설치 과정:
GitHub에서 리포지토리를 포크하거나, 템플릿 버튼을 사용해 새로운 리포지토리 생성.
로컬에 클론:
bash
코드 복사
git clone https://github.com/{USERNAME}/{REPOSITORY}.git
디렉토리 변경:
bash
코드 복사
cd neumorphism
의존성 설치:
bash
코드 복사
yarn
bundle install
### 3. 로컬 실행:
개발 환경에서 gulp 명령어로 로컬 서버 실행.
개인화 및 커스터마이징
_config.yml
_config.yml 파일을 편집하여 개인화 가능.
사이트 제목, 설명, 소셜 미디어 링크 등을 설정.
GitHub Metadata Plugin
GitHub API를 사용해 자동으로 프로젝트 목록을 표시할 수 있음.
인증 토큰을 생성해 .env 파일에 추가:
text
코드 복사
JEKYLL_GITHUB_TOKEN=0YOUR0TOKEN0
Particles.js
assets/particles.json 파일을 수정하여 배경 애니메이션을 커스터마이징.
