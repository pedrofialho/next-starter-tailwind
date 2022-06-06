# next-starter-tailwind

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Features

- [Typescript](https://www.typescriptlang.org)
- [EditorConfig](https://editorconfig.org/) for cross-editor coding style consistency
- [ESLint](https://eslint.org/) for static code analysis
- [Prettier](https://prettier.io/) for code formatting
- [classnames](https://github.com/JedWatson/classnames)

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

### Code Linting

```bash
npm run lint
# or
yarn lint
```

You can also fix all auto-fixable problems with `--fix`.

#### Suggested VS Code Settings

Additionally, you can install the [ESlint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) extension for VS Code and take advantage of automatic formatting/fixing:

```jsonc
// .vscode/settings.json
{
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) is also recommended, along with formatting on save:

```jsonc
// .vscode/settings.json
{
  "editor.formatOnSave": true
}
```

#### Configuration

The linter/formatter configuration is pretty great out of the box, but if needed these 3 configuration files can be customized:

- `.editorconfig` - Customize options like charset, EOL, indent type/size, etc. View [EditorConfig Properties](https://github.com/editorconfig/editorconfig/wiki/EditorConfig-Properties) for more info;
- `.prettierrc` - Customize advanced formatting rules. View [Prettier Docs](https://prettier.io/docs/en/index.html) for more info.
- `.eslintrc.json` - Customize static analysis rules. View [ESLint Rules](https://eslint.org/docs/rules/) for more info.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
