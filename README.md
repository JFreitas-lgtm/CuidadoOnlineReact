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

## Executar

```bash
npm install
npm start
```

Depois, escaneie o QR Code com o Expo Go ou pressione `a` para Android e `w` para web.

## Estrutura principal

- `src/app/`: telas e navegação com Expo Router.
- `src/components/`: componentes reutilizáveis.
- `src/context/`: estado compartilhado da aplicação.
- `src/data/`: conteúdo educativo temporário.
- `src/theme.js`: cores da identidade visual.
