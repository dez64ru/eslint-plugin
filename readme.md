# Eslint plugins and rules

## Configs

<details><summary>Base</summary>

### Extends

- [eslint:recommended](https://eslint.org/docs/latest/use/configure/configuration-files#using-eslintrecommended)
- [@typescript-eslint/eslint-recommended](https://github.com/typescript-eslint/typescript-eslint/blob/main/packages/eslint-plugin/src/configs/eslint-recommended.ts)
- [@typescript-eslint/recommended](https://github.com/typescript-eslint/typescript-eslint/blob/main/packages/eslint-plugin/src/configs/recommended.ts)
- [import/recommended](https://github.com/import-js/eslint-plugin-import#helpful-warnings)
- [import/typescript](https://github.com/import-js/eslint-plugin-import#helpful-warnings)

### Rules

- [jsx-multiline-paddings](/docs/jsx-multiline-paddings.md): `error`
- [prop-multiline-paddings](/docs/prop-multiline-paddings.md): `error`
- ["@typescript-eslint/no-empty-interface](/docs/jsx-multiline-paddings.md): `off`
- [padding-line-between-statements](https://eslint.org/docs/latest/rules/padding-line-between-statements): `adds paddings before return, between all multiline expressions`
</details>

<details><summary>React</summary>

### Extends

- Base
- [react/recommended](https://github.com/jsx-eslint/eslint-plugin-react#list-of-supported-rules)
- [react/jsx-runtime](https://github.com/jsx-eslint/eslint-plugin-react#list-of-supported-rules)
- [react-hooks/recommended](https://legacy.reactjs.org/docs/hooks-rules.html)

### Rules

- [react/react-in-jsx-scope](https://github.com/jsx-eslint/eslint-plugin-react/blob/master/docs/rules/react-in-jsx-scope.md): off

</details>

<details><summary>Next.js</summary>

> **note** WIP

### Extends

- React

### Rules

</details>

<details><summary>Electron</summary>

### Extends

- React
- [plugin:import/electron](https://github.com/import-js/eslint-plugin-import#helpful-warnings)

### Rules

</details>

## Rules

- [jsx-multiline-padding](/docs/jsx-multiline-paddings.md)
- [prop-multiline-paddings](/docs/prop-multiline-paddings.md)
