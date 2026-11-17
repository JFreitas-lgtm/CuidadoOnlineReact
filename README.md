# CuidadOnline Mobile

Versão mobile do **CuidadOnline**, criada com React Native, JavaScript e Expo. Esta primeira etapa não usa banco de dados: os dados ficam somente no estado da aplicação enquanto ela está aberta.

## Telas implementadas

1. Login
2. Cadastro
3. Início
4. Aprender
5. Detalhe da leitura
6. Praticar

O projeto também contém componentes reutilizáveis para botões, campos de texto, cabeçalhos, cartões, contêiner de tela e menu inferior. Todos os estilos usam `StyleSheet`.

## Requisitos

Antes de começar, instale:

- [Node.js](https://nodejs.org/) 22.13 ou superior, que já inclui o npm.
- [Expo Go](https://expo.dev/go) no celular, caso queira executar o aplicativo em um aparelho Android ou iOS.

## Instalação e execução

Clone o repositório e entre na pasta do projeto:

```bash
git clone https://github.com/joaofreitas77/CuidadoOnlineReact.git
cd CuidadoOnlineReact
```

Instale exatamente as versões registradas no `package-lock.json`:

```bash
npm ci
```

Inicie o Expo:

```bash
npm start
```

Quando o Expo iniciar:

- Escaneie o QR Code com o aplicativo Expo Go para abrir no celular.
- Pressione `a` no terminal para abrir em um emulador Android já configurado.
- Pressione `w` no terminal para abrir no navegador.

Também é possível iniciar diretamente pelo terminal:

```bash
npm run android
npm run web
```

Para validar uma compilação web antes de publicar alterações:

```bash
npm run check
```

## Estrutura principal

- `src/app/`: telas e navegação com Expo Router.
- `src/components/`: componentes reutilizáveis.
- `src/context/`: estado compartilhado da aplicação.
- `src/data/`: conteúdo educativo temporário.
- `src/theme.js`: cores da identidade visual.

## Versionamento

Arquivos gerados, dependências, credenciais nativas e variáveis de ambiente não são enviados ao GitHub. Se o projeto passar a usar configurações locais, documente apenas nomes e valores fictícios em um arquivo `.env.example`.

Fluxo básico para publicar alterações:

```bash
git add .
git commit -m "descreva a alteração"
git push origin main
```
