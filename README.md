# DESAFIO IEL 

## Fase 1: Desafio em Duplas - Tela de Comunicação Simples  
**Tempo:** 1h20  
**Descrição:**  
Os participantes devem criar uma tela de comunicação básica para pais e professores usando **HTML** e **CSS**, com funcionalidades simuladas. Essa tela deve conter:  
1. Um campo para o nome do remetente.  
2. Um campo de texto para a mensagem.  
3. Um botão para enviar a mensagem (não precisa funcionar, mas deve estar estilizado).  
4. Uma área que mostre as mensagens enviadas (simulada com um exemplo estático).  

**Tarefa:**  
- Estruturar a interface usando **HTML**.  
- Estilizar a página com **CSS**, incluindo cores, espaçamento e fontes legíveis.  
- A interface deve ser simples, mas visualmente organizada, como se fosse parte de um sistema de comunicação.  

**Requisitos:**  
1. A tela deve incluir:
   - Um título como "Sistema de Mensagens".
   - Um formulário com os campos mencionados.
   - Uma seção que simula a exibição das mensagens.
2. Usar **CSS externo** para estilizar a página.

---

## Fase 2: Desafios Individuais  
**Tempo:** 1h  

### **Desafio 1: Cálculo de Média Ponderada**  
**Nível:** Fácil  
**Descrição:**  
Você precisa criar uma função para calcular a média ponderada de um aluno. Cada nota tem um peso diferente, e a fórmula para o cálculo é:

$$ \text{Média Ponderada} = \frac{\text{(Nota 1 × Peso 1) + (Nota 2 × Peso 2) + ...}}{\text{Soma dos Pesos}} $$

**Tarefa:**  
- A função deve receber dois arrays:
  - Um com as **notas** do aluno.
  - Outro com os **pesos** correspondentes.  
- Calcular e retornar a média ponderada.
**Exemplo de Entrada/ Saída**:

```javascript
const  notas = [7, 8, 6];
const  pesos = [2, 3, 1];

calcularMediaPonderada(notas, pesos);
// Saída: "A média ponderada é: 7.33"

```

### **Desafio 2: Agenda de Reuniões**  
**Nível:** Médio  
**Descrição:**  
Você precisa criar uma função para verificar se um horário de reunião está disponível. Cada professor tem horários disponíveis de manhã (8h às 12h) e tarde (13h às 17h). O aluno (pai) pode escolher um horário dentro do período disponível do professor. O sistema deve verificar se o horário desejado já está ocupado.

**Tarefa:**  
- Crie uma função `verificarHorarioDisponivel` que recebe o horário do professor e o horário desejado pelo aluno, e retorne se o horário está disponível ou não.
**Tarefa**:

- Crie uma função `verificarHorarioDisponivel` que recebe o horário do professor e o horário desejado pelo aluno, e retorne se o horário está disponível ou não.
- 
**Exemplo de Entrada/ Saída**:

```javascript

verificarHorarioDisponivel("8h às 12h", "10h"); // Saída: "Horário disponível."

verificarHorarioDisponivel("8h às 12h", "13h"); // Saída: "Horário não disponível."

```

### **Desafio 3: Gerenciamento de Recados**  
**Nível:** Difícil  
**Descrição:**  
Você tem uma lista de recados enviados entre pais e professores. Cada recado tem uma data e uma prioridade (importante ou regular). O sistema deve organizar os recados em ordem de data, com os recados importantes aparecendo primeiro.

**Tarefa:**  
Crie uma função `organizarRecados` que organiza os recados por data e prioridade (importante vem antes de regular).

**Tarefa**:

Crie uma função `organizarRecados` que organiza os recados por data e prioridade (importante vem antes de regular).

**Exemplo de Entrada/ Saída**:

```javascript

const  recados = [
{mensagem:  "Reunião agendada", prioridade:  "Importante", data:  "01/12"},
{mensagem:  "Boletim disponível", prioridade:  "Regular", data:  "02/12"},
{mensagem:  "Lembrete de evento", prioridade:  "Importante", data:  "01/12"}
]; 

organizarRecados(recados);

// Saída:

// "Reunião agendada (Importante, 01/12)"

// "Lembrete de evento (Importante, 01/12)"

// "Boletim disponível (Regular, 02/12)"

```
