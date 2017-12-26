# Assembly languages

As linguagens Assembly correspondem diretamente a uma linguagem de máquina, de modo que as instruções do código da máquina aparecem de uma forma não compreensível por humanos. As linguagens Assembly permitem que os programadores usem endereços simbólicos, que o assembler converte em endereços absolutos. A maioria dos assemblers também suporta macros e constantes simbólicas.

## Terminolgia

- Um macro assembler inclui uma instalação de macroinstrução para que o texto da linguagem assembly (parametrizado) possa ser representado por um nome e esse nome pode ser usado para inserir o texto expandido em outro código.

- Um cross assembler (veja também o cross compiler) é um assembler que é executado em um computador ou sistema operacional (o sistema host) de um tipo diferente do sistema no qual o código resultante deve ser executado (o sistema de destino). A Cross-assembling facilita o desenvolvimento de programas para sistemas que não possuem recursos para suportar o desenvolvimento de software, como um sistema embarcado. Nesse caso, o código do objeto resultante deve ser transferido para o sistema alvo, seja através de memória somente leitura (ROM, EPROM, etc.) ou de um link de dados usando uma cópia exata bit-a-bit do código objeto ou um representação baseada em texto desse código, como o Motorola S-record ou o Intel HEX.

- Um high-level assembler é um programa que fornece abstrações de linguagem mais frequentemente associadas a linguagens de alto nível, como estruturas de controle avançadas (IF / THEN / ELSE, DO CASE, etc.) e tipos de dados abstratos de alto nível, incluindo estruturas / registros, unions, classes, e sets.

- Um microassembler é um programa que ajuda a preparar um microprograma, chamado firmware, para controlar a operação de baixo nível de um computador.

- Um meta-assembler é um termo usado em alguns círculos para "um programa que aceita a descrição sintática e semântica de uma linguagem assembly e gera um assembler para essa linguagem".

# Como parte de um conjunto de compiladores

- GNU Assembler (gas): GPL: many target instruction sets including ARM architecture, Atmel AVR, x86, Freescale 68HC11, Freescale v4e, Motorola 680x0, MIPS, PowerPC, IBM System z, TI MSP430, Zilog Z80.

- ASxxxx Cross Assembler (part of the Small Device C Compiler project): GPL: several target instruction sets including Intel 8051, Zilog Z80, Freescale 68HC08, PIC microcontroller.

- The Amsterdam Compiler Kit (ACK) targets many architectures of the 1980s, including 6502, 6800, 680x0, ARM, x86, Zilog Z80 and Z8000.

- LLVM targets many platforms, however emits no per-target assembly language, instead more high-level typed intermediate representation assembly-like language used.
        |MOS Technology 6502|various|
        |vasm       |Free       |MOS Technology 6502|various|

- Some others self-hosted native-targeted language implementations (like Go, Free Pascal, SBCL) have their own assemblers with multiple targets. They may be used for inline assembly inside language, or even included as a library, but not always suitable for standalone application - no command-line tool exists, or only intermediate representation used as a source, or support for targets very limited.

# Single target assemblers

## **6502 assemblers**

| Assembler | License | Instruction set | Host platform |
|---------- | ------- | --------------- | ------------- |
|XASM       |Public domain|MOS Technology 6502|various|
|XA65       |GNU GPL    |MOS Technology 6502, others| various|
|WLA DX     |GNU GPL    |MOS Technology 6502, others|various|
|VISUAL6502|GNU GPL     |MOS Technology 6502|various|
|vasm       |Free       |MOS Technology 6502|various|
|TMPx       |Proprietary|MOS Technology 6502|various|
|S-C Assembler II|Proprietary|MOS Technology 6502|Apple II|
|ORCA/M |Proprietary|MOS Technology 6502, WDC 65C02|Apple II series|
|Ophis |MIT|MOS Technology 6502, WDC 65C02, 4502/4510 (experimental)|various|
|NESASM	|?|Ricoh 2A03|DOS|
|MOSASM|GNU GPL|MOS Technology 6502|various|
|Merlin|Proprietary|MOS Technology 6502, WDC 65C02, WDC 65816/65802|Apple II series, Commodore 64, Commodore 128|
|Magic ASM|?|HuC6280|DOS|
|MAE|?|MOS Technology 6502, WDC 65C02, WDC 65816/65802|Atari 8-bit family|
|MADS|Public domain|MOS Technology 6502, WDC 65816/65802|various|
|Macross|MIT|MOS Technology 6502|various|
|MAC/65|Proprietary|MOS Technology 6502, WDC 65C02|Atari 8-bit family|
|Lisa|Proprietary|MOS Technology 6502|Apple II series|
|Kick Assembler|Proprietary|MOS Technology 6502|various||
|French Silk|Proprietary| MOS Technology 6502  |Commodore 64|
|dreamass|GNU GPL|MOS Technology 6502, WDC 65816/65802|various|
|dasm|GNU GPL|MOS Technology 6502, others|various|
|CSC6502|Proprietary|MOS Technology 6502, WDC 65C02|various|
|CA65|GNU GPL|MOS Technology 6502, WDC 65C02, WDC 65816/65802|various|
|C64List|Proprietary|MOS Technology 6502|Commodore 64|
|ATASM|GNU GPL|MOS Technology 6502|various|
|Atari Macro Assembler|Proprietary|MOS Technology 6502|Atari 8-bit family|
|Atari Assembler Editor|Proprietary	|MOS Technology 6502|Atari 8-bit family|
|ASM6|Public domain|MOS Technology 6502|various|
|AS65|Proprietary|MOS Technology 6502, WDC 65C02, WDC 65816/65802|various|
|ACME|GNU GPL|MOS Technology 6502, WDC 65C02, WDC 65816/65802|various|
|64tass|GNU GPL|MOS Technology 6502, WDC 65C02, WDC 65816/65802|various|

## **680x0 assemblers**

|Assembler|Open source|License|Instruction set| Host paltform| Developmentactive|
|-------- | --------- | ----- | ------------- | ------------ | ---------------- |
|A68K|No|Free|Motorola 680x0|Commodore Amiga|No|
