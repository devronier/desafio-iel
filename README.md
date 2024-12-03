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

---

## Fase 3: Individual - Aprimoramento da Solução de Comunicação 
**Tempo:** 3 horas

### Objetivo:  
Expandir e aprimorar o sistema de comunicação criado no **Desafio 1**, com foco na implementação de funcionalidades adicionais para **educação** e **gestão de informações acadêmicas**.

### Descrição:  
Os participantes devem expandir a solução do **Desafio 1** (agora de forma individual) implementando as seguintes funcionalidades, com ênfase no **módulo de comunicação**.

1. **Aprimoramento do Sistema de Comunicação**  
   - Melhorar a interface de mensagens criada no **Desafio 1**, agora adicionando **filtros de categorias** como:
     - **Mensagens não lidas**
     - **Mensagens prioritárias**
     - **Mensagens enviadas/recebidas**
   - Simulação de envio de mensagens entre os três tipos de usuários: **Aluno**, **Pai** e **Professor**.

2. **Autenticação de Usuários**  
   - Adicionar uma tela de **login básico** com autenticação para três tipos de usuários: **Aluno**, **Pai** e **Professor**.
   - Dependendo do tipo de usuário, a interface da página inicial será adaptada, oferecendo funcionalidades específicas de **mensagens** ou **acompanhamento acadêmico**.

3. **Área de Acompanhamento Acadêmico**  
   - Para **Alunos**: Criar uma área de **acompanhamento de notas** com uma tabela ou gráfico, mostrando suas médias e status de aprovação.
   - Para **Pais**: Exibir o desempenho acadêmico de seus filhos, com uma visão geral das notas e eventuais comentários dos professores.
   - Para **Professores**: Exibir uma lista de alunos com suas notas, permitindo a visualização de desempenho geral da turma.

### Critérios de Avaliação:

1. **Integração e Expansão da Comunicação:**  
   - A funcionalidade de **comunicação** deve ser aprimorada com filtros e uma navegação eficiente. O sistema de mensagens deve ser o principal módulo da solução.

2. **Qualidade Técnica:**  
   - Organização do código, uso de boas práticas de desenvolvimento, como modularização e legibilidade.

3. **Usabilidade:**  
   - A interface deve ser intuitiva e fácil de usar.

4. **Alinhamento com a Proposta de Educação e Comunicação:**  
   - A solução deve atender a proposta de **educação** e **comunicação** de forma eficaz, com uma interface funcional e relevante.

5. **Acessibilidade (Critério de Avaliação):**  
   - Embora não seja um requisito obrigatório, será considerado como critério de avaliação a implementação de boas práticas de **acessibilidade**, como contraste ajustável, navegação por teclado, e texto alternativo para imagens, para tornar a interface mais inclusiva.

---

### Resultado Final:  
Os 5 participantes com as soluções mais completas, inovadoras e bem executadas serão selecionados para a próxima fase.

 
