# Programação Orientada a Objetos

**_Vantagens de POO:_**

## COMERNada

> `Confiável`, o isolamento entre as partes gera software seguro. Ao alterar uma parte, nenhuma outra é afetada. Ex: pilha e controle remoto

> `Oportuno`, ao dividir tudo em partes, várias delas conseguem ser desenvolvidas em paralelo.

> `Manutenivel`, atualizar um software é mais fácil. Uma pequena modificação vai beneficiar todas as partes que usarem o objeto.

> `Extensivel`, o software não é estático, ele deve crescer para permanecer útil.

> `Reutilizavel`, podemos usar objetos de um sistema que criamos em um objeto futuro.

> `Natural`, todo software orientado a objetos tem que ser natural, uma coisa natural é algo mais fácil de entender. Você se preocupa mais nas funcionalidades do que nos detalhes de implementação.

# Objeto

Coisa material ou abstrata que pode ser percebida pelos sentidos e descrita por meio de suas caracteristicas, comportamento e estado atual.

Exemplo:  
`Objeto = Caneta`  
**Classe** é o modelo para classificar objeto (molde)
**(Atributo) Coisas que eu tenho:**  
modelo: bic  
cor: azul  
ponta: 0.5  
carga: 90%  
tampada: falso  
**(Métodos)Coisas que eu faço:**  
escrever, rabiscar, pintar, tampar, destampar  
**(Estado)**  
destampada  
azul  
90% de carga

`Classe Caneta`  
`modelo`: _Caractere_  
`cor`: _Caractere_  
`ponta`: _Real_  
`carga`: _Inteiro_  
_acima são os atributos definidos d a classe_

    Metodo rabiscar()
        Se (tampada) entao
            Escreva("ERRO")
            senao
            Escreva("Rabisco")
            FimSe
    FimMetodo
    Metodo tampar()
        tampada = verdadeiro
    FimMetodo
    FimClasse

``

# Instanciar

É gerar um objeto a partir de uma classe.

**sem () = `atributo`**  
**com () = `método`**

c1 = **nova** `Caneta`  
c1.cor: azul  
c1.ponta: 1.0  
c1.carga: 50%  
c1.tampada(): verdadeiro  
c1.rabiscar(): falso

c2 = **nova** `Caneta`  
c1.cor: vermelho  
c1.ponta: 0.5  
c1.carga: 30%  
c1.tampada(): falso  
c1.rabiscar(): verdadeiro

Classe e objeto são praticamente irmãos, pois um conceito depende do outro.

**_Exercicío:_** **Classifique dois objetos que você está vendo neste momento.**

OBJETOS
Tesoura  
**Atributos**  
Buracos
Bordas  
Ponta aguda
Leve

**Metodos**
abrir  
fechar  
cortar  
furar

**Estado**  
fechada  
50% usada

Cola
**Atributos**
Marca
Tampa
Boca
Recipiente
Adesivo
Descrição
Liquido
Peso

**Metodos**
Abrir
Fechar
Destampar
Tampar
Espremer
Apertar

**Estado**
Aberto
30% usada
