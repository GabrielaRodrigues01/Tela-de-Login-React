# React + Vite

Este projeto serve como um exemplo prático de como criar uma tela de login simples e eficaz utilizando as tecnologias React, Vite e JavaScript. O projeto demonstra os passos básicos para configurar o ambiente de desenvolvimento, criar componentes React, estilizar com CSS e executar o projeto localmente.

 Sinta-se à vontade para explorar o código-fonte, fazer contribuições ou utilizar como base para seus próprios projetos. 

**1- Configuração do ambiente de desenvolvimento:**

Para realizar esse projeto foi necessário ter o Node.js e o npm instalados, em seguida criar um novo diretório para o projeto, navegar ate esse diretório e inicializar um novo projeto npm. 

Instalei o Vite globalmente utilizando o comando (create-vite .), e criei um novo projeto Vite dentro do diretório que estava utilizando atualmente, selecionei a opção de utilizar react e depois javascript e logo em seguida utilizei mais dois comandos sendo eles o (npm install), para instalar todas as dependências necessárias do projeto e o comando (npm run dev), para iniciar o servidor de desenvolvimento. 

Após instalar todas as dependências e configurar o ambiente de desenvolvimento, consegui ter uma estrutura básica do projeto, e fui limpando o que não iria utilizar e criar minha própria estrutura de pastas e arquivos. Eu retirei tudo que estava no index.css onde vem todos os estilos globais pois criei os meus, e também limpei o que não precisava utilizar do app.jsx como os states e imports. 

**2- Componente de formulário de Login:**

Dentro da pasta source do projeto eu criei uma outra pasta chamada de (components), e dentro dela criei mais uma pasta para alocar separadamente os componentes necessários que utilizei sendo ela a pasta (login), onde utilizei ela para separar por dois arquivos, o de login que é o principal (login.jsx), e o (login.css) onde deixei para colocar os estilos da parte do formulário. 

Para me auxiliar melhor no desenvolvimento utilizei a extensão 'ES7 React/Redux/GraphQL/React-Native snippets' pois ela fornece um conjunto de atalhos que torna a criação de componentes mais fácil, e também utilizei uma biblioteca de ícones do react que instalei manualmente no meu arquivo (package.json) que é a '@react-icons/all-files'. 

No login.jsx modelei o componente de formulário e implementei a funcionalidade de envio do formulário com o evento (OnSubmit), e o (OnChange), para mapear os dados do usuário em cada campo e salvá-los no hook 'useState'. 

**3- Estilização com CSS:**

Para estilizar o projeto utilizei CSS para deixar a tela mais atrativa. 

**4- Execução do projeto:**

Para executar o projeto é necessário utilizar o comando 'npm run dev', ele vai iniciar um servidor e vai abrir a aplicação em seu navegador padrão. 






