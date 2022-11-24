# Servicenow-Nowlearning
Esse repositório contém os exercícios resolvidos do learning path: "flow designer essentials"

# Social Media Comment Checker
É um subflow que verifica se existem mais de 3 records com avaliação negativa de um mesmo source e o com prioridade alta, se sim ele ira criar um registro na tabela 
problema do aplicativo com a lista dos records na lista dos registros relacionados. Caso já exista um registro de problema na tabela problema
o flow ira atualizar-lo com a lista de registros atualizada.

Exemplo: Suponhamos que mais de três registros novos sejam cadastrados na tabela monitor com comentários negativos e criticos no youtube sobre ou produto ou serviço
fornecido pela companhia, o flow Social Media Comment Checker ira verificar se já existe um registro na tabela problema com o source youtube. Se não ele ira criar
um novo registro na tabela problema para o source youtube e em seguida ira cadastrar os registros sobre o youtube na lista de registros relacionados ao problema. Se ja 
existir um registro na tabela problema o flow ira verificar a lista de registros relacionados e ira atualizar a lista inserindo os novos registros criados se houver.


# Create cupon code
É um custom action que gera um cupom de desconto para o usuário que registrou a reclamação, e retorna esse cupom no field work notes com o seguinte texto: "thank you 
for share your experience, here your discount code: "
