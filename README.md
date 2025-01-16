# cronexia-test-nextjs-react-hook-forms


yep

[doc](https://nextjs.org/docs/app/getting-started/installation)

```bash
npx create-next-app@latest project
cd project/
bun dev
```

[doc](https://react-hook-form.com/get-started)

```bash
bun add react-hook-form
```

HS / The export useForm was not found in module

lié a [typescript ?](https://react-hook-form.com/ts) d'après so

https://stackoverflow.com/questions/72144671/how-to-resolve-the-error-module-react-hook-form-has-no-exported-member-use

Besoin de 

```ts
'use client';
```

en début de fichier

https://github.com/react-hook-form/react-hook-form/issues/11284#issuecomment-1850995149
https://react.dev/reference/rsc/use-client
