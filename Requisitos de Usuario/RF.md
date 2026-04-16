
# 1. Requisitos Funcionais

<p align="justify">A <i>Tabela 1</i> a seguir contém os Requisitos Funcionais (RF) elicitados utizando a técnica de Brainstorm.</p>

| ID   |                                 Requisito                                 | Prioridade | Requisitos Relacionados |
| :--: | :-----------------------------------------------------------------------: | :--------: | :---------:|
| RF01 |              O usuário deve poder cadastrar novos produtos                |  Alta      |  RF03,RF09 |
| RF02 |           O usuário deve poder atualizar quantidade em estoque            |  Alta      | RF03, RF10, RNF03|
| RF03 |              O usuário deve poder listar produtos e quantidades           |  Média     | RF01, RF02, RF09|
| RF04 |                 O usuário deve poder cadastrar clientes                   |  Média     | RF05,RF0,RF09|
| RF05 |        O usuário deve poder listar clientes cadastrados                   |  Média     | RF04,RF06|
| RF06 |       O usuário deve poder excluir clientes                               |  Baixa     | RF04,RF05|
| RF07 |              O usuário deve poder cadastrastrar funcionários              |  Média     |  RF08,RF09|
| RF08 |           O usuário deve poder excluir funcionários                       |  Baixa     | RF07,RF09|
| RF09 |              O usuário deve poder efetuar uma venda                       |  Alta      | RF01,RF04,RF07,RF10,RF12|
| RF10 |                 O usuário deve atualizar estoque automaticamente          |  Alta      | RF02,RF09,RNF03|
| RF11 |        O usuário deve poder listar histórico de clientes                  |  Média     | RF09,RF12|
| RF12 |       O usuário deve poder gerar nota fiscal de venda                     |  Baixa     | RF09,RF11|


<div style="text-align: center">
  
<p>Tabela 1: Requisitos Funcionais</p>
</div>

# 2. Requisitos Não-Funcionais

<p align="justify">A <i>Tabela 2</i> a seguir contém os Requisitos Não-Funcionais (RNF) elicitados utizando a técnica de Brainstorm.</p>

| ID   |                                 Requisito                                 | Prioridade | Requisitos Relacionados |
| :--: | :-----------------------------------------------------------------------: | :--------: | :---------:|
| RF01 |              A interface deve ser Responsiva (Mobile)                     |  Alta      |  Todos os RFs |
| RF02 |           O sistema deve ter um desempenho (Carga < 2s)                   |  Média     | RF03,RF05,RF11|
| RF03 |              O sistema deve impedir estoque negativa                      |  Alta      | RF02,RF10|
| RF04 |                 O sistema deve ter compatibilidade (Navegadores)          |  Média     | Todos os RFs|
| RF05 |        O sistema deve possuir autenticação de usuários                    |  Alta      | RF06,RF08,RF09|


<div style="text-align: center">
<p>Tabela 2: Requisitos Não-Funcionais</p>
</div>

# 2. Referências


<a href="../README.md">VOLTAR INÍCIO</a>

