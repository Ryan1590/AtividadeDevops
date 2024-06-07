# Documentação do Sistema de Cadastro, Login e Recuperação de Senha

## Índice
1. [Introdução](#introdução)
2. [Visão Geral do Sistema](#visão-geral-do-sistema)
3. [Arquivos e Estrutura](#arquivos-e-estrutura)
4. [Funcionalidades Principais](#funcionalidades-principais)
5. [Requisitos do Sistema](#requisitos-do-sistema)
6. [Guia de Instalação](#guia-de-instalação)
7. [Guia de Uso](#guia-de-uso)
8. [Segurança](#segurança)
9. [Manutenção e Suporte](#manutenção-e-suporte)
10. [Conclusão](#conclusão)

## Introdução
Esta documentação fornece uma descrição detalhada de um sistema web que inclui páginas de cadastro de usuário, login e recuperação de senha. O sistema é construído usando HTML, CSS e JavaScript, e faz uso do framework Bootstrap para estilização e responsividade.

## Visão Geral do Sistema
O sistema é composto por quatro páginas principais:
- **Cadastro de Novo Usuário**
- **Tela Principal**
- **Tela de Login**
- **Recuperação de Senha**

Cada página possui uma estrutura básica de cabeçalho e conteúdo centralizado, utilizando Bootstrap para garantir uma interface responsiva e agradável.

## Arquivos e Estrutura
- **cadastro.html**: Página de cadastro de novo usuário.
- **home.html**: Página principal após o login.
- **login.html**: Página de login.
- **redefinirSenha.html**: Página de recuperação de senha.
- **css/styles.css**: Arquivo de estilo adicional.
- **img/logo-ge.svg**: Logo utilizada nas páginas.
- **img/news1.jpg, img/news2.jpg, img/news3.jpg**: Imagens de notícias para o carrossel na página principal.

## Funcionalidades Principais
### Cadastro de Novo Usuário (`cadastro.html`)
- Formulário de cadastro com campos para nome completo, e-mail, nome de usuário, senha e confirmação de senha.
- Validação de senha para atender a requisitos específicos (uma letra maiúscula, um número, um caractere especial e pelo menos 8 caracteres).
- Verificação de correspondência de senhas.
- Exibição de mensagens de erro para campos inválidos.

### Tela Principal (`home.html`)
- Cabeçalho com logo, saudação ao usuário e menus de configurações e logout.
- Área para exibição de notícias da semana com funcionalidade de busca e carrossel de imagens.

### Tela de Login (`login.html`)
- Formulário de login com campos para e-mail e senha.
- Opção para visualizar a senha ao clicar no ícone de olho.
- Links para recuperação de senha e cadastro de novo usuário.

### Recuperação de Senha (`redefinirSenha.html`)
- Formulário para inserir o e-mail cadastrado e enviar a solicitação de recuperação de senha.
- Exibição de mensagem de confirmação após o envio.

## Requisitos do Sistema
### Requisitos de Hardware
- Um dispositivo com capacidade de rodar um navegador web moderno.

### Requisitos de Software
- Navegador web moderno (Google Chrome, Mozilla Firefox, Microsoft Edge, etc.).
- Conexão com a internet para carregar bibliotecas e frameworks externos.

## Guia de Instalação
1. Clone ou faça download do repositório contendo os arquivos HTML, CSS, e imagens.
2. Certifique-se de que todos os arquivos estejam na mesma pasta ou em suas respectivas pastas conforme especificado no código.
3. Abra qualquer um dos arquivos HTML em um navegador web para visualizar as páginas.

## Guia de Uso
### Cadastro de Novo Usuário
1. Abra `cadastro.html` em um navegador.
2. Preencha todos os campos do formulário de cadastro.
3. Clique em "Cadastrar" para enviar o formulário.
4. Se houver erros nos campos (como senhas que não coincidem ou senha que não atende aos requisitos), as mensagens de erro serão exibidas.
5. Após o sucesso, o usuário será redirecionado para a página de login (`login.html`).

### Tela de Login
1. Abra `login.html` em um navegador.
2. Insira o e-mail e senha cadastrados.
3. Clique em "Entrar" para fazer login.
4. Use o ícone de olho para alternar a visibilidade da senha, se necessário.
5. Utilize os links para recuperação de senha ou cadastro de novo usuário, se necessário.

### Recuperação de Senha
1. Abra `redefinirSenha.html` em um navegador.
2. Insira o e-mail cadastrado no campo apropriado.
3. Clique em "Enviar" para solicitar a recuperação de senha.
4. Uma mensagem de confirmação será exibida após o envio.

### Tela Principal
1. Após fazer login, o usuário será redirecionado para `home.html`.
2. Navegue pela página para ver as notícias da semana.
3. Use a barra de busca para procurar notícias específicas.
4. Navegue pelo carrossel de imagens de notícias usando os botões de anterior e próximo.

## Segurança
- As senhas devem atender a requisitos específicos para garantir a segurança.
- A exibição de senha no login pode ser alternada para melhorar a usabilidade, mantendo a segurança.
- As senhas não são armazenadas ou processadas no cliente, apenas enviadas ao servidor para verificação.

## Manutenção e Suporte
### Atualizações
- Verifique periodicamente se há atualizações para as bibliotecas e frameworks utilizados (Bootstrap, FontAwesome).

### Backup e Recuperação
- Mantenha backups dos arquivos HTML, CSS, e imagens.
- Garanta que os arquivos não sejam alterados sem um processo de controle de versão.

### Suporte Técnico
- Para problemas técnicos, consulte a documentação oficial do Bootstrap, FontAwesome, e outras bibliotecas utilizadas.
- Caso necessite de suporte adicional, entre em contato com a equipe de desenvolvimento responsável.

## Conclusão
Este documento forneceu uma visão detalhada do sistema web de cadastro, login e recuperação de senha, incluindo suas funcionalidades principais, estrutura de arquivos, e orientações de uso e manutenção. Para qualquer dúvida ou necessidade de suporte, consulte a equipe técnica.
