# 🚀 **Projeto completo (P1)**

Um projeto completo de compilador, assembler e executor desenvolvido em C. Esta é uma implementação acadêmica que demonstra o ciclo completo de compilação, desde o código fonte até a execução.

## 🛠️ **Componentes principais**:
- **Compilador**: Traduz linguagem de alto nível para assembly.
- **Assembler**: Converte código assembly em código de máquina.
- **Executor**: Roda o código compilado em uma máquina virtual simples.

## 💼 **Funcionalidades**:
- Suporte para expressões aritméticas básicas (adição, subtração e multiplicação).
- Geração de código assembly otimizado para expressões constantes.
- Máquina virtual simples com arquitetura baseada em acumulador.
- Formato binário compacto para execução.

## 🔍 **Como usar**:
```bash
# Compilar todos os componentes
make

# Compilar um programa
./compilador programa.lpn

# Gerar o binário
./assembler programa.asm programa.bin

# Executar
./executor programa.bin
```

## 📋 **Exemplo de programa**:
```
PROGRAMA "exemplo":
INICIO
  a = 2
  b = 3
  c = 4
  RES = (c + a - b) * b
FIM
```

**Limitações pertinentes** ⚠️
- Deve ser executado um a um (seguindo a ordem do item de "Como usar"), não tem um make run que já gere o programa final e execute.
- Os nomes precisam seguir: programa."tipo", ou seja, programa.lpn, programa.asm e programa.bin.
- Funcionam apenas as operações: Soma, Subtração e Multiplicação. Divisão buga e fica em loop infinito ao tentar usar.
