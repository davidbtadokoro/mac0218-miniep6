---
# MAC0218 - MINIEP06
---
## Informações Gerais

**Nome: David de Barros Tadokoro
NUSP: 10300507
Prof.: Alfredo Goldman**

Este MINIEP06 foi feito como trabalho para a disciplina de MAC0218 (Técnicas de Programação II) do IME-USP no primeiro semestre de 2022.

O objetivo deste MINIEP06 era nos familiarizar com a plataforma Docker, criando uma imagem customizada de um servidor caddy, que servia uma simples página web.

## Conteúdo do repositório

Este repo deve conter os seguintes arquivos/diretórios
- `README.md`: &nbsp; (este arquivo);
- `pages/`: &nbsp; diretório com os objetos da página web;
- `Caddyfile`: &nbsp; arquivo de configuração do servidor Caddy;
- `Dockerfile`: &nbsp; arquivo de configuração da imagem Docker;
- `history.txt`: &nbsp; "log" dos comandos usados para criar a imagem e rodar o container.

## Execução do container

No estado atual do repositório, siga os comandos da Parte 2 descritos no arquivo `history.txt` para colocar o servidor no ar. É necessário que o ambiente de execução possua o Docker instalado

A porta de acesso está configurada para ser a 8080. Além disso, não há um `index.html` nos objetos da página. Assim, acesse a página em seu navegador de escolha com a seguinte URL:
`http://localhost:8080/produtos.html` ou similar.

## Observação

A página usada neste trabalho foi de minha autoria e foi criada acompanhando um  [curso online da Alura](https://cursos.alura.com.br/course/html5-css3-posicionamento-listas-navegacao) (o acesso só é possível se o usuário tiver uma inscrição da Alura).
