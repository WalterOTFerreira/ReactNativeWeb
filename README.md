# Gerando uma aplicação Web com React Native

>**Note**: Pré-requisito: [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup)

## Passo 1: Instalar dependencias

```bash
# usando npm
npm install --legacy-peer-deps
```

## Passo 2: Rodar a aplicação no browser

```bash
npm run web
```

Aguardar a aplicação compilar e abrir em uma aba do navegador padrão do sistema.

## Passo 3: Rodando em emulador Android

Pré-requisito, instalar o Android Studio e ter um emulador Android criado no AVD.
 
### For Android

```bash
npm run start
```

Em seguida, selecionar a opção **Android**. Em pouco tempo, o emulador Android irá inicializar, e a aplicação irá ser instalada no dispositivo. Caso dê timeout (por causa da inicialização do dispositivo e instalação da aplicação), no Metro, pode selecionar a opção **r** para recarregar a aplicação.
