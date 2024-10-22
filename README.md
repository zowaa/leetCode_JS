# 30 Days of JavaScript Challenge (LeetCode) - TypeScript Edition

This repository contains my solutions for the **30 Days of JavaScript** challenge on LeetCode, implemented in TypeScript.

## Environment Setup

I have set up my environment using the following tools to ensure smooth development with TypeScript, ESLint, and Prettier.

### I. npm

Initialize `npm` to manage dependencies:

```bash
npm init -y
```

### II. TypeScript

1- Install `TypeScript` globally:

```bash
npm install -g typescript
```

2- Initialize TypeScript configuration in the project:

```bash
tsc --init
```

3- A file `tsconfig.json`  is created with initial setup , that i changed

### III. ESLint

1- To maintain code quality, I installed ESLint along with TypeScript and Prettier support:

```bash
npm install --save-dev eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-plugin-import eslint-config-prettier
```

2- create `.eslintrc.json` file

### IV. Prettier

For code formatting, I installed Prettier as a development dependency:

```bash
npm install --save-dev prettier
```

### V. ts-node

To run TypeScript files directly without needing to compile them manually:

```bash
npm install -g ts-node
```

now you can use directly:
```bash
ts-node src/yourfile.ts
```

### For the lazy ones, you can simply run `npm init -y` to initialize npm and then install all necessary packages in one go. This will give you a quick start without needing to manually configure each step.

