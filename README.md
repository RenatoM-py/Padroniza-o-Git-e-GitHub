# PADRONIZAÇÃO 🧾

Estudos de padronização em GIT & GITHUB

## Tipo e descrição 📝

O commit semântico possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.

- `feat`- Commits do tipo feat indicam que seu trecho de código está incluindo um **novo recurso** (se relaciona com o MINOR do versionamento semântico).

- `fix` - Commits do tipo fix indicam que seu trecho de código commitado está **solucionando um problema** (bug fix), (se relaciona com o PATCH do versionamento semântico).

- `docs` - Commits do tipo docs indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

- `test` - Commits do tipo test são utilizados quando são realizadas **alterações em testes**, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)

- `build` - Commits do tipo build são utilizados quando são realizadas modificações em **arquivos de build e dependências**.

- `perf` - Commits do tipo perf servem para identificar quaisquer alterações de código que estejam relacionadas a **performance**.

- `style` - Commits do tipo style indicam que houveram alterações referentes a **formatações de código**, semicolons, trailing spaces, lint... (Não inclui alterações em código).

- `refactor` - Commits do tipo refactor referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

- `chore` - Commits do tipo chore indicam **atualizações de tarefas** de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)

- `ci` - Commits do tipo ci indicam mudanças relacionadas a **integração contínua** (_continuous integration_).

- `raw` - Commits do tipo raw indicam mudanças relacionadas a arquivos de configurações, dados, features, parâmetros.

- `cleanup` - Commits do tipo cleanup são utilizados para remover código comentado, trechos desnecessários ou qualquer outra forma de limpeza do código-fonte, visando aprimorar sua legibilidade e manutenibilidade.

- `remove` - Commits do tipo remove indicam a exclusão de arquivos, diretórios ou funcionalidades obsoletas ou não utilizadas, reduzindo o tamanho e a complexidade do projeto e mantendo-o mais organizado.


## Padrão + Comando 💻

[commit] 🎉: Commit inicial: 
```bash
git commit -m ":tada: Commit inicial"
```
[docs] 📚: Atualização do README
```bash
git commit -m ":books: docs: Atualização do README"
```	
[fix] 🐛: Loop infinito na linha 100
```bash 
git commit -m ":bug: fix: Loop infinito na linha 50"
```	
[feat] ✨: Página de login
```bash
git commit -m ":sparkles: feat: Página de login"
```
[ci] 🧱: Modificação no Dockerfile
```bash
git commit -m ":bricks: ci: Modificação no Dockerfile"
```
[refactor] ♻️: Passando para arrow functions
```bash
git commit -m ":recycle: refactor: Passando para arrow functions"
```	
[perf] ⚡: Melhoria no tempo de resposta
```bash
git commit -m ":zap: perf: Melhoria no tempo de resposta"
```	
[fix] 💥: Revertendo mudanças ineficientes
```bash
git commit -m ":boom: fix: Revertendo mudanças ineficientes"
```	
[feat] 💄: Estilização CSS do formulário
```bash
git commit -m ":lipstick: feat: Estilização CSS do formulário"
```	
[test] 🧪: Criando novo teste
```bash
git commit -m ":test_tube: test: Criando novo teste"	
```
[docs] 💡: Comentários sobre a função XXXXXXXX
```bash
git commit -m ":bulb: docs: Comentários sobre a função XXXXXXXX"
```	

## Fora do comum, mas utilizado:

[raw] 🗃️: RAW Data do ano aaaa
```bash
git commit -m ":card_file_box: raw: RAW Data do ano aaaa"
```
[cleanup] 🧹: Eliminado comentários e variáveis não usadas
```bash
git commit -m ":broom: cleanup: Eliminado comentários e variáveis não usadas"
```	
[remove] 🗑️: Removido arquivos não usados
```bash
git commit -m ":wastebasket: remove: Removido arquivos não usados"
```	
