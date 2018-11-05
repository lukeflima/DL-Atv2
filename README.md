# LeNet-Naive
O objetivo deste trabalho consiste na implementação da LeNet-5 com ReLU, minibatch = 32, batch normalization, inicialização de pesos de He, saída SoftMax. Devendo ser aplicado no banco MNIST.  
## Implementação
Este projeto consiste na implementação da arquitetura LeNet-5. Também foi usado o método do gradiente como forma de aprendizagem, para isso, foi necessário a redução de neurônios nas camadas, para que o algoritmo pudesse rodar de forma mais rápida.  
## Resultados
Foram feitas 44 iterações e houve uma redução da perda média com o uso da busca local usando gradiente com decaimento consideravelmente rápida no início, mas com atenuação com poucas iterações, chegando em uma perda média de 1.979500943 após as 44 iterações.  

![Gráfico da perda média](https://i.imgur.com/bPwejUf.png)
