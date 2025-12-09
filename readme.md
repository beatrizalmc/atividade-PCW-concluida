# Classificados Online: Livros Usados (atividade)

## Sobre o Projeto
Este projeto foi desenvolvido como atividade avaliativa da disciplina Padrões para Conteúdos Web (PCW).
A proposta consiste em desenvolver uma plataforma onde as pessoas possam realizar a consulta (visualizar) e cadastrar anúncios de produtos e/ou serviços pela Internet. O tema ficou livre, então decidi escolher fazer um Classificados de Livros usados. 

## Arquitetura do Projeto
```
🗂️ Projeto-Classificados            
 ├── css/
 │    ├── style.css
 │    └── reset.css            
 ├── imagens/
 │    ├── 1984.jpg
 │    ├── hp.jpg
 │    ├── osol.jpg
 │    └── senhor.jpg
 ├── paginas/
 │    ├── index.html     
 │    ├── produtos.html             
 │    ├── detalhes1.html
 │    ├── detalhes2.html
 │    ├── detalhes3.html
 │    ├── detalhes4.html     
 │    ├── cadastro.html             
 │    └── portfolio.html
 └── readme.md       
```

## Páginas que compõem o site
- Página Inicial (index.html)
A página inicial apresenta:

Cabeçalho com nome da plataforma
Menu de navegação para todas as seções do site
Layout construído com Flexbox

- Página de Produtos (produtos.html)

Nesta página, o usuário pode visualizar 4 produtos/serviços já anunciados, cada um exibindo:

Imagem, Nome, Breve descrição, Botão “Ver detalhes” a qual redireciona para detalhes.html

Toda a estrutura é montada com Flexbox, garantindo boa organização visual.

- Página de Detalhes (detalhes.html) - como são 4 produtos separei por 'detalhes1' a 'detalhes4'

Ao clicar em um produto, o usuário é direcionado para esta página, que exibe:

Imagem ampliada, Título do anúncio, Descrição completa, Informações adicionais fornecidas pelo anunciante

- Cadastro de Anúncio (cadastro.html)

Nesta página, há um formulário para permitir o cadastro de novos produtos/serviços.
O formulário inclui campos como:

Nome do produto, Categoria, Preço, Descrição, etc.

A estilização foi feita com CSS e o layout segue padrões de responsividade.

- Página do Aluno – Portfólio (portfolio.html)

Página desenvolvida para apresentação pessoal, contendo:

Nome completo, Informações acadêmicas/profissionais, Links (LinkedIn e GitHub), Pequena descrição pessoal, etc.

## Tecnologias Utilizadas

- HTML5
- CSS3
- Flexbox
- Estrutura semântica

## Como Executar o Projeto

- Baixe os arquivos do repositório
- Extraia o conteúdo
- Abra o arquivo index.html no navegador
