## Front-End Project

Nextjs 13 기반으로 프로젝트를 개발

### Built With

이 프로젝트는 다음과 같은 기술스택으로 구성되어 있습니다.

- [Next.js](https://nextjs.org/)
- [React.js](https://reactjs.org/)
- [yarn](https://yarnpkg.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [ESLint](https://eslint.org/)


## Getting Started

다음은 local 개발환경에서 프로젝트를 설정하는 방법을 설명합니다.

### Prerequisites

이 프로젝트는 node.js와 yarn package manager가 설치되어 있어야 합니다.<br />
mac을 개발도구로 사용하고 있어서 모두 mac 기준으로 설명합니다.<br /><br />
homebrew를 사용하여 설치해 줍니다.<br />

- node.js

  ```sh
  brew install node

  ```

- yarn
  ```sh
  brew install yarn --ignore-dependencies
  ```

위에서 node를 설치해 줬기 때문에 node를 제외하고 설치합니다.
<br />
<br />

### 🛠️ Installation Steps

1. 저장소 복사

```bash
git clone https://github.com/deanlim8961/project-dean.git
```

2. working directory로 이동

```bash
cd project-dean
```

3. Install dependencies - yarn 패키지 설치 (yarn berry 3.2.2)

```bash
yarn install
```

4. app 실행

```bash
yarn dev
```

# 📁 Folder Structure

A quick look at the directories you'll see in this project.

### Root driectory layout

    .
    ├── components          # common, 각 page component
    ├── core                # configs, hooks, redux, utils
    ├── interfaces          # interface 선언
    ├── pages               # page 구성
    ├── public              # 파일 (svg, png...)
    ├── styles              # css
    └── ...
