# ⚖️ Calculadora de IMC Dinâmica

![Bootstrap](https://img.shields.io/badge/bootstrap-%238511f2.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=f7df1e)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

Uma calculadora de Índice de Massa Corporal (IMC) moderna e intuitiva. O projeto combina a agilidade do **Bootstrap 5** com uma lógica de validação robusta em **JavaScript**, oferecendo feedback visual imediato através de cores dinâmicas para cada classificação de saúde.

---

## 🌟 Destaques do Projeto

* **Interface Responsiva:** Desenvolvida com Bootstrap 5 para garantir que a calculadora funcione em qualquer tamanho de tela.
* **Feedback Visual Inteligente:** O resultado muda de cor automaticamente de acordo com o IMC:
  * 🩵 **Ciano:** Abaixo do peso
  * 💚 **Verde:** Peso normal
  * 💛 **Dourado:** Sobrepeso
  * 🧡 **Laranja/Coral:** Obesidade I e II
  * ❤️ **Vermelho:** Obesidade III
* **Tratamento de Dados:** O sistema identifica se o usuário digitou a altura em centímetros (ex: 170) ou metros (ex: 1.70) e faz a conversão automática.
* **Estilização Avançada:** Uso de `linear-gradient` com `-webkit-background-clip: text` para um título moderno e elegante.

---

## 🛠️ Tecnologias Utilizadas

* **Bootstrap 5:** Sistema de grid e componentes de formulário.
* **JavaScript (ES6+):** Lógica de cálculo, validação de inputs e manipulação de classes CSS.
* **CSS3 Personalizado:** Efeitos de borda dupla, sombras (`box-shadow`) e estilização de backgrounds.

---

## 📂 Estrutura de Arquivos

| Arquivo | Descrição |
| :--- | :--- |
| `index.html` | Estrutura da página, estilos CSS e lógica de interface. |
| `IMC_CALC.js` | Arquivo externo contendo as funções matemáticas `imc()` e `situacao()`. |
| `IMC.jpg` | Imagem de fundo temática para a aplicação. |

---

## 🚀 Como Executar

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/groshiro/calculadora-imc.git](https://github.com/groshiro/calculadora-imc.git)
    ```
2.  **Verifique os caminhos:** Certifique-se de que o arquivo `IMC_CALC.js` e a imagem `IMC.jpg` estão na pasta correta indicada no código.
3.  **Abra o arquivo:** Basta abrir o `index.html` em qualquer navegador moderno.

---

## 🧠 Lógica de Cálculo

O IMC é calculado através da fórmula matemática:

$$IMC = \frac{peso}{altura^2}$$

[Image of BMI classification table with weight categories and ranges]

O projeto segue os padrões da Organização Mundial da Saúde (OMS) para as faixas de classificação.

---
⭐ **Projeto desenvolvido para fins de estudo de integração entre JS e CSS dinâmico.**
