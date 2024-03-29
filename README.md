# Churrascômetro - Calculadora de Churrasco

## Enunciado do projeto prático

### Objetivo

O objetivo desta atividade é desenvolver uma calculadora chamada "Churrascômetro" que tem o intuito de calcular os itens para um churrasco. A página deve funcionar em 3 passos, sendo que cada passo pode ser uma tela montada dinamicamente dentro do mesmo arquivo HTML ou simplesmente os componentes sendo atualizados dinamicamente.

### Requisitos

1. **Passo 1: Informações Iniciais**
   - Exibir 4 campos para digitar "nome, e-mail e CEP" além de checkbox de consentimento com o texto "aceito receber e-mails com promoções".
   - Os campos "nome", "e-mail" e CEP devem ser obrigatórios.
   - O campo "e-mail" deve conter um e-mail válido.
   - O checkbox deve ser carregado marcado automaticamente.
   - Indicação visual na tela caso algum campo esteja inválido.
   - Não solicitar novamente os campos preenchidos após a página ser recarregada.

2. **Passo 2: Quantidades de Participantes**
   - Contém 3 ou 4 campos para indicar a quantidade de pessoas entre (homens, mulheres/adultos, crianças e pessoas que bebem bebidas alcoólicas).
   - Os campos devem permitir somente inteiros não negativos.

3. **Passo 3: Resultado do Cálculo**
   - Exibir uma tabela com o resultado do cálculo com a quantidade indicada para cada um dos itens.
   - Itens: carne, cerveja, sal grosso, refrigerante, água, carvão, gelo e pão de alho.
   
### Tabela de Referência (sugestão)
   
   - **Carne**
     - 0,4 KG por homem;
     - 0,32 KG por mulher;
     - 0,20 KG por criança;
   - **Pão de alho**
     - 2 por adulto;
     - 1 por criança;
   - **Carvão**
     - 1 KG por pessoa;
   - **Sal**
     - 0,04 KG por pessoa;
   - **Gelo**
     - 5KG a cada 10 pessoas;
   - **Refrigerante**
     - 1 garrafa de 2L a cada 5 pessoas;
   - **Água**
     - 1 garrafa de 1L a cada 5 pessoas;
   - **Cerveja**
     - 3 garrafas de 600ml por pessoa (adultos)

### Critérios

1. A calculadora deve funcionar corretamente e atender aos requisitos especificados;
2. O código deve fazer uso de seletores e métodos para manipulação do DOM;
3. O código deve fazer uso de adição e remoção de classes e estilização através do Javascript;
4. O código deve fazer uso de eventos ligados aos elementos da página;
5. O código deve fazer uso de armazenamento no browser (Web Storage API);
6. O código deve fazer uso de chamadas assíncronas e seus derivados.
