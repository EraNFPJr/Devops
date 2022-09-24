# LINUX PARA O DIA A DIA.

## Parte 1: Navegando por Diretórios

Use the **ls** command to display a listing of the current directory. Remember that commands are casesensitive.
$ **ls**

Use the **ls** command with the **labs** argument to display the contents of the labs folder.
$ **ls labs**

Use the **ls** command with the **-l** option to display a "long display" of the contents of the current directory.
$ **ls -l**

Use the **ls** command with the **-r** option to display the contents of the current directory in reverse alphabetical order.
$ **ls -r**

Multiple options can be used at the same time. Use the **ls** command with both the **-l** and **-r** options to display the contents of the current directory both in long and reverse order.
$ **ls -lr**

There are many more options that can be used with the **ls** command. Use the **man** command with the argument **ls** to see all of the possibilities in the manual. The **man** command can be used to look up any command within the system. Use the space bar to advance to subsequent screens. Press **q** to quit.
$ **man ls**

You can also use **--help** argument after most commands to see a shorter summary of all the available command options.
$ **ls --help**

## pwd
Use the **pwd** command to display the current working directory.
$ **pwd**

## cd
Use the **cd** command to change the directory to /home/devasc/Documents.
$ **cd**

Use the **cd** command with the **/** symbol to change directories to the root directory. Use **pwd** again to see that you are now in the root directory.
$ **cd /**
$ **pwd**

Return to the **/home/devasc/Documents** directory. Tip: You can move one directory at a time or all the way to a destination. To quickly enter the command, type the first few letters of the directory name and press **Tab** for the system to automatically enter the rest of the name. Remember that names are casesensitive.
$ **cd /home/devasc/Documents**

Use the **..** characters to move up a single directory. Use **pwd** again to see you are back in the user’s home directory.
$ **cd ..**
$ **pwd**

## Parte 2: Usando comandos do super usuários para acesso administrativo

Use the **sudo** command to issue a single command as the root user. A new terminal will not be created. Use the **sudo apt-get update** command to update to refresh the list of available packages installed on the VM. This command will not work without using the **sudo** command.
**Note:** Your output will most likely be different.
$ **sudo apt-get update**

## Parte 3: Revisão sobre Gerenciamento de Arquivos
In this part, you will review file permissions, change file permissions and ownership, move files, copy files, remove files, and view files.

### Etapa 1: Revisando as permissões de arquivos
