<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@vue/compiler-core](./compiler-core.md) &gt; [CodegenOptions](./compiler-core.codegenoptions.md)

## CodegenOptions interface

<b>Signature:</b>

```typescript
export interface CodegenOptions 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [bindingMetadata](./compiler-core.codegenoptions.bindingmetadata.md) | [BindingMetadata](./compiler-core.bindingmetadata.md) |  |
|  [filename](./compiler-core.codegenoptions.filename.md) | string | Filename for source map generation.  'template.vue.html' |
|  [mode](./compiler-core.codegenoptions.mode.md) | 'module' \| 'function' | - <code>module</code> mode will generate ES module import statements for helpers and export the render function as the default export. - <code>function</code> mode will generate a single <code>const { helpers... } = Vue</code> statement and return the render function. It expects <code>Vue</code> to be globally available (or passed by wrapping the code with an IIFE). It is meant to be used with <code>new Function(code)()</code> to generate a render function at runtime.  'function' |
|  [optimizeImports](./compiler-core.codegenoptions.optimizeimports.md) | boolean | Option to optimize helper import bindings via variable assignment (only used for webpack code-split)  false |
|  [prefixIdentifiers](./compiler-core.codegenoptions.prefixidentifiers.md) | boolean |  |
|  [runtimeGlobalName](./compiler-core.codegenoptions.runtimeglobalname.md) | string | Customize the global variable name of <code>Vue</code> to get helpers from in function mode  'Vue' |
|  [runtimeModuleName](./compiler-core.codegenoptions.runtimemodulename.md) | string | Customize where to import runtime helpers from.  'vue' |
|  [scopeId](./compiler-core.codegenoptions.scopeid.md) | string \| null | SFC scoped styles ID |
|  [sourceMap](./compiler-core.codegenoptions.sourcemap.md) | boolean | Generate source map?  false |
|  [ssr](./compiler-core.codegenoptions.ssr.md) | boolean |  |

