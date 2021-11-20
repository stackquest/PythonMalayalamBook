[NOTE]
====
- **Compiled Language:** If a programming language is compiled, compiler reads the entire program and creates binary from the entire program. We have to execute this binary in order to get output.
- **Interpreted and Interactive:** Python processed at runtime by the interpreter. We need not compile the program before executing it. The Python prommpt interact with the interpreter to interpret the program that you have written. Python has REPL mode
====





NOTE: Bytecode is an intermediate code between high-level language and machine level-language that is platform independent.
* **Poratable:**
 - It can be

.Translators (Compiler, Interpreter and Assembler)
[%breakable]
****
[NOTE]
====
- The computer understands only machine languages. So there should be a decoder to translate from high-level to low-level and vice versa. This is done by a sequence of Programs called language processors or Translators. It could be a **compiler, interpreter or assembler**.
- The **compiler** compiles (translates) the entire program in high-level language (source code) into its machine language (object code) before execution starts. Therefore, the object code will be completely ready, as a binary file (for example exe) in the system prior to execution and these binary file does not require the compiler to run at any time. We can say these binary files are easily portable.

- The **interpreter** reads each line of source code and then translates into its machine language and then executes. The process of translation will be repeated for each line of the source code according to the program sequence. Here the source code will translated many times, whenever a program segment repeats. Hence *more time is required to translation* by an interpreter.
- **Assembly language** are bridge between high-level languages and machine language. It has lower level primtives and operations. An assembler translates the assembly language to machine language. The speed, compactness and close association with hardware are the advantages of assembly language.

[ditaa]
....
        +---------------------+
        | High Level Language |
        +---------------------+
                |
                |  (Compiler/ Interpreter)
                |
                v
        +---------------------+
        |  Assembly Language  |
        +---------------------+
                |
                |  (Assembler)
                |
                v
        +--------------------------+
        |  Machine Level Language  |
        +--------------------------+
....

====
****

\\( \int x dx = \frac{x^2}{2} + C \\)

=== How Python Works?

image::python_pvm.png[Python PVM]