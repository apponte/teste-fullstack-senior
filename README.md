# Teste Apponte - Fullstack Sênior
Desenvolver uma pequena API utilizando Node.js que será consumida por um APP simples em Ionic

## Instruções
- Siga as especificações abaixo.
- Crie um README com as instruções para compilar e rodar o projeto.
- O link do projeto deverá ser enviado ao término do prazo.

## Especificações tecnicas
- Criar uma rota onde podemos cadastrar um usuário com os campos: nome, email, senha, endereço, estado, cidade e descrição
- Criar uma autenticação utilizando JWT e Koa ou Express para as rotas
- Criar uma rota onde o acesso aos dados só será permitido para usuários autenticados
- Criar um app simples com o Ionic para consumir os dados da API
- Criar uma tela para cada rota: cadastrar usuário, login e perfil do usuário logado
- Utilizar MongoDB para armazenar os dados
- Testes automatizados é um diferencial

## Especificações funcionais
### Tela Inicial
A tela inicial deverá ser uma tela de login com dois botões: cadastro e login.
Ao clicar em "cadastro" deverá ir para uma tela com um formulário para cadastrar um usuário.
Ao clicar em "login" deverá ir para uma tela com um formulário para realizar o login na aplicação.

### Tela do perfil do usuário
Após realizar o login o usuário deverá ser redirecionado para esta tela, contendo todos os dados de seu perfil.
A tela também deverá ter um botão de logout.

## O que será avaliado?
- Organização do projeto
- Lógica do código
- Design das páginas
