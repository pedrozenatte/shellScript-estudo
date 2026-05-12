# Shell

Shell é a interface entre o usuário e o sistema Unix. 
Ele atua como um interpretador de comandos.

## Tipos de Shell 
- Bourne Shell (sh): Shell original e padrão do Unix
- Bourne-Again Shell (bash): Shel padrão no Linux, compatível com sh, mas com melhorias. Também incorpora recursos do csh e ksh. 
- Korn shell (ksg).
- C Shell (csh): Traz para o shell recursos da linguagem C.
- zsh.
- Windows PowerShell.

OBS: Todos os Shell são derivados do Bourne Shell.

Para verificar qual Shell está utilizando, basta rodar o comando para imprimir a variável de ambiente Shell.
```bash
echo $SHELL 

# Ou, de maneira mais antiga

echo $0
```

# Shell Script

## O que é?
Shell Script é uma sequência lógica de comandos e instruções no Shell. 
Além de comandos, também são utilizadas variáveis, instruções lógicas e condicionais. 

#### Funções do Shell Script
As funções inclui:
- Automatizar e agilizar atividades repetitivas;
