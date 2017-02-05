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
