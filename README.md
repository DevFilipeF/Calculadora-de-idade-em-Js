# Age Calculator

Este é um simples projeto de **Calculadora de Idade**, desenvolvido utilizando **HTML, CSS e JavaScript**. Ele permite que o usuário insira sua data de nascimento e, ao clicar no botão, veja sua idade exata em anos, meses e dias.

## 📌 Funcionalidades
- Calcula a idade do usuário com base na data de nascimento fornecida.
- Exibe os anos, meses e dias vividos até a data atual.
- Valida se a data inserida não está no futuro.
- Alerta o usuário caso ele insira uma data inválida.

## 🚀 Tecnologias Utilizadas
- **HTML**: Estrutura da aplicação.
- **CSS**: Estilização do layout.
- **JavaScript**: Lógica de cálculo da idade e manipulação do DOM.

## 📂 Estrutura do Projeto
```
📁 age-calculator
│── index.html    # Página principal
│── style.css     # Estilização da página
│── script.js     # Lógica de cálculo da idade
```

## 📜 Como Usar
1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em um navegador.
3. Insira sua data de nascimento no campo apropriado.
4. Clique no botão "Calcular Idade".
5. Veja o resultado exibido na tela!

## 📌 Explicação do Código (JavaScript)
- **`ageCalculate()`**: Captura a data inserida pelo usuário e calcula a idade.
- **`isFutureDate()`**: Verifica se a data inserida é inválida (futura).
- **`calculateAge()`**: Realiza os cálculos de idade em anos, meses e dias.
- **`getDaysInMonth()`**: Retorna o número de dias do mês específico, considerando anos bissextos.
- **`displayResult()`**: Exibe os resultados no HTML.
- **`addEventListener`**: Ativa o cálculo ao clicar no botão.

## 📌 Melhorias Futuras
- Adicionar suporte a diferentes fusos horários.
- Criar um design mais responsivo e moderno.
- Implementar mensagens de erro mais intuitivas.

