# trailerflix-frontend

## Configurando Ambiente

### Recomendações

Criar um Perfil (Profile) no VSCode para evitar que alguma configuração do settings.json, Eslint, Prettier, EditorConfig, dê conflitos

- Arquivo > Preferências > Perfil > Criar Perfil

---

### Tecnologias utilizadas
Para instalar as dependências:

```
npm install
```

- eslint
- prettier
- husky
- lint staged
- styled-components
  - jest-styled-components
- editor config
- storybook
- react router dom

---

### Extensões para instalar

- ESLint
  - https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
- Prettier - Code formatter
  - https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
- vscode-styled-components
  - https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components
- EditorConfig for VS Code
  - https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig


---

## Commits Semânticos

link para consulta: https://blog.geekhunter.com.br/o-que-e-commit-e-como-usar-commits-semanticos/

tipos:

1. build: alterações que afetam o sistema de construção ou dependências externas;
2. docs: referem-se a inclusão ou alteração somente de arquivos de documentação;
3. feat: tratam adições de novas funcionalidades ou de quaisquer outras novas implantações ao código;
4. fix: essencialmente definem o tratamento de correções de bugs;
5. perf: uma alteração de código que melhora o desempenho;
6. refactor: tipo utilizado em quaisquer mudanças que sejam executados no código, porém não alterem a funcionalidade final da tarefa impactada;
7. style: alterações referentes a formatações na apresentação do código que não afetam o significado do código;
8. test: adicionando testes ausentes ou corrigindo testes existentes nos processos de testes automatizados (TDD);
9. chore: atualização de tarefas que não ocasionam alteração no código de produção, mas mudanças de ferramentas, mudanças de configuração e bibliotecas que realmente não entram em produção;
10. env: utilizado na descrição de modificações ou adições em arquivos de configuração de parâmetros em arquivos de configuração.
11. ci: alteração nos scripts ou arquivos de configuração CI.
