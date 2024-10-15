![ufpb](imgs/ufpb.png)

# Prova 4 Cálculo Numérico

- Aluno : Flávio Mesquita Marinho Filho
- Matrícula : 20230146390

# Relatório

- Foi utilizado o jupyter notebook com a linguagem python para resolução das questões 1, 2 e 4. Para tal foram utilizados as devidas bibliotecas em python para as melhores finalidades, como o numpy para realizar calculos e utilizar suas funções tais como o np.log para realizar calculos logaritmicos. A biblioteca Pandas para gerar os dataframes e a biblioteca matplotlib que ao utilizar os dataframes do pandas ela plota os gráficos que foram utilizados.

### Detalhes

- O código está no github no arquivo "questoes", lá está o código em python completo.

### Bibliotecas

- Numpy (usado para realizar os cálculos)

# Introdução 

 Resolvendo os exercicios que foram propostos nessa prova e nas demais, é notório a importância da resolução de questões utilizando de métodos que podem ser aplicados computacionalmente como nos vimos e vamos ver a seguir na resolução das questões.
 Ademais, foram utilizados os métodos de Regra de Simpson, regra dos trapézios, método de Gauss-Seidel, método de eliminação de Gauss.
 Destarte, a utilização de métodos computacionais torna a resolução de diversas questões possíveis e de forma mais rápida e prática.

# Questão 1

Para a resolução da questão 1 foi utilizada a Regra de Simpson


A Regra de Simpson composta será aplicada, que é

![image](https://github.com/user-attachments/assets/98c199b3-ca5b-47f3-ac78-1517e18b9466)


- O valor obtido ao rodar o código da questão 1 foi o seguinte:

A distância coberta é: 44.735

# Questão 2

A Regra dos trapézios generalizada que foi utilizada é

![image](https://github.com/user-attachments/assets/2c9a6b36-ac08-44a7-916d-0d73f3b5ece7)

- E o resultado obtido foi o seguinte:

A área sob a curva da pressão é: 1870.0

# Questão 3 (B)

Nessa questão foi utilizado o método de Gauss-Seidel com epsilon = 0,001.

![image](https://github.com/user-attachments/assets/68770c73-c843-4fbd-879a-3a8bb810b7a4)


Dado esse sistema de equações :

![image](https://github.com/user-attachments/assets/c3b6a5eb-5ff5-40b9-a883-81ab50ce1fae)

Foi obtido o resultado de que o método não convergiu. Mesmo alterando a quantidade de interações ela não converge, pra 100, 300, e o máximo foi 383 antes de aparecer inf ou nan nan nan.

# Questão 4

Foi utilizado o método de eliminação de Gauss nessa questão

Nessa questão foi pedido para calcular a quantidade de computadores de cada tipo produzido dado a quantidade de materiais das questões.

![image](https://github.com/user-attachments/assets/7fa200b5-3b55-443a-ab0d-92177165c634)

Número de computadores de cada tipo:
Tipo 1: 89
Tipo 2: -269
Tipo 3: 549
Tipo 4: 12

Tivemos o valor de x negativo, que foi o -269, significa que a solução não é física, ou seja, não é possível produzir uma quantidade negativa de computadores. Isso pode indicar que os recursos disponíveis não são suficientes para atender à demanda ou que o modelo matemático não é adequado para o problema.



