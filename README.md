# aulagit1
@@ -0,0 +1,101 @@
to-do-list-app/
├── index.html       # Estrutura HTML do aplicativo
├── style.css        # Estilos do aplicativo
├── script.js        # Lógica do aplicativo
├── README.md        # Documentação inicial
├── DEVLOG.md        # Log de desenvolvimento
└── Apresentação.pptx # Apresentação final (criada no final)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do List App</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>To-Do List</h1>
        <div class="input-section">
            <input type="text" id="taskInput" placeholder="Add a new task...">
            <button id="addTaskBtn">Add Task</button>
        </div>
        <ul id="taskList"></ul>
    </div>
    <script src="script.js"></script>
</body>
</html>
/* Estilo global */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
/* Estilo do container */
.container {
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    width: 300px;
}
/* Estilo do título */
h1 {
    text-align: center;
    color: #333;
}
/* Estilo da seção de entrada */
.input-section {
    display: flex;
    margin-bottom: 20px;
}
#taskInput {
    flex: 1;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    margin-right: 10px;
}
#addTaskBtn {
    padding: 10px 15px;
    background-color: #28a745;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}
#addTaskBtn:hover {
    background-color: #218838;
}
/* Estilo da lista de tarefas */
#taskList {
    list-style: none;
    padding: 0;
}
.task {
    display: flex;
    justify-content: space-between;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    margin-bottom: 10px;
    background: #f9f9f9;
}
.task.complete {
    text-decoration: line-through;
    color: #888;
}
git
