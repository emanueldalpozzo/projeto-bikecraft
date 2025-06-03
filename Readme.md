# projeto-bikecraft
### Autor: Emanuel Ingles Dal Pozzo  
Este projeto tem por objeto implementar uma aplicação web inspirada em uma loja online de venda de bicicletas.

O frontend da aplicação foi desenvolvido com HTML, CSS e JavaScript e o backend foi simulado pela implementação de uma API Fake, usando o JSON Server.

## Design das Telas Figma:
       https://www.figma.com/design/OxqgDbiL1gRXjmqZZNndQQ/emanuel.2002-s-team-library?node-id=0-1&t=t0PkgUNDSmGv5IXY-1


## Design System: 
      https://www.figma.com/design/OxqgDbiL1gRXjmqZZNndQQ/emanuel.2002-s-team-library?node-id=2332-2&t=t0PkgUNDSmGv5IXY-1

## Site em Produção - GitHub Pages

## Framework CSS:
      https://materializecss.com/

## Dependências:
#### Materialize: 
      <link rel="stylesheet" href="./assets/libraries/materialize/css/materialize.css">
      <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>

#### Google Fonts - Poppins:
      <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

#### Google Material Icons:
      <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

#### jQuery:
      <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
      
#### Fetch API:
      https://jsonplaceholder.typicode.com/posts



## Checklist | Indicadores de Desempenho (ID) dos Resultados de Aprendizagem (RA)

### RA1 - Construir layouts responsivos e interativos utilizando técnicas avançadas de CSS
- [x] **ID 00** - Prototipa interfaces adaptáveis para no mínimo os tamanhos de tela mobile e desktop, usando ferramentas de design como Figma, Quant UX ou Sketch.
- [x] **ID 01** - Implementa um layout responsivo de uma página web utilizando um Framework CSS, como Bootstrap, Materialize ou Tailwind (com DaisyUI), aproveitando as técnicas de Flexbox ou Grid oferecidas pelo próprio framework, garantindo que o layout se adapte adequadamente a diferentes tamanhos de tela e dispositivos.
- [x] **ID 02** - Utiliza técnica de responsividade nativa de CSS, como Flexbox ou Grid Layout, para criar layouts responsivos e fluidos em diferentes resoluções de tela.
- [x] **ID 03** - Utiliza componentes CSS (ex. card, button ou outros) e JavaScript (ex. modal, carrousel ou outro) oferecidos por um Framework CSS.
- [x] **ID 04** - Implementa um layout fluido e responsivo utilizando unidades relativas (vw, vh, %, em ou rem) em vez de unidades fixas (px) em diferentes dispositivos e tamanhos de tela.
- [x] **ID 05** - Implementa animações em elementos da página, como fadeIn/fadeOut, slideIn/slideOut, utilizando CSS Animations ou bibliotecas de animação, como o Animate.css ou JQuery, para fornecer feedback visual ao usuário e criar uma experiência interativa.
- [x] **ID 07** - Aplica um Design System consistente, definindo diretrizes de estilo, cores, tipografia e padrões de componentes que são seguidos em toda a aplicação, garantindo uma experiência de usuário uniforme e atraente.
- [x] **ID 08** - Implementa pré-processadores CSS, como o Sass, em conjunto com um Framework CSS ou de forma isolada, para organizar e modularizar o código CSS, aplicando variáveis, mixins e funções para facilitar a manutenção e escalabilidade dos estilos.
- [x] **ID 09** - Aplica tipografia responsiva utilizando media queries ou a função clamp(), em conjunto com unidades relativas como rem, em ou vw, para ajustar o tamanho da fonte de acordo com diferentes tamanhos de tela.

### RA2 - Realizar tratamento de formulários e aplicar validações customizadas no lado cliente, utilizando a API do HTML e expressões regulares (REGEX).
- [ ] **ID 10** - Implementa tratamento de formulários no lado cliente com apresentação de mensagens de erro (texto próximo dos campos de entrada ou balões com mensagens) ou sucesso, utilizando os recursos da API do HTML, como validação de campos obrigatórios, tipo de entrada e limites de caracteres, garantindo que os dados inseridos sejam válidos antes de serem enviados para o servidor (via tratador de evento submit).
- [ ] **ID 11** - Aplica expressões regulares (REGEX) de forma eficiente para realizar validações customizadas nos campos de formulários, como formatos específicos de e-mail, telefone, data ou outros padrões personalizados definidos pelos requisitos do projeto.
- [ ] **ID 12** - Incorpora elementos de listagem, como checkbox, radio ou select, de maneira eficiente em formulários web, possibilitando a seleção e coleta precisa de dados pelos usuários.
- [ ] **ID 13** - Realiza a escrita e leitura de dados no Web Storage, permitindo a persistência de informações entre sessões de usuário e fornecendo uma maneira eficaz de armazenar dados localmente no navegador.

### RA3 - Aplicar ferramentas para otimização do processo de desenvolvimento web, incluindo Node.js, NPM e linters para garantir a qualidade do código, juntamento com boas práticas de versionamento e organização de projetos.
- [ ] **ID 14** - Configura adequadamente um ambiente de desenvolvimento usando Node.js e NPM para gerenciar pacotes e dependências do projeto, facilitando a instalação e o uso de bibliotecas e ferramentas de terceiros.
- [ ] **ID 16** - Adota boas práticas de versionamento utilizando sistemas como Git e GitHub, criando e gerenciando repositórios com branches adequados ou pelo menos o branch main.
- [ ] **ID 17** - Organiza o arquivo README.md conforme o template exigido na disciplina, contendo informações claras e estruturadas sobre o projeto, principalmente o checklist de tópicos devidamente preenchido.
- [ ] **ID 19** - Organiza os arquivos do projeto em uma estrutura coerente, lógica e modular, conforme projeto de exemplo, facilitando a localização, manutenção e escalabilidade.
      
### RA4 - Aplicar bibliotecas de funções e componentes em JavaScript para aprimorar a interatividade de páginas web.
- [ ] **ID 21** - Utiliza a biblioteca jQuery para manipular o DOM e aprimorar a interatividade das páginas web, implementando funcionalidades como eventos, animações e manipulação de elementos HTML de forma eficiente.
- [ ] **ID 22** - Seleciona e integra com sucesso um plugin jQuery, como o jQuery Mask Plugin ou outro plugin relevante para o projeto, a fim de melhorar a funcionalidade ou a aparência de elementos específicos em uma página web.
- [ ] **ID 23** - Utiliza bibliotecas de web components, como Lit, para criar componentes reutilizáveis e encapsulados, melhorando a modularidade e a manutenibilidade das páginas web.
- [ ] **ID 24** - Utiliza uma biblioteca de componentes prontos, como Material Web Components ou outra de escolha, ou então, algum componente independente (standalone) a fim de oferecer funcionalidades específicas sem a necessidade de estar integrado a uma biblioteca completa.

### RA5 - Efetuar requisições assíncronas para uma API fake e APIs públicas, permitindo a obtenção e manipulação de dados dinamicamente.
- [ ] **ID 25** - Realiza requisições assíncronas para uma API fake utilizando adequadamente conceitos como AJAX, Fetch API ou bibliotecas, para persistir os dados originados de um formulário.
- [ ] **ID 26** - Realiza requisições assíncronas para uma API fake utilizando adequadamente conceitos como AJAX, Fetch API ou bibliotecas, para exibição dos dados na página web.
