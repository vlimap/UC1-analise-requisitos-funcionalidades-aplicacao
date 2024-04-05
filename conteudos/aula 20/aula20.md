## Aula 20: Controle de Versão e Colaboração

### Objetivos:
- Compreender o uso de sistemas de controle de versão como Git para gerenciamento de código.
- Aprender estratégias de colaboração em equipes de desenvolvimento.

### Introdução ao Git:

1. **Instalação do Git:**
   - Baixe e instale o Git de acordo com seu sistema operacional (Windows, Linux ou macOS) seguindo as instruções do site oficial [Git SCM](https://git-scm.com/download/win).

2. **Configuração Inicial:**
   - Configure seu nome de usuário e e-mail com os comandos:
     ```
     git config --global user.name "Seu Nome"
     git config --global user.email "seuemail@example.com"
     ```

3. **Criação de um Repositório Git:**
   - Inicie um repositório Git em seu projeto com o comando:
     ```
     git init
     ```

4. **Adição de Arquivos:**
   - Adicione arquivos ao controle de versão com:
     ```
     git add nome-do-arquivo
     ```

5. **Commit:**
   - Faça um commit das alterações com uma mensagem descritiva:
     ```
     git commit -m "Sua mensagem de commit aqui"
     ```

6. **Histórico de Commits:**
   - Visualize o histórico de commits com:
     ```
     git log
     ```

### Estratégias de Colaboração:

1. **Branches:**
   - Crie ramificações (branches) para trabalhar em novas funcionalidades ou correções sem afetar a linha principal (main) do projeto.

2. **Merges:**
   - Combine as alterações de diferentes branches de volta à linha principal com merges.

3. **Pull Requests:**
   - Use pull requests em plataformas como GitHub para revisar e discutir alterações antes de integrá-las ao projeto principal.

4. **Code Reviews:**
   - Realize revisões de código para garantir a qualidade e a consistência do código antes de mesclar alterações.

### Atividade Prática: Colaboração em um Projeto

1. **Clonar um Repositório:**
   - Clone um repositório existente para começar a colaborar em um projeto.
     ```
     git clone url-do-repositório
     ```

2. **Trabalhando com Branches:**
   - Crie uma nova branch para desenvolver uma nova funcionalidade.
     ```
     git branch nome-da-branch
     git checkout nome-da-branch
     ```

3. **Enviando Alterações:**
   - Faça commits e envie suas alterações para o repositório remoto.
     ```
     git push origin nome-da-branch
     ```

4. **Criando Pull Requests:**
   - Abra um pull request no GitHub para propor suas alterações ao projeto principal.

5. **Revisão e Merge:**
   - Revise as alterações em pull requests e faça o merge para integrá-las ao projeto principal.

### Conclusão:
- O controle de versão e a colaboração são aspectos fundamentais do desenvolvimento de software moderno. O uso de sistemas como Git e práticas colaborativas permite que equipes trabalhem de forma mais eficiente e mantenham a qualidade do código.

### Recursos Adicionais:
- [O que é Git e Github: como configurar e primeiros passos | Alura](https://www.alura.com.br/artigos/o-que-e-git-e-github)
- [Guia Completo de Git e Github - DevMedia](https://www.devmedia.com.br/guia/git-e-github/38148)
- [Jogo Interativo para Aprender Git](https://learngitbranching.js.org/?locale=pt_BR)

