# Gerando uma aplicação Web com React Native

> **Note**: Pré-requisito: [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup)

## Rodando o projeto localmente

### Passo 1: Instalar dependencias

```bash
# usando npm
npm install --legacy-peer-deps
```

### Passo 2: Rodar a aplicação no browser

```bash
npm run web
```

Aguardar a aplicação compilar e abrir em uma aba do navegador padrão do sistema.

### Passo 3: Rodando em emulador Android

Pré-requisito, instalar o Android Studio e ter um emulador Android criado no AVD.

```bash
npm run start
```

Em seguida, selecionar a opção **a - run on Android**. Em pouco tempo, o emulador Android irá inicializar, e a aplicação irá ser instalada no dispositivo. Caso dê timeout (por causa da inicialização do dispositivo e instalação da aplicação), no Metro, pode selecionar a opção **r - reload the app** para recarregar a aplicação.

## Testando o site previamente publicado no GitHub Pages

Acessar o site https://walterotferreira.github.io/ReactNativeWeb .

O site foi previamente publicado através dos comandos:

```bash
npm run predeploy
npm run deploy
```
