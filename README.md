# Tiptap extension symbol

![GitHub License](https://img.shields.io/github/license/vueditor/tiptap-extension-symbol?style=plastic) ![NPM Version](https://img.shields.io/npm/v/%40vueditor%2Ftiptap-extension-symbol?style=plastic) ![NPM Downloads](https://img.shields.io/npm/dm/%40vueditor%2Ftiptap-extension-symbol?style=plastic)  ![GitHub Repo stars](https://img.shields.io/github/stars/vueditor/tiptap-extension-symbol?style=plastic)

A tiptap extension to  add symbols for nodes and marks, read the [docs](https://vueditor.litingyes.top/) to learn more.

## Installation

```bash
pnpm add @vueditor/tiptap-extension-symbol
```

or

```bash
npm install @vueditor/tiptap-extension-symbol
```

## Basic usage

> [!TIP]
> For more detailed usage，see the [examples](./examples/) directory or more comprehensive usage: [rich text editor](https://github.com/vueditor/rich-text-editor.git).

```ts
import { Editor } from '@tiptap/core'
import { symbol } from '@vueditor/tiptap-extension-symbol'

const editor = new Editor({
  extension: [symbol]
})
```

### Options

```ts
interface SymbolOptions {
  // whether to add name attribute for nodes and marks, default: true
  // usually used to customize the css style of nodes and marks
  enableName: boolean

  // whether to add unique ID attribute for nodes, default: true
  enableId: boolean
}
```
