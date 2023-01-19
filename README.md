# Script de atualização completa do sistema (Distros GNU/Linux)
## Instruções
1. Clone o projeto e salve o arquivo `update.sh` no diretório de preferência da sua máquina.
2. Abra o seu terminal e execute o comando `pwd`no diretório onde se encontra o arquivo. Logo após copie o path, você precisará inserí-lo nos passos 3 e 5.
3. Execute o comando abaixo para dar permissão de execução para o arquivo:

```
sudo chmod +x <path>/update.sh
```

4. Execute o comando abaixo para editar o arquivo .bashrc que contém os command aliases:

```
nano ~/.bashrc
```

5. Adicione a linha abaixo para utilizar o comando `update` para executar a atualização completa:

```
alias update='<path>/update.sh'
```

6. Feche e abra novamente seu terminal. Por fim, execute o comando abaixo para que o sistema seja atualizado completamente:

```
update
```
