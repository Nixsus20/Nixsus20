# Nixsus

`C` · `Linux` · `Bash` · `PostgreSQL`

I like understanding how things work under the hood: what a command-line tool does with its arguments, how data is stored in memory, and how to implement something normally handled by a standard library.

**This is the public part of my project archive.** I keep other coursework, Linux and systems analysis projects, and earlier iterations in private repositories.

## C projects

| Project | What I worked on |
| --- | --- |
| [Simple Bash Utils](https://github.com/Nixsus20/school_21/tree/main/C/simple-bash-utils) | Reimplementing `cat` and `grep` — flags, regex, file I/O, comparison tests |
| [s21_stringplus](https://github.com/Nixsus20/school_21/tree/main/C/string-library) | String and memory functions, pointers, a custom `sprintf` |
| [s21_decimal](https://github.com/Nixsus20/school_21/tree/main/C/decimal-library) | Decimal arithmetic, a 96-bit integer representation, rounding and conversions |
| [s21_matrix](https://github.com/Nixsus20/school_21/tree/main/C/matrix-library) | Dynamic memory, matrix operations, determinants and inverse matrices |
| [Terminal Tetris](https://github.com/Nixsus20/school_21/tree/main/C/terminal-tetris) | Finite-state game logic, keyboard input and an ncurses interface |

## SQL / PostgreSQL

Six sets of exercises, each with its own queries and task constraints:

[SELECT & filtering](https://github.com/Nixsus20/school_21/tree/main/SQL/01-sql-basics) ·
[Set operations](https://github.com/Nixsus20/school_21/tree/main/SQL/02-set-operations) ·
[JOINs & CTEs](https://github.com/Nixsus20/school_21/tree/main/SQL/03-joins-and-subqueries) ·
[DML](https://github.com/Nixsus20/school_21/tree/main/SQL/04-data-manipulation) ·
[Views](https://github.com/Nixsus20/school_21/tree/main/SQL/05-views-and-snapshots) ·
[Traveling salesman](https://github.com/Nixsus20/school_21/tree/main/SQL/06-traveling-salesman)

## Try the code

Everything listed above is in [school_21](https://github.com/Nixsus20/school_21). Clone it and run the available C and SQL checks in Docker:

```bash
git clone https://github.com/Nixsus20/school_21.git
cd school_21
make check
```

[Project documentation](https://github.com/Nixsus20/school_21#readme) · [Build and test runs](https://github.com/Nixsus20/school_21/actions/workflows/verify.yml)

