# Script de atualização completa do sistema (Distros GNU/Linux)
## Instruções
1. Baixe o arquivo `update.sh` e salve no diretório de preferência
2. Abra o terminal e execute o comando abaixo para editar o arquivo .bashrc que contém os command aliases

```nano ~/.bashrc```

3. Adicione a linha abaixo para utilizar o comando `update` para executar a atualização completa

```alias update='~/.update.sh'```

4. Reinicie sua máquina, abra o terminal e execute o comando abaixo para que o sistema seja atualizado completamente

```update```
