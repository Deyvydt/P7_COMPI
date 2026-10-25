# P7_COMPI

Prueba 7 - Compiladores (CS3402, UTEC 2026-2).

Extensión del compilador de la semana 11 con tres expresiones nuevas:

| Expresión | Qué hace | Tipos |
|---|---|---|
| `min(e1, ..., en)` | devuelve el menor valor | n >= 2, todos `int` → `int` |
| `max(e1, ..., en)` | devuelve el mayor valor | n >= 2, todos `int` → `int` |
| `count(c1, ..., cn)` | cuenta cuántas condiciones son verdaderas | n >= 1, todos `bool` → `int` |

Archivos modificados: `token.h`, `token.cpp`, `scanner.cpp` (palabras reservadas y `_` en identificadores),
`parser.cpp`, `ast.h`, `ast.cpp`, `visitor.h`, `visitor.cpp` (TypeChecker y GencodeVisitor).

## Ejecutar

```bash
python3 run_all_inputs.py
```

Genera `outputs/inputN.s` y `outputs/reporte.txt`.
