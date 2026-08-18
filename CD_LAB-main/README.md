# CS4501 – Compiler Design Lab

All 10 experiments from the lab manual, each in its own folder with the
FLEX/BISON source code, sample input (where applicable), and the
expected output, exactly as documented in the manual.

| Folder | Experiment |
|---|---|
| `Exp01_Lexical_Analyzer_SymbolTable` | Lexical analyzer recognizing identifiers, constants, comments, operators + symbol table |
| `Exp02_Lexical_Analyzer` | Lexical analyzer for keywords, identifiers, numbers, operators, preprocessor directives, delimiters |
| `Exp03_Arithmetic_Expression_Validation` | Validate arithmetic expressions using +, -, *, / |
| `Exp04_Valid_Variable_Recognition` | Validate variable names (letter followed by letters/digits) |
| `Exp05_Control_Structure_Validation` | Validate C control structures (if/else, for, while, switch-case) |
| `Exp06_Calculator` | Calculator using LEX and YACC/BISON |
| `Exp07_Three_Address_Code_Generation` | Generate three-address code (TAC) for arithmetic expressions |
| `Exp08_Type_Checking` | Type checking using a symbol table built during parsing |
| `Exp09_Code_Optimization` | Constant folding, strength reduction, algebraic simplification |
| `Exp10_Backend_8086_Codegen` | Compiler back-end: TAC → 8086 assembly code |

Each experiment folder contains:
- `*.l` — FLEX source
- `*.y` — BISON grammar (where applicable)
- sample input file (where applicable)
- `output.txt` — compile commands + expected program output
- `README.md` — AIM, files, how to run, RESULT
