1 - B
2 - B
3 - D
4 - D
5 - B
6 - B
7 - 
var idade 
if idade < 16
	não pode votar
else if idade >= 16 && idade <18
	voto facultativo
else 
	voto obrigatório

8- 
Classe FormaGeometrica:
    Atributos:
        - cor

    Método Construtor(cor):
        Define o valor do atributo cor com o valor passado como parâmetro.

    Método CalcularArea():
        # Implementação genérica para cálculo de área, a ser sobrescrita pelas subclasses.

Classe Retangulo herda FormaGeometrica
    super Atributos
        cor
        largura
        comprimento
    
    Método Construtor (cor, largura, comprimento)
        definição da cor
        definição de largura
        definição de comprimento

    Método CalcularArea(): 
        largura * comprimento

Classe Circulo herda FormaGeometrica
    super Atributos
        cor
        raio
    
    Método Construtor (cor, largura, comprimento)
        definição da cor
        definição de raio

    Método CalcularArea(): 
        π * raio * raio
    

9- 
var velocidadeMaxima
var velocidadeInicial
var tempoMaximo
var tempo
var aceleração
var velocidade
var distanciaTotal
var distanciaPercorrida

if tempo <= tempoMaximo
    if velocidade < velocidadeMaxima
        velocidade = velocidadeInicial + aceleracao*tempo
    else
        velocidade = velocidadeMaxima

    distanciaPercorrida = velocidade * tempo
    if distanciaPercorrida >= distanciaTotal
        console.log(tempo)
    tempo ++
else 
    console.log(tempo excedido)
