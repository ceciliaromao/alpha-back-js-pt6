![](https://portal.alphaedtech.org.br/images/edtech/logo-edtech.webp)

# Back-End

## Módulo 7 - JavaScript - Part 6

### Exercícios de classe 🏫

#### Questão 1
Crie uma página web que ‘arme uma bomba’ (imagem de uma bomba) que ‘exploda’ em 10 segundos, considerando:
* Utilize o setTimeout para ‘armar a bomba’ (bomba com pavil aceso);
* Caso o usuário clique na bomba, utilize o clearTimeout para desarmar a bomba (bomba com pavil apagado);
* Caso a bomba não seja desarmada, ao terminar o tempo, a bomba deve explodir e um som de explosão deve ser tocado.

#### Questão 2
Substitua o setTimeout do exercício anterior, aumente o tempo para 60 segundos e adicione um setInterval que mostra os segundos decrementando de 1 em 1 segundo até a explosão caso não seja desarmada, considerando:
* A cada ‘tick’ de tempo decrescente, adicione um som de ‘tick’ curto para demonstrar que o tempo está acabando;
* Se o usuário clicar na bomba, utilizar o clearInterval para desarmar a bomba;
* Se o usuário não clicar na bomba, a bomba deve explodir (som de explosão) e a contagem deve parar.

#### Questão 3
Crie uma página web que contenha um alarme no qual o usuário define os minutos (máximo 59 minutos) e segundos e clica em um botão que inicia a contagem regressiva, considerando:
* Utilizar o HTML select para seleção dos minutos e segundos;
* Criar um botão que inicia a contagem regressiva que ao ser clicado este se torna um botão de desarmar alarme;
* O contador regressivo mostra o tempo a cada segundo;
* Quando faltar menos de 5% do tempo inicial mudar a interface de contagem para informar que o tempo está acabando;
* Ao término da contagem, o tempo deve parar de ser decrementado e deve-se disparar um alarme (som de alarme) informando que o tempo acabou;
* Se o usuário clicar no botão de desarmar alarme, a contagem deve ser parada e, caso o alarme esteja tocando, o som deve parar, transformando o botão para que possa armar o alarme novamente.

###### tags: `módulo 7` `back-end` `JavaScript`