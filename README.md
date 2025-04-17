# 🚀 **Projeto Completo (P1)**

Um projeto completo de compilador, assembler e executor desenvolvido em C. Esta é uma implementação acadêmica que demonstra o ciclo completo de compilação, desde o código fonte até a execução.

## 🛠️ **Componentes Principais**:
- **Compilador**: Traduz linguagem de alto nível para assembly.
- **Assembler**: Converte código assembly em código de máquina.
- **Executor**: Roda o código compilado em uma máquina virtual simples.

## 💼 **Funcionalidades**:
- Suporte para expressões aritméticas básicas (adição, subtração, multiplicação, divisão).
- Geração de código assembly otimizado para expressões constantes.
- Máquina virtual simples com arquitetura baseada em acumulador.
- Formato binário compacto para execução.

## 🔍 **Como Usar**:
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

## 📋 **Exemplo de Programa**:
```
PROGRAMA "exemplo":
INICIO
  a = 2
  b = 3
  c = 4
  RES = (c + a - b) * b
FIM
```

---
**Projeto Acadêmico de Compiladores** ⤵️
- Implementado completamente em C
- Demonstra conceitos básicos de compilação
- Inclui análise léxica, sintática e geração de código
