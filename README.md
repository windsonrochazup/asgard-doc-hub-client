# NextJs React Template

A starter for React applications that includes all you need to build amazing projects. ๐ฅ

## Content table

- [NextJs React Template](#nextjs-react-template)
  - [Content table](#content-table)
  - [Tech Stack](#tech-stack)
  - [Status Project](#status-project)
  - [๐ Getting started](#-getting-started)
    - [Read our workflow guideline](#read-our-workflow-guideline)
    - [Read our naming guideline](#read-our-naming-guideline)
    - [Read our versioning guideline](#read-our-versioning-guideline)
    - [Read our coding guideline](#read-our-coding-guideline)
    - [Read our git flow guideline](#read-our-git-flow-guideline)
    - [๐ฒ Explanation of main scripts](#-explanation-of-main-scripts)
      - [Start](#start)
      - [Test](#test)
      - [Build](#build)
      - [Generate](#generate)
      - [Eslint](#eslint)
      - [Prettier](#prettier)
      - [Analyze](#analyze)
      - [Commit](#commit)
      - [Storybook](#storybook)
  - [Files organization](#files-organization)
  - [๐ค Contributing](#-contributing)
  - [Authors](#authors)
    - [๐๐ฝ Contact us](#-contact-us)

## Tech Stack

- โ [React](https://pt-br.reactjs.org/)
- ๐ [Typescript](https://www.typescriptlang.org/)
- ๐จ [Styled Components](https://styled-components.com/)
- ๐ฏ [Jest](https://jestjs.io/)
- ๐งช [React Testing Library](https://testing-library.com/docs/react-testing-library/intro)
- ๐ [Storybook](https://storybook.js.org/)
- ๐ [Eslint](https://eslint.org/)
- ๐ [Prettier](https://prettier.io/)
- ๐ถ [Husky](https://github.com/typicode/husky)
- ๐ซ [Lint-staged](https://github.com/okonet/lint-stageds)
- ๐ [Git-cz](https://github.com/streamich/git-cz)
- ๐ค [Webpack](https://webpack.js.org/)
- โก๏ธ [Babel](https://babeljs.io/)

## Status Project

๐ง Under construction... ๐ง

## ๐ Getting started

Before starting you need to know some patterns and flows followed within our project, they are:

### Read our workflow guideline

You can find it here: [WORKFLOW_GUIDELINE.md](docs/WORKFLOW_GUIDELINE.md).

### Read our naming guideline

You can find it here: [NAMING_GUIDELINE.md](docs/NAMING_GUIDELINE.md).

### Read our versioning guideline

You can find it here: [VERSIONING_GUIDELINE.md](docs/VERSIONING_GUIDELINE.md).

### Read our coding guideline

You can find it here: [CODING_GUIDELINE.md](docs/CODING_GUIDELINE.md).

### Read our git flow guideline

You can find it here: [GIT_FLOW_GUIDELINE.md](docs/GIT_FLOW_GUIDELINE.md).

And for local development, you will need to have the following tools installed on your machine:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).
Besides, it's nice to have an editor to work with code like [VSCode](https://code.visualstudio.com/)

### ๐ฒ Explanation of main scripts

#### Start

React uses Node.js on development to open the app on `http://localhost:3000`, thus the start script enables you to start the server.

You can run the start script command on the terminal with either npm or yarn.

```bash
  yarn start
```

Or, if youโre using npm:

```bash
  npm start
```

This command will not only start the server, but it will also react and display the latest version each time a change occurs. In addition, it will show lint errors on the terminal (console) when it fails to start the server in the form of meaningful error messages.

#### Test

This template uses Jest as a test runner. The test script enables you to launch the test runner in interactive watch mode. I wonโt dive too deep into testing React apps, but keep in mind that any file with .test.js or .spec.js extensions will be executed when the script is launched.

The test script can be run on the terminal with the following commands.

```bash
  yarn test
```

npm:

```bash
  npm test
```

You can run derivations for this command as:

```bash
  # Watch files for changes and rerun tests related to changed files.
  yarn test:watch

  # Indicates that test coverage information should be collected and reported in the output.
  yarn test:coverage
```

#### Build

React is modular, which is why you can create several files or components if you want to. These separate files need to be merged or bundled to be precise in one single file.

Thatโs one of the major benefits of the build script. The other is performance; as you know, a development mode is not optimized. And React uses the build script to ensures that the finished project is bundled, minified and optimized with best practices.

The script can be run with the following commands.

```bash
  yarn test
```

npm:

```bash
  npm test
```

#### Generate

You can use this command to generate files with a default initial structure adopted for this template.

The script can be run with the following commands.

```bash
  yarn generate <desired component name>
```

As a result, a structure of folders and files will be generated as suggested in the default template inside the src/components folder with the following structure:

```txt
  - components (must contain the specific components that can be reused throughout the application)
    - <Desired component name> (directory that will contain the entire structure of the component)
      - index.tsx (file that will contain the entire structure of the component)
      - styles.ts (file containing the component's styling)
      - test.tsx (file containing the unit tests for the component)
      - story.tsx (file containing example usage of the component generated with the storybook library)
    - index.ts (must export all components)
```

#### Eslint

Statically analyzes your code to quickly find problems.

```bash
  yarn eslint
```

#### Prettier

An opinionated code formatter.

```bash
  yarn prettier
```

#### Analyze

Responsible for analyzing the application's final bundle.

```bash
  yarn analyze
```

#### Commit

Starts in the terminal interactively a pattern of commits used in this template.

```bash
  yarn commit
```

#### Storybook

It will start Storybook locally and output the address. Depending on your system configuration, it will automatically open the address in a new browser tab.

```bash
  yarn storybook
```

## Files organization

The organization of project folders and files is described below.

```txt
  - components (must contain the specific components that can be reused throughout the application)
      - index.ts (must export all components)
```

## ๐ค Contributing

1. Fork this repository;
2. Create your branch: `git checkout -b type/my-new-feature`;
3. Commit your changes: `yarn commit`;
4. Push to the branch: `git push origin type/my-new-feature`.

**After your pull request is merged**, you can safely delete your branch.

## Authors

Made with โค๏ธ by Kallรฉo Pinheiro - Realwave Team

### ๐๐ฝ Contact us

windson.rocha@zup.com.br
