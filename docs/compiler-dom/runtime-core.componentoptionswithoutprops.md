<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@vue/runtime-core](./runtime-core.md) &gt; [ComponentOptionsWithoutProps](./runtime-core.componentoptionswithoutprops.md)

## ComponentOptionsWithoutProps type

<b>Signature:</b>

```typescript
export declare type ComponentOptionsWithoutProps<Props = {}, RawBindings = {}, D = {}, C extends ComputedOptions = {}, M extends MethodOptions = {}, Mixin extends ComponentOptionsMixin = ComponentOptionsMixin, Extends extends ComponentOptionsMixin = ComponentOptionsMixin, E extends EmitsOptions = EmitsOptions, EE extends string = string> = ComponentOptionsBase<Props, RawBindings, D, C, M, Mixin, Extends, E, EE> & {
    props?: undefined;
} & ThisType<CreateComponentPublicInstance<{}, RawBindings, D, C, M, Mixin, Extends, E, Readonly<Props>>>;
```