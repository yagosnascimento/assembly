# assembly
Assembly não é uma linguagem, é a representação legível por humanos do Machine Code (código de máquina). Cada instrução que você escreve é mapeada quase 1:1 para os opcodes que o seu Ryzen executa.
No Assembly, você não tem variáveis bonitinhas; você tem Registradores (pequenos espaços de memória ultra-rápidos dentro da CPU). Você não tem "if/else"; você tem Jumps e Comparisons. É você lidando diretamente com a eletrônica do processador.

# Por que assembly?
Porque eu queria sentir a dor real de gerenciar cada byte manualmente.

# O que vamos usar?
- **CPU:** AMD Ryzen
- **Assembler:** NASM
- **Sintaxe:** Intel (porque não sou masoquista de usar AT&T)
- **Linker:** ld (binutils)
