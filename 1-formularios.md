# Formulários
O objetivo deste desafio é criar um formulário com HTML e CSS apenas, contendo validação dos campos de forma nativa e submetendo via POST os dados preenchidos.

## Desafio
Construa um formulário utilizando apenas HTML e CSS, garantindo que as regras de validação de cada campo seja seguida corretamente, sem uso de Javascript.
Cada campo obrigatório deve ser sinalizado de alguma maneira, podendo ser um * (asterisco) ou outra indicação.
O formulário precisa ter também dois botões: Limpar, Salvar, cada um seguindo funções padrões, sem necessidade de implementar Javascript.

## Contexto
O formulário a ser criado é um Formulário de Abertura de chamado de uma plataforma, e por isso, deve conter alguns campos que facilite o atendimento do agente.


### Os campos

| Campo | Obrigatório | Validações |
| :---- | :---------- | :--------- |
| Nome | Sim | Minimo 3 caracteres |
| E-mail | Sim | Valida se é e-mail válido |
| Início do problema | Sim | Data mínima 01/01/2022; data máxima 31/06/2022 |
| Tipo de solicitação | Sim | Deve ser um combo com a lista de problemas: Incidente, Visíta Técnica, Reclamação, Compra de Serviço |
| Prioridade | Não | Uma lista de seleção, podendo ser Radio ou Combo com as opção: Baixa, Média, Alta, Urgente |
| Assunto | Não | Mínimo 5 caracteres e máximo 20 caracteres |
| Descrição | Não | Mínimo 5 caracteres e máximo 100 caracteres |
| Anexos | Não | Permitir mais de um arquivo e os formatos jpg, png e pdf |

### Os botões
O formulário deve possuir dois botões:

* Salvar: deve validar os campos e, caso todas as regras sejam aceitas, submeter o formulário
* Cancelar: deve limpar todos os campos preenchidos

## Como enviar o projeto
Você pode desenvolver localmente ou criar no https://codepen.io/ seu código e enviar vi chat.
