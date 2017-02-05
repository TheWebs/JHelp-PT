#Arrays
##Criacao e inicializacao
Um array e basicamente um conjunto de varios objectos do mesmo tipo, int, double, String, float, etc.. Sao criados desta forma:
```java
String[] array; //exemplo usando String
```
Os arrays precisam de ser inicializados, que pode ser feito manualmente ou nao, desta forma:

```
String[] array;
//Forma 1
array = new String[20]; //cria um array com 20 elementos que vai do 0 ao 19
//Forma 2
array = new String {"texto1", "texto2", "texto3"}; //cria um array com 3 elementos que vai do 0 ao 2
```
Para aceder a um elemento especifico do array usa se parenteses rectos:
```java
String[] array;
array = new String {"texto1", "texto2", "texto3"}; 
System.out.println(array[1]); //imprime texto2
```
