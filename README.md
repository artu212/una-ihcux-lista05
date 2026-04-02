# una-ihcux-lista05

# ConversorExpert

## Descrição
Este projeto consiste em um sistema de conversão de moedas (Real para Dólar) desenvolvido em C# no console, aplicando conceitos de IHC (Interação Humano-Computador) e UX.

## Heurísticas de Nielsen Aplicadas

### 1. Visibilidade do Status do Sistema
O sistema informa ao usuário o que está acontecendo durante a execução, exibindo mensagens como:

- "Conectando ao Banco Central..."
- "Calculando taxas..."

Isso mantém o usuário informado sobre o progresso, reduzindo dúvidas e incertezas.

---

### 2. Prevenção de Erros
O sistema utiliza a estrutura `try-catch` para evitar falhas quando o usuário insere dados inválidos.

Caso o usuário digite valores incorretos (como letras), o sistema não trava. Em vez disso, exibe uma mensagem clara:

"Entrada inválida! Use apenas números e vírgula para decimais."

Isso melhora a experiência e orienta o usuário a corrigir o erro.

---

### 3. Estética e Design Minimalista
O sistema apresenta uma interface limpa e organizada no console, utilizando:

- Cores para destacar informações importantes
- Linhas para separar seções
- Formatação clara do resultado final

Exemplo:
-------------------------------------------
VALOR CONVERTIDO: $ XX,XX (Dólares)
-------------------------------------------

Isso facilita a leitura e torna o sistema mais agradável de usar.

---

## Conclusão
O projeto demonstra como aplicar boas práticas de UX mesmo em aplicações simples de console, tornando o sistema mais intuitivo, seguro e eficiente para o usuário.
