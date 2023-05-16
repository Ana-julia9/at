# <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gerenciador de Contatos</title>
    <style>
        input[type="text"], input[type="tel"] {
        margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <h1>Gerenciador de Contatos</h1>

    <h2>Adicionar Contato</h2>
    <label for="name">Nome:</label>
    <input type="text" id="name" placeholder="Nome">
    <br>
    <label for="phone">Telefone:</label>
    <input type="tel" id="phone" placeholder="Telefone">
    <br>
    <button onclick="adicionarContato()">Adicionar</button>

    <h2>Buscar Nome</h2>
    <label for="searchName">Nome:</label>
    <input type="text" id="searchName" placeholder="Nome">
    <br>
    <button onclick="buscarContato()">Buscar</button>

    <h2>Lista de Contatos</h2>
    <ul id="contactList"></ul>

    <h2>Remover Contato</h2>
    <label for="removeName">Nome:</label>
    <input type="text" id="removeName" placeholder="Nome">
    <br>
    <button onclick="removerContato()">Remover</button>

    <h2>Atualizar Contato</h2>
    <label for="updateName">Nome:</label>
    <input type="text" id="updateName" placeholder="Nome">
    <br>
    <label for="updatePhone">Telefone:</label>
    <input type="tel" id="updatePhone" placeholder="Telefone">
    <br>
    <button onclick="atualizarContato()">Atualizar</button>

    
    <script src="/atividade/script.js"></script>
</body>

</html>
