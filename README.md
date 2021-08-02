# Fonte-Ajustavel
### Objetivo: montar uma fonte de tensão ajustável entre 12V e 3V que funcione com uma corrente de saída de 100 mA.
# Componentes
Todos os preços foram conferidos no site https://www.baudaeletronica.com.br
| Componente  |  Preço  |
| ------------------- | ------------------- |
|  Capacitor Eletrolítico 470uF / 35V |  R$ 0,77 |
|  Resistor 2K7 5% (1/4W) |  R$ 0,05 |
|  Resistor 1K8 5% (1/4W) |  R$ 0,05 |
|  Ponte Retificadora KBPC1010 |  R$ 3,67 |
|  Diodo Zener 1N4743 [13V / 1W] |  R$ 0,19 |
|  Potenciômetro Linear de 5K (5000Ω) |  R$ 1,99 |
|  Transistor NPN BC337 |  R$ 0,20 |
|  Transformador Trafo 12V+12V 500mA - 110/220VAC |  R$ 32,86 |
Vídeo curto com explicação dos valores escolhidos: https://drive.google.com/file/d/1bg3l0aVqp5aAvlKfoLDQY94b8t1-KplE/view?usp=sharing

## ponte retificadora
Aproveita a energia vinda do gerador(tomada) em ambas as fases da onda.
## diodo zenner
O regulador de tensão, corta a tensão abaixo do ripple do capacitor, permitindo uma tensão constante na carga.
## potenciometro
Permite regular a tensão a tensão na carga.
## capacitor
O capacitor armazena um pouco da energia de cada onda vinda do gerador de corrente alternada(no nosso caso, a tomada) e libera tal energia quando a tensão cinda da fonte é inferior à do capacitor, evitando grandes variaçõesd e tensão.
## transistor
Amplifica e barra a corrente no circuito.
## resistor
limita a passagem da corrente no circuito.
## transformador
Diminui a tensão vinda da tomada.
# Link para o Falstad
https://tinyurl.com/yhgow4pc
# Imagem do circuito
![image](https://user-images.githubusercontent.com/68250033/127785311-03c42bc8-bcb4-443f-ba87-aa717113c6ab.png)
# Imagem do schematic
![image](https://user-images.githubusercontent.com/68250033/127785332-94cf212a-0213-4f40-a7f6-897098b376c7.png)
# Imagem do board
![image](https://user-images.githubusercontent.com/68250033/127785052-da3b0d05-0426-483a-90cd-1333ae8d7b56.png)

# Autoria 
Daniel Afonso Borges dos Santos- 12608581
