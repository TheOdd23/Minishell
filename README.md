# Minishell

The goal of minishell is exactly like the name says, recreating a minimalistic shell (in teams of 2).

We had to implement redirections `<`, `<<`, `>` and `>>` and pipes `|` , 7 builtins(`echo`, `cd`, `pwd`, `export`, `unset`, `env` and `exit`), handle environment variables, single and double quotes, and more.

Like the real `bash`, our program needed to react accordingly to signals such as `ctrl-d` and `ctrl-c`.

The hardest part of the project was not the project in itself, but mostly knowing when to stop adding stuff, when it was ok to be different from the original, how to handle certain situations, etc.

This is one of the project I'm most proud of since it was one of the most complex in terms of comprehension, parsing, memory handling and project structure. There was a lot of documentation to dig in and intricacies to take in consideration. Comparing our project with `bash` made us do additional functionalities we weren't supposed to do, but I'm glad we still did them, cause it showed us we could.
