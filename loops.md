#Loops
##For
```java
for(variavel;condicao;accao)
{
  accao para cada elemento
}

ex:
for(int i = 0; i < 3; i++)
{
  System.out.println(i); //imprime 012
}
```
##ForEach
```java

for(por cada elemento nome do tipo String contido no array nomes)
{
  imprime um nome;
}

ex:
String[] nomes = new String[] {"Jose", "Manuel", "Joao", "Pedro"};

for(String nome : nomes)
{
  System.out.println(nome); //imprime Jose Manuel Joao Pedro
}
```
##While
```java
while(condicao) ---> equanto a condicao se verificar repetira o codigo dentro de chavetas
{
  accoes;
}

ex:
int i = 0;

while(i < 5)
{
  System.out.println(i); //imprime 01234
  i++;
}
```
##DoWhile
```java
do --->repete o codigo entre chavetas enquanto a condicao dentro do while se verificar
{
accoes
}while(condicao);

ex:
int i = 0;
do
{
  System.out.println(i); //imprime 01234
  i++
}while(i < 5);
```
![GitHub Logo](https://github.com/TheWebs/JHelp-PT/blob/master/giphy%20(34).gif?raw=true)
