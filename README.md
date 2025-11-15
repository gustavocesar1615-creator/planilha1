<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Jogo da Normalização dos Dados Bagunçados</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f2f2f2;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            margin-bottom: 30px;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid #bbb;
        }
        th, td {
            padding: 12px;
            text-align: left;
        }
        th {
            background: #e3e3e3;
        }
        .section-title {
            font-size: 20px;
            margin-top: 30px;
            margin-bottom: 10px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>O Jogo da Normalização dos Dados Bagunçados</h1>
        <p><strong>Conceito Principal:</strong> Normalização de Bancos de Dados (1FN, 2FN, 3FN).</p>

        <table>
            <tr>
                <th>Aspecto</th>
                <th>Descrição</th>
            </tr>
            <tr>
                <td><strong>Cenário</strong></td>
                <td>Uma planilha desorganizada e repetitiva (ex: inventário de biblioteca ou coleção de jogos).</td>
            </tr>
            <tr>
                <td><strong>Interatividade</strong></td>
                <td>O visitante recebe um conjunto de cartões (registros) e é desafiado a organizá-los em grupos (tabelas) seguindo as "regras de normalização" para eliminar repetições.</td>
            </tr>
            <tr>
                <td><strong>Dinâmica</strong></td>
                <td>Use cores e formas para representar as tabelas. O visitante precisa identificar onde os dados estão repetidos e separá-los em novas tabelas, interligando-as com uma <strong>Chave Estrangeira</strong> (peças de LEGO ou ímãs). Os alunos guiam o processo mostrando como a repetição causa problemas ao tentar mudar dados como autor ou nome de um item.</td>
            </tr>
            <tr>
                <td><strong>Ponto Alto</strong></td>
                <td>O projeto mostra a diferença de espaço/eficiência entre as tabelas iniciais bagunçadas e as tabelas normalizadas.</td>
            </tr>
        </table>
    </div>
</body>
</html>
