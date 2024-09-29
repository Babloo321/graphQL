<h1>############GRAPH-QL AND APOLLO SERVER###########</h1>
<p>Graphql is a query language</p>
<p>It is alternative of <strong>REST api</strong></p>
<br />
<h1>#############REST API#############</h1>
<p>REST api Create overfetching problem</p>
<h3>OverFetching</h3>
<p>Let's we have some user's data</p>
<table>
  <thead>
    <tr>
      <td>id</td>
      <td>firstName</td>
      <td>lastName</td>
      <td>email</td>
      <td>password</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Babloo</td>
      <td>Kumar</td>
      <td>babloo@babloo.com</td>
      <td>12345</td>
    </tr>
     <tr>
      <td>2</td>
      <td>Rahul</td>
      <td>Kumar</td>
      <td>rahul@rahul.com</td>
      <td>12345</td>
    </tr>
  </tbody>
</table>
<p>If we fetch some data from server and we want only user firstName and lastName </p>
<p>In case Rest api fetch user's all data, but we want only user's firstName and lastName, here Rest api introduce <strong>OVERFETCHING</strong></p>
<hr />
<h3>To solve <strong>OVERFETCHING and UNDERFETCHING</strong> we used <strong>GRAPHQL</strong></h3>
<p><strong>REST API have various endpoint for various request</strong></p>
<p><strong>GRAPHQL has only one enpoint i.e., POST</strong></p>
