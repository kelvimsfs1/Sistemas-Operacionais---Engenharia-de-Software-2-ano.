# sop_exer_terminal_shellscript
Respostas do exercício de sop

exercio 1

vi exercicio1.txt

#!/bin/bash

echo "Digite o seu nome"

read nome

echo "Bom dia $nome"

exercicio 2

vi exercicio2.txt

#!/bin/bash

echo "digite o primeiro valor"

reade v1

echo "digite o segundo valor"

read v2

resultado= $(($v1*$v2))

echo "o resultado da multiplicação é $z"

exercicio 3

#!/bin/bash

echo "digite um valor"

read x

if [ $x -gt 0 ]; then

   echo "positivo"
 
elif [ $x -lt 0 ]; then

  echo "negativo"
 
 else
 
  echo "zero"
  
fi

exercicio 4

vi tabuada.txt

#!/bin/bash

echo "digite o numero"
 
read numero
 
x=0
 
while [ $x -le 10 ];
do
      conta=$[ $numero * $x ]
 
      x=$[ $x + 1 ]
 
      echo "$numero x $x = $conta"
 
done

Exercicio 5

#!/bin/bash
 
 
opcao=0

while [ $opcao -ne 3 ]

do
      echo "Digite sua opcao"
      
      read opcao
      
      if [ $opcao -eq 1  ]; then
      
      cal
 
 
      elif  [ $opcao -eq 2 ]; then
      
             ls -l
 
 
 
 
      fi
      
done
 
