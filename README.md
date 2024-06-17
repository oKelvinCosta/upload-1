# with vite 2 (upload-1)

A Quasar Project

## Install the dependencies
```bash
yarn
# or
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```


### Build the app for production
```bash
quasar build
```

### Customize the configuration
See [Configuring quasar.config.js](https://v2.quasar.dev/quasar-cli-vite/quasar-config-js).


Passo a passo de como dar deploy de aplicações Quasar no github pages no modo vueRouterMode history.
Processo que mantém os arquivos de desenvolvimento juntos mas mantém a lógica se for separar.



This command will build your project in SPA mode and output your production ready bundle to a newly created folder /dist/spa

No arquivo .gitignore
Excluir linha que contém /dist


No arquivo quasar.config.js

Add no build:
PublicPath '/prodemge/dist/spa'
Utilize o caminho de onde está o index.html do build

DistDir: 'dist/spa'


Quando for dar build
quasar build

Palavras chaves: vue rota history quasar hospedar publicar
