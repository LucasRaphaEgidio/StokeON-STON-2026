
# 1. História de Usuário

A Tabela 3 a seguir contém as Histórias de Usuárias elicitadas. 

<table>
    <thead>
        <tr style="background-color: purple; color: white" >
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Critérios de aceitação</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">RF/RNF relacionado</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Story Points</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como
gerente, quero poder cadastrar novos produtos e atualizar o estoque para manter o inventário atualizado</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O formulário deve conter nome, categoria e valor.</li><li> Deve ser possível editar a quantidade existente.</li><li>Os dados devem ser salvos no banco de dados.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01, RF02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">5</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como vendedor, desejo listar os produtos e suas quantidades para consultar a disponibilidade aos clientes</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O sistema deve exibir uma tabela com Código, Nome, Valor e Quantidade.</li><li> A listagem deve refletir o banco de dados em tempo real.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Média </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como vendedor, desejo cadastrar, listar e excluir clientes para manter a base de contatos da loja organizada</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>Deve haver campos de CPF, Nome e Endereço.</li><li> A exclusão de um cliente deve pedir confirmação na tela.</li><li> Uma tabela deve exibir os clientes ativos. </li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF04, RF05, RF06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">8</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como administrado r, quero gerenciar os funcionários (cadastrar e excluir) para controlar quem tem acesso e atua nas vendas</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>O cadastro exige CPF, Nome e Matrícula.</li><li> Funcionários excluídos / inativados não podem aparecer na lista de vendedores na hora da venda.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Média </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF07, RF08.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">5</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como operador de caixa, quero efetuar uma nova venda adicionando itens ao carrinho para agilizar o atendimento</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>Deve ser possível buscar o cliente por CPF e o funcionário por nome.</li><li> O sistema deve calcular o valor total automaticamente conforme os itens adicionados.</li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> alta </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF09 </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">13</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como gerente, desejo que o estoque seja atualizado automaticam ente e nunca fique negativo para não furar o inventário </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li>Após registrar a venda, a quantidade deve ser deduzida do estoque.</li><li> O sistema deve impedir a adição de um item na venda se a quantidade solicitada for maior que o estoque. </li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> alta </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF10, RNF03.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">8</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US07</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como operador de caixa, quero gerar nota fiscal e listar o histórico do cliente para entregar o comprovante e ter registro</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li> O sistema deve gerar um número de NF único após a venda </li><li> Deve ser possível vusualizar as compras anteriores pesquisando o cliente. </li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Baixa </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF11, RF12 </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">5</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US08</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como funcionário, desejo passar por uma tela de autenticação para que o sistema fique seguro contra acessos indevidos. </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li> O usuário deve inserir login e senha. </li><li> Sem autenticação, o acesso às telas do sistema deve ser bloqueado. </li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Alta </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> RNF05 </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">5</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US09</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário do sistema, quero utilizar a plataforma pelo celular para realizar consultas direto dos corredores do depósito. </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol><li> O layout das telas e tabelas deve se adaptar a telas menores (Mobile). </li><li> O sistema deve carregar em menos de 2 segundos. </li></ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Alta </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> RNF01, RNF02, RNF04 </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">13</td>
            
</table>

<div style="text-align: center">
<p>Tabela 3: História de Usuário</p>
</div>

## 5. Referências bibliográficas
