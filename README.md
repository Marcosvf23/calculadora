🧮 Projeto Calculadora

Este é um projeto de uma calculadora web simples e funcional, criada com o objetivo de praticar e demonstrar habilidades em desenvolvimento front-end com HTML, CSS e JavaScript puro.



📖 Descrição do Projeto

A calculadora é capaz de realizar as quatro operações aritméticas básicas, além de funcionalidades como apagar o último dígito e limpar toda a operação. A lógica foi implementada utilizando uma classe em JavaScript (Calculator), o que torna o código mais organizado, legível e escalável.

✨ Funcionalidades

Operações Básicas: Adição (+), Subtração (-), Multiplicação (*) e Divisão (÷).

Entrada de Números: Suporte para números inteiros e decimais.

Limpeza Total: O botão AC (All Clear) reinicia o estado da calculadora.

Apagar: O botão DEL (Delete) remove o último dígito inserido.

Display Duplo: A interface mostra tanto a operação anterior quanto o número que está sendo digitado atualmente.

Formatação de Números: Os números são formatados para facilitar a leitura (ex: 1,000,000).

🛠️ Tecnologias Utilizadas

HTML5: Para a estrutura e os elementos da calculadora.

CSS3: Para a estilização, layout e design responsivo.

JavaScript (ES6+): Para toda a lógica de funcionamento, manipulação do DOM e interatividade, utilizando o paradigma de Programação Orientada a Objetos com classes.

🚀 Como Executar o Projeto

Para visualizar e interagir com a calculadora, basta seguir os passos abaixo:

Clone este repositório para a sua máquina local:

Bash
```
 git clone [https://github.com/](https://github.com/)[Marcosvf23]/[calculadora].git
 ```
Navegue até a pasta do projeto.

Abra o arquivo index.html no seu navegador de preferência.

E pronto! A calculadora estará pronta para uso.


🏛️ Estrutura do Código JavaScript


O código JavaScript é o coração do projeto. Ele é estruturado da seguinte forma:

Seleção de Elementos do DOM:
No início do script, todos os botões e elementos de texto do display são selecionados e armazenados em constantes para fácil acesso.

Classe Calculator:
Esta classe encapsula toda a lógica e o estado da calculadora.

constructor(): Inicializa o objeto com os elementos do display e chama o método clear() para definir o estado inicial.

appendNumber(number): Adiciona um número ao operando atual.

chooseOperation(operation): Define qual operação matemática será realizada.

calculate(): Executa o cálculo com base nos operandos e na operação escolhida.

delete(): Remove o último caractere do operando atual.

clear(): Reseta todos os operandos e a operação.

updateDisplay(): Atualiza a interface do usuário para refletir o estado atual da calculadora.

formatDisplayNumber(number): Formata os números para exibição, incluindo separadores de milhar.

Event Listeners (Ouvintes de Eventos):
Ao final do script, são adicionados event listeners a todos os botões. Cada clique em um botão aciona o método correspondente na instância da classe Calculator, garantindo a interatividade e o funcionamento correto da aplicação.

👨‍💻 Autor
Feito por [Marcos Fernandes].

 **GitHub:** [@Marcosvf23](https://github.com/[Marcosvf23])
 **LinkedIn:** [/in/Marcosvf23](www.linkedin.com/in/marcosvf23])
