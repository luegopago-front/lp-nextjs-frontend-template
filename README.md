![](https://luegopago.blob.core.windows.net/luegopago-uploads/website/luegopago-logo.png)

# Luegopago Next.js Front-end Template

![](https://img.shields.io/badge/release-v0.1.0-%23FF40FC?style=flat-square)
![](https://img.shields.io/badge/Node.js-v14.19.*-green?style=flat-square)
![](https://img.shields.io/badge/Yarn-v1.22.10-green?style=flat-square)
![](https://img.shields.io/badge/Next.js-v12.1.0-black?style=flat-square)

Next.js with Typescript template for front-end projects with
Atomic Design pattern.

## Features
- Typescript support.
- Atomic Design pattern.
- Jest setup for unit/integration testing.
- Cypress setup for end-to-end testing.
- VSCode Code Snippets.
- Eslint and Prettier configuration.
- Client side, server side and full-stack debugger.
- Axios interceptor already.
- Storybook MDX documentation support.
- MDX pages support.
- Rendering strategies: ISR, SSG, SSR, CSR.
- Precommit hook to check format and types.

## Development notes
#### Node.js support
Minimum Node.js version recommended is `v14.19.*`

#### Package manager
Use [Yarn](https://yarnpkg.com) like package manager recommended.

### Getting started
#### Install and Run
Install all **npm** dependencies that are in `package.json` file.

`$ yarn`

`$ yarn dev`

#### Deployment
- On promise deployment.

`$ yarn build`

`$ yarn start`

- Docker deployment.

`$ docker build . -t <project-name>`

`$ docker run -p 3000:3000 -n <project-name>`

### Folder structure
````
 .
├─ 📂 __tests__
├─ 📂 .circleci
├─ 📂 .husky
├─ 📂 .storybook
├─ 📂 .vscode
├─ 📂 public
|  └─ ...
├─ 📂 src
|  ├─ 📂 components
|  |  ├─ 📂 atoms
|  |  |  ├─ 📂 __stories__
|  |  |  |  ├─ 📄 Button.stories.tsx
|  |  |  ├─ 📄 Button.tsx
|  |  |  ├─ ...
|  |  ├─ 📂 molecules
|  |  ├─ 📂 organisms
|  |  ├─ 📂 templates
|  ├─ 📂 constants
|  |  ├─ 📄 urls.constants.ts
|  |  ├─ ...
|  ├─ 📂 hooks
|  |  ├─ 📄 useCart.hook.tsx
|  |  ├─ ...
|  ├─ 📂 layouts
|  ├─ 📂 mocks
|  ├─ 📂 modules
|  |  ├─ 📄 api.interceptor.ts
|  |  ├─ ...
|  ├─ 📂 pages
|  ├─ 📂 services
|  |  ├─ 📄 api.service.ts
|  |  ├─ ...
|  ├─ 📂 types
|  |  ├─ 📄 car.types.ts
|  |  ├─ ...
|  └─ 📂 utils
|     ├─ 📄 sum.util.ts
|     └─ ...
├─ 📂 styles
|  ├─ 📄 globals.css
└ ... 
````

### Build code
Snippets:

| **Snippet** | **Descripción** |
| ------------ | ------------ |
| `ccomp` | Create a component or page. |
| `csvc` | Create a service. |
| `chok` | Create a hook. |
| `cstr` | Create story for a component. |


### Testing
#### Unit testing and integration testing
Is recommended do unit testing and integration testing for
some required features.
Use [Jest](https://jestjs.io) as framework to develop tests.

#### End-to-end testing
E2E testing is required just for some cases or important features flows.
Use [Cypress](https://www.cypress.io) as framework to develop automated testing.

#### Design System testing and documentation
Make documentation for created components in `components` folder using [Storybook](https://storybook.js.org/)

### References
- [Next.js](https://nextjs.org/docs/getting-started) documentation.
- [Semantic Versioning 2.0.0](https://semver.org/)
- [Commit Eslint](https://github.com/conventional-changelog/commitlint/#what-is-commitlint) based on the Angular conventions.