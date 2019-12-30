# Awesome Typescript Ecosystem [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> 😎 A list of awesome Typescript transformers, plugins, handbooks, etc

> As always,
> use caution when trying out Typescript transformers & plugins,
> especially those marked as 🔧 _experimental_ or 🔧🚧 _under construction_.

## Handbooks

- [typescript-book](https://github.com/basarat/typescript-book/) - 📚 The definitive guide to TypeScript and possibly the best TypeScript book 📖
- [ts-transformer-handbook](https://github.com/madou/ts-transformer-handbook) - 📘 A handbook on how to create transformers for Typescript with real code examples
- [TypeScript-Handbook](https://github.com/microsoft/TypeScript-Handbook) - The TypeScript Handbook is a comprehensive guide to the TypeScript language
- [TypeScript wiki](https://github.com/Microsoft/TypeScript/wiki)

## Transformers

Transformers are synonymous with Babel Plugins.
They enable transforming code from one to to another,
generally used for improving the developer experience,
doing performance optimizations,
and more.

### General transformers

- [ts-nameof](https://github.com/dsherret/ts-nameof) - nameof in TypeScript
- [ts-transform-json](https://github.com/longlho/ts-transform-json) - Inline specific values from a JSON file or the whole JSON blob
- [ts-transform-css-modules](https://github.com/longlho/ts-transform-css-modules) - Extract css class names from required css module files for TypeScript
- [ts-transform-img](https://github.com/longlho/ts-transform-img) - Allow `import * as img from 'foo.png'` in TS 
- [ts-transform-import-path-rewrite](https://github.com/dropbox/ts-transform-import-path-rewrite) - TS AST transformer to rewrite import path
- [ts-transform-graphql-tag](https://github.com/firede/ts-transform-graphql-tag) - Compiles GraphQL tagged template strings using graphql-tag in TypeScript files. 

### Module resolution

- [ts-transformer-imports](https://www.npmjs.com/package/ts-transformer-imports) - A TypeScript transformer which enables compilation of absolute imports (using baseUrl or paths) so they can be required as modules from Javascript or TypeScript, without additional configuration or path mapping

### React

- [react-hot-ts](https://www.npmjs.com/package/react-hot-ts) - A lightweight, Typescript-native, Babel-free, plugin-free, implementation of react-hot-loader
- [@avensia/oss/ts-transform-hoist-objects-in-props](https://www.npmjs.com/package/@avensia-oss/ts-transform-hoist-objects-in-props) - A TypeScript custom transformer that hoists object literals and functions that are passed to JSX props.
- [ts-transform-react-jsx-source](https://github.com/dropbox/ts-transform-react-jsx-source) - TypeScript AST Transformer that adds source file and line number to JSX elements 
- [ts-transform-react-constant-elements](https://github.com/dropbox/ts-transform-react-constant-elements) - A TypeScript AST Transformer that can speed up reconciliation and reduce garbage collection pressure by hoisting React elements to the highest possible scope

### i18n

- [@formatjs/ts-transformer](https://www.npmjs.com/package/@formatjs/ts-transformer) - Extracts string messages for translation from modules that use React Intl (similar to babel-plugin-react-intl)

### Types

- [ts-transformer-keys](https://www.npmjs.com/package/ts-transformer-keys) - A TypeScript custom transformer which enables to obtain keys of given type

### Testing

- [ts-auto-mock](https://www.npmjs.com/package/ts-auto-mock) - A Typescript transformer that will allow you to create mock for any types (Interfaces, Classes, ...) without need to create manual fakes/mocks.
- [jest-ts-auto-mock](https://github.com/Typescript-TDD/jest-ts-auto-mock) - Jest test utility with automatic mock creation for interfaces and classes

### Optimization

- [ts-transform-inferno](https://github.com/deamme/ts-transform-inferno) - Typescript transformer for InfernoJS 

## Language service plugins

Language service plugins enable rich developer experience warnings, errors, and even intellisense in your IDE.
Read [how to write your own langauge service plugin here](https://github.com/Microsoft/TypeScript/wiki/Writing-a-Language-Service-Plugin).

- [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin) - TypeScript Language Service Plugin for GraphQL developers 
- [typescript-styled-plugin](https://github.com/Microsoft/typescript-styled-plugin) - TypeScript server plugin that adds intellisense to styled component css strings
- [tslint-language-service](https://github.com/angelozerr/tslint-language-service/) - TypeScript 2.2.1 plugin for tslint 
- [ts-sql-plugin](https://github.com/xialvjun/ts-sql-plugin) -  TypeScript Language Service Plugin for SQL with a tagged template strings SQL builder
