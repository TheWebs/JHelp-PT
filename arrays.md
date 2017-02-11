#Arrays
##Criacao e inicializacao
Um array e basicamente um conjunto de varios objectos do mesmo tipo, int, double, String, float, etc.. Sao criados desta forma:
```java
String[] array; //exemplo usando String
```
Os arrays precisam de ser inicializados, que pode ser feito manualmente ou nao, desta forma:

```java
String[] array;
//Forma 1
array = new String[20]; //cria um array com 20 elementos que vai do 0 ao 19
//Forma 2
array = new String[] {"texto1", "texto2", "texto3"}; //cria um array com 3 elementos que vai do 0 ao 2
```
##Elementos do array
Para aceder a um elemento especifico do array usa se parenteses rectos:
```java
String[] array;
array = new String[] {"texto1", "texto2", "texto3"}; 
System.out.println(array[1]); //imprime texto2
```
Quando se cria um array de int, double ou float os elementos desse array comecam todos com o valor 0 a nao ser que seja iniciado manualmente, exemplo:
```java
int[] array;
array = new int[10];
System.out.println(array[3]);
System.out.println(array[4]);
```
O programa acima apresentado imprime "00" (em linhas diferentes).
Com os arrays de tipo String os elementos comecam a null.

##Loop por elementos de um array:
Como obter ou aplicar alguma accao a todos os elementos de um array:

```java
for(int i = 0; enquanto o i for menor que o numero de elementos do array (se tem 22 elementos vai do 0 ao 21); i++)
{
  accao;
}


int[] array;
array = new int[10];
for(int i = 0; i < array.length;i++) //imprime 000000000
{
  System.out.println(array[i]); 
}
```
