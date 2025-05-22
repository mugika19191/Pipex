# 🔗 Pipex

> Recreating Unix pipelines in C to understand process forking, piping, and file descriptor manipulation.

## 📘 Project Description

The **pipex** project replicates the functionality of Unix pipelines by executing multiple commands connected by pipes. You will learn how to use `fork()`, `execve()`, `pipe()`, and file descriptors to simulate shell behavior.

### 💡 Example Shell Equivalent

```bash
< infile cmd1 | cmd2 > outfile
./pipex infile "ls -l" "wc -l" outfile
