# valgrind_supress_file
<br>
 - BASIC USE
```bash
./push_swap 2 1 3
```
<br>
 - use like this :
```bash
valgrind --suppressions=readline.supp ./your_prog
```

<br>

 - for minishell : 
```bash
valgrind --leak-check=full --track-fds=yes --trace-children=yes --show-leak-kinds=all --suppressions=readline.supp ./minishell
```
