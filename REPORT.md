## Laboratory work XV

Данная лабораторная работа посвещена изучению инструментов статического и динамического анализа кода
```ShellSession
$ open http://cppcheck.sourceforge.net
```

## Tasks

- [x] 1. Ознакомиться со ссылками учебного материала
- [x] 2. Используя **cpplint** провести анализ проекта на **C++**
- [x] 3. Используя **Cppcheck** провести анализ проекта на **C++**
- [x] 4. Используя **OCLint** провести анализ проекта на **C++**
- [x] 5. Используя **Valgrind** провести анализ проекта на **C++**
- [x] 6. Составить отчет и отправить ссылку личным сообщением в **Slack**

**Valgrind**
```
$ valgrind ./main 
==2602== Memcheck, a memory error detector 
==2602== Copyright (C) 2002-2017, and GNU GPL'd, by Julian Seward et al. 
==2602== Using Valgrind-3.13.0 and LibVEX; rerun with -h for copyright info 
==2602== Command: ./main 
==2602== 
==2602== 
==2602== HEAP SUMMARY: 
==2602== in use at exit: 72,704 bytes in 1 blocks 
==2602== total heap usage: 1 allocs, 0 frees, 72,704 bytes allocated 
==2602== 
==2602== LEAK SUMMARY: 
==2602== definitely lost: 0 bytes in 0 blocks 
==2602== indirectly lost: 0 bytes in 0 blocks 
==2602== possibly lost: 0 bytes in 0 blocks 
==2602== still reachable: 72,704 bytes in 1 blocks 
==2602== suppressed: 0 bytes in 0 blocks 
==2602== Rerun with —leak-check=full to see details of leaked memory 
==2602== 
==2602== For counts of detected and suppressed errors, rerun with: -v 
==2602== ERROR SUMMARY: 0 errors from 0 contexts (suppressed: 0 from 0
```

## Links

- [Google C++ Style Guide](https://github.com/cpplint/cpplint)
- [Cppcheck Manual](http://cppcheck.sourceforge.net/manual.pdf)
- [Valgrind Quick Start Guide](http://valgrind.org/docs/manual/index.html)
- [OCLint Tutorial](http://docs.oclint.org/en/stable/intro/tutorial.html)

```
Copyright (c) 2017 Братья Вершинины
```
