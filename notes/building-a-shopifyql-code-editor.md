---
title: "Building a ShopifyQL Code Editor"
link: https://shopify.engineering/building-a-shopifyql-code-editor
topics:
  - Frontend
year: 2023
---

Shopify needed ShopifyQL support in CodeMirror without rewriting the ANTLR grammar already shared by its client and server. The team built an adapter that converts language-server tokens into Lezer parse trees and connects validation, completion, and hover APIs to CodeMirror plugins. This enabled syntax highlighting, linting, autocomplete, and tooltips while retaining a single language grammar.
