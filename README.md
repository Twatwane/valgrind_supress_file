# valgrind_supress_file
use like this : valgrind --suppressions=readline.supp ./your_prog
for minishell : valgrind --leak-check=full --track-fds=yes --trace-children=yes --show-leak-kinds=all --suppressions=readline.supp ./minishell
