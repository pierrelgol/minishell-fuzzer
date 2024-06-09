# minishell-fuzzer

```Bash
                 Minishell-Fuzzer
                                 
 Description :                                
                                 
 Fuzzy testing, also known as fuzzing is a software testing techinque
 that involves providing invalid, unexpected or random data as inputs
 to a computer program. The goal is to identify errors, vulnerabilites,
 and crashes.
 
 Minishell-Fuzzer is a small program designed to be able to                                
 test the parsing capabilites of your minishell implementation.
 it is not a tester, simply a tool that will improve your ability
 to test your implementation. The way it works is simple, you provide
 the absolute path to your executable, a set of options, and mshfuzz
 will launch your minishell and input random series of commands into it
                                 
 Usage :                                
 
 $> mshfuzz [absolute_path_to_minishell] [options]
 $> mfhfuzz $HOME/workspace/42/minishell -n 5 -l 10

 Options :

 -h    : void :     print help message.
 -n    : i32  :     number_of input line to send to minishell.
 -l    : i32  :     max length of commands per input line.
```
