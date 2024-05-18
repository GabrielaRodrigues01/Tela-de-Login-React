# React + Vite

Tela de login desenvolvida com React e Vite. 

**1- Configuração do ambiente de desenvolvimento:**

Para realizar esse projeto foi necessário ter o Node.js e o npm instalados, em seguida criar um novo diretório para o projeto, navegar ate esse diretório e inicializar um novo projeto npm. 

Instalei o Vite globalmente utilizando o comando (create-vite .), e criei um novo projeto Vite dentro do diretório do projeto, selecionei a opção de utilizar react e depois javascript e logo em seguida utilizei mais dois comandos sendo eles (npm install), para instalar todas as dependências necessárias do projeto e o comando (npm run dev), para iniciar o servidor de desenolvimento. 

Após instalar todas as dependências e configurar o ambiente de desenvolvimento, consegui ter uma estrutura básica do projeto, e fui limpando o que não iria utilizar e criar minha própria estrtura de pastas e arquivos. Eu retirei tudo que estava no index.css onde vem todos os estilos globais pois criei os meus, e também limpei o que não precisava utilizar do app.jsx como os states e imports. 

**2- Componente de formulário de Login:**

Dentro da pasta source do projeto eu criei uma outra pasta chamada de (components), e dentro dela criei mais uma pasta para alocar separadamente os componentes necessários que utilizei sendo ela a pasta (login), onde utilizei ela para separar por dois arquivos, o de login que é o principal (login.jsx), e o (login.css) onde deixei para colocar os estilos da parte do formulário. 

Para me auxiliar melhor no desenvolvimento utilizei a extensão 'ES7 React/Redux/GraphQL/React-Native snippets' pois ela fornece um conjunto de atalhos que torna a criação de componentes mais fácil.

No login.jsx modelei o componente de formulário e implementei a funcionalidade de envio do formulário com o evento (OnSubmit), e o (OnChange), para mapear os dados do usuário em cada campo e salvá-los no hook 'useState'. 

**3- Estilização com CSS:**

Para estilizar o projeto utilizei CSS para deixar a tela mais atrativa. 

**4- Execução do projeto:**

Para executar o projeto é necessário utilizar o comando 'npm run dev', ele vai iniciar um servidor e vai abrir a aplicação em seu navegador padrão. 






