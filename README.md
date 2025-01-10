## Overview

Easyreadme streamlines README creation, leveraging AI to craft visually appealing documentation with elegant templates. Simplify your project communication effortlessly.

## Project Structure

```bash

  ├── .env.example
  ├── LICENSE
  ├── README.md
  ├── bun.lockb
  ├── next.config.js
  ├── package.json
  ├── src
  │   ├── app
  │   │   ├── api
  │   │   │   ├── rate-limit
  │   │   │   │   └── route.ts
  │   │   │   └── remaining
  │   │   │       └── route.ts
  │   │   ├── builder
  │   │   │   └── page.tsx
  │   │   └── page.tsx
  │   ├── components
  │   │   ├── code-block.tsx
  │   │   ├── copy-button.tsx
  │   │   └── ui
  │   │       ├── button.tsx
  │   │       └── tabs.tsx
  │   └── utils
  │       ├── prompts.ts
  │       └── repository-template.ts
  ├── tailwind.config.ts
  └── tsconfig.json

```

## Project Summary

- [src](src): Main source code directory for the TypeScript project.
- [src/app](src/app): Application-specific code and functionalities.
- [src/components](src/components): Reusable UI components for the application.
- [src/services](src/services): Services providing specific functionalities to the application.
- [src/styles](src/styles): Styling configurations and global styles for the project.
- [public](public): Public assets and resources accessible from the application.
- [public/hero](public/hero): Hero images or visuals for the project's landing or main page.
- [src/utils](src/utils): Utility functions and helper modules for various tasks.

## Stack

- [@tiptap/core](https://www.tiptap.dev/): WYSIWYG editor framework for Vue.js and React.
- [swr](https://swr.vercel.app/): React Hooks library for data fetching.
- [zustand](https://zustand.surge.sh/): State management for React using Zustand.
- [tailwindcss](https://tailwindcss.com/): A utility-first CSS framework for rapid UI development.
- [next](https://nextjs.org/): React framework for building web applications with server-side rendering.

## Setting Up

#### OPENAI_API_KEY

- Visit the OpenAI website and sign in to your account.
- Navigate to the API section in your account settings.
- Generate a new API key for access to the GPT models.
- Copy the generated API key and securely store it.

#### GITHUB_ACCESS_TOKEN

- Log in to your GitHub account.
- Go to 'Settings' and navigate to 'Developer settings'.
- Select 'Personal access tokens' and generate a new token.
- Choose the required scopes for the token, e.g., 'repo' for repository access.
- Copy the generated token and store it securely.

#### KV_REST_API_URL

- Insert a guide.

#### KV_REST_API_TOKEN

- Insert a guide.

## Run Locally

1. Clone easyreadme repository:  
```bash  
git clone https://github.com/xavimondev/easyreadme  
```
2. Install the dependencies with one of the package managers listed below:  
```bash  
pnpm install  
bun install  
npm install  
yarn install  
```
3. Start the development mode:  
```bash  
pnpm dev  
bun dev  
npm run dev  
yarn dev  
```

## Deploy

Insert your application URL.

## License

This project is licensed under the **MIT** - see the [MIT](https://github.com/xavimondev/easyreadme/blob/main/LICENSE) file for details.

## Acknowledgements

- Thanks to [Lucide icons.](https://lucide.dev/)
- [Awesome Inspiration.](https://awesomeinsp.link)
- Thanks to this outstanding resource [Awesome Tool.](https://awesomeinsp.link)

## Api Reference

#### Get all products

```bash
GET /api/products
```

| Name | Type   | Optional | Description                                                                                                                                                                 |
| ---- | ------ | -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| term | string | required | Search term.![React](https://img.shields.io/badge/React-blue?logo=react&logoColor=white)
![Nextjs](https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white) |

## Changelog

#### [Version X.X.X] - YYYY-MM-DD

- New features or enhancements added in this release.
- Fixes to errors or problems

## Commands

This extension contributes the following commands to the Command palette:

- **Command name:** Command description.
- **Authenticate:** Command description.

## Contributors

[![Contributors](https://contrib.rocks/image?repo=xavimondev/easyreadme)](https://github.com/xavimondev/easyreadme/graphs/contributors)

## FAQ

#### 1.What is this project about?

This project aims to **briefly describe your project's purpose and goals.**

#### 2.How can I contribute to this project?

Yes, we welcome contributions! Please refer to our [Contribution Guidelines](CONTRIBUTING.md) for more information on how to contribute.

#### 3.What is this project about?

Your answer.

## Feedback

If you have any feedback, please reach out to us at [random@company.com](mailto:random@company.com).

## License

This project is licensed under the **MIT** - see the [MIT](https://github.com/xavimondev/easyreadme/blob/main/LICENSE) file for details.

## Monorepo Summary

### web

Insert a brief description of your workspace.

| Package      | Description                            |
| ------------ | -------------------------------------- |
| [ui](web/ui) | Insert a summary of your this package. |

## Prerequisites

- [Node](https://nodejs.org/en): Install following the instructions for your operating system. Then, open a new terminal and run `node --version`.
- [bun](https://bun.sh/docs/installation): To check that bun was installed successfully, open a new terminal window and run bun --version.
- [TypeScript](https://www.typescriptlang.org/download): Download and install following the instructions.
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git): Download and install Git following the instructions for your operating system. To check that Git was installed successfully, run `git --version`.
- [Visual Studio Code](https://code.visualstudio.com/): A lightweight powerful source code editor.

## Project Structure

```bash

  ├── .env.example
  ├── LICENSE
  ├── README.md
  ├── bun.lockb
  ├── next.config.js
  ├── package.json
  ├── src
  │   ├── app
  │   │   ├── api
  │   │   │   ├── rate-limit
  │   │   │   │   └── route.ts
  │   │   │   └── remaining
  │   │   │       └── route.ts
  │   │   ├── builder
  │   │   │   └── page.tsx
  │   │   └── page.tsx
  │   ├── components
  │   │   ├── code-block.tsx
  │   │   ├── copy-button.tsx
  │   │   └── ui
  │   │       ├── button.tsx
  │   │       └── tabs.tsx
  │   └── utils
  │       ├── prompts.ts
  │       └── repository-template.ts
  ├── tailwind.config.ts
  └── tsconfig.json

```

## Stack

- [@tiptap/core](https://www.tiptap.dev/): WYSIWYG editor framework for Vue.js and React.
- [swr](https://swr.vercel.app/): React Hooks library for data fetching.
- [zustand](https://zustand.surge.sh/): State management for React using Zustand.
- [tailwindcss](https://tailwindcss.com/): A utility-first CSS framework for rapid UI development.
- [next](https://nextjs.org/): React framework for building web applications with server-side rendering.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Project Summary](#project-summary)
- [Stack](#stack)
- [Setting Up](#setting-up)
- [Run Locally](#run-locally)
- [Deploy](#deploy)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Api Reference](#api-reference)
- [Changelog](#changelog)
- [Commands](#commands)
- [FAQ](#faq)
- [Feedback](#feedback)
- [License](#license)
- [Monorepo Summary](#monorepo-summary)
- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Stack](#stack)
