# 🤖 BIMO - Calculadora de IMC

Um programa simples de terminal que calcula o Índice de Massa Corporal (IMC) do usuário e retorna uma classificação personalizada, com formatação colorida e uma pitada de personalidade.

## 📋 Sobre o projeto

Esse projeto foi desenvolvido como prática dos conceitos iniciais de Python (entrada e saída de dados, tipos primitivos, operadores aritméticos, manipulação de strings e estruturas condicionais `if`/`else`), aprendidos durante o **Curso em Vídeo** do professor Gustavo Guanabara.

O programa se apresenta como "BIMO", pede o nome, peso e altura do usuário, calcula o IMC e devolve uma mensagem personalizada de acordo com o resultado.

## ⚙️ Funcionalidades

- Coleta o nome completo do usuário e extrai apenas o primeiro nome para personalizar as mensagens
- Solicita peso (kg) e altura (m) e confirma os dados informados antes de prosseguir
- Calcula o IMC com a fórmula `IMC = peso / altura²`
- Classifica o resultado em três faixas:
  - **Abaixo do peso** (IMC < 18.5)
  - **Peso adequado** (18.5 ≤ IMC < 25)
  - **Acima do peso** (IMC > 25)
- Interface de terminal com cores (ANSI escape codes) e pausas (`time.sleep`) para simular um processamento mais dinâmico

## ▶️ Como executar

Certifique-se de ter o Python 3 instalado, depois rode:

```bash
python imc.py
```

> 💡 As cores usadas no terminal (códigos ANSI) funcionam melhor em terminais que suportam essa formatação, como o terminal integrado do VS Code, PyCharm, ou terminais Linux/macOS. No Prompt de Comando (cmd) do Windows mais antigo, as cores podem não aparecer corretamente.

## 🖥️ Exemplo de uso

```
-=--=--=--=--=--=--=--=--=--=--=--=--=--=--=--=--=--=--=--=-
                    CALCULADORA DE IMC
-=--=--=--=--=--=--=--=--=--=--=--=--=--=--=--=--=--=--=--=-
Por gentileza, digite seu nome completo: Ana Silva
...
Certo! É um prazer Ana! Me chamo BIMO e eu vou calcular seu IMC.
...
PESO EM KG (KILOGRAMAS): 60
ALTURA EM M (METROS): 1.65
...
Olha só!
Analisando seu IMC, você está no peso adequado, com um IMC de 22.04
Meus parabéns, Ana!!
```

## 🛠️ Tecnologias

- Python 3
- Módulos nativos: `math`, `time`

## 📚 Conceitos aplicados

- Entrada e saída de dados (`input`, `print`)
- Conversão de tipos (`str`, `float`)
- Manipulação de strings (`.strip()`, `.split()`, `.format()`)
- Estruturas condicionais (`if` / `else`)
- Formatação de texto no terminal com códigos ANSI

## 📌 Status

✅ Concluído — projeto funcional desenvolvido para praticar os conceitos do Mundo 1 do curso.

## ✍️ Autor

Desenvolvido por **Igor Cavalcanti** durante os estudos de Python.