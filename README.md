<!DOCTYPE html>
<html>
<body>
    <h1>Cats Nomad</h1>
    <h2>Descrição</h2>
    <p>Este é um repositório do projeto Cats Nomad, desenvolvido em React Native. O objetivo deste projeto é permitir que os usuários visualizem diferentes tipos de gatos e adicionem seus favoritos.</p>
<h2>Bibliotecas Utilizadas</h2>
<ul>
    <li><strong>React Navigation:</strong> Biblioteca de roteamento e navegação para React Native.</li>
    <li><strong>Axios:</strong> Biblioteca para realizar requisições HTTP.</li>
    <li><strong>Expo:</strong> Plataforma para desenvolvimento de aplicativos móveis com React Native.</li>
    <li><strong>Google Fonts:</strong> Biblioteca de fontes da web fornecida pelo Google.</li>
    <li><strong>TanStack React Query:</strong> Biblioteca para gerenciamento de estados e cache de dados.</li>
      <li><strong>Styled Components:</strong> Biblioteca para estilização de componentes com React Native.</li>
</ul>
<h2>Usuários</h2>
<p>O projeto inclui uma lista de usuários pré-definidos para fins de demonstração. Aqui estão os detalhes dos usuários disponíveis:</p>
<pre><code>
export const Users = [
{
id: '1',
fullName: 'Usuário Visitante',
email: 'user@gmail.com',
favorites: [],
},
{
id: '2',
fullName: 'João',
email: 'joao@gmail.com',
favorites: [],
},
{
id: '3',
fullName: 'Ana',
email: 'ana@gmail.com',
favorites: [],
},
];
</code></pre>
<h2>Contextos</h2>
<p>O projeto utiliza Contextos para gerenciar o estado global da aplicação. São utilizados os seguintes Contextos:</p>
<ul>
    <li><strong>AuthContext:</strong> Contexto responsável pela autenticação do usuário e gerenciamento do estado de login.</li>
</ul>
<p>Os Contextos são utilizados para fornecer os dados e funcionalidades necessárias para os componentes em toda a aplicação, evitando a necessidade de passar dados através de propriedades de forma direta.</p>
</body>
</html>
