<h1>ProductManager_API-Restful</h1>
<h3>API de gerenciamente de produtos</h3>
<h3>Funções:</h3>
<ul>
  <li>Postagem de produtos;</li>
  <li>Visualização de todos os produtos;</li>
  <ul>
     <li>Link de cada produto.</li>
  </ul>
  <li>Visualização de um único produto;</li>
  <ul>
     <li>Link de todos os produtos.</li>
  </ul>
  <li>Excluir produto;</li>
  <li>Modificar produto;</li>
  <li>Identificação (ID) de cada produto.</li>
</ul>
<h3>Observações:</h3>
<p>Antes de utilizar a API certifiquece de colocar a URL JDBC, Username (Padrão: postgres) e Senha (Password) no arquivo de texto "application"</p>
<p>Caminho: (<code>src\main\resources</code>)</p>
<h3>Comandos:</h3>
<ul>
  <li><code>/products</code> - POST - Postagem de produtos;</li>
  <li><code>/products</code> - GET - Visualização de todos os produtos;</li>
  <li><code>/products/{id}</code> - GET - Visualização de um único produto;</li>
  <li><code>/products/{id}</code> - DEL - Excluir produto;</li>
  <li><code>/products/{id}</code> - PUT - Modificar produto.</li>
</ul>
