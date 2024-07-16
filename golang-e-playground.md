# Golang e Playground

- Linguagem Go: O que é? onde mora? é de comer?

- [Golang site oficial](http://golang.org/)
- [Go Playground](https://play.golang.org/)

## TODO

- [x] Como surgiu Go e quem criou
- [x] Onde é usada
- [x] Características
- [x] compilação / interpretação 
- [x] tipos
    - [x] os tipos em Go
    - [x] tipagem dinâmica / tipagem estática
    - [x] tipagem forte / tipagem fraca
- [x] Go Playground


### Como surgiu Go e quem criou

Go foi criada em setembro de 2007 no Google
por Robert Griesemer (Java HotSpot virtual), Rob Pike(UNIX / UTF-8) e Ken Thompson (UTF-8 / UNIX / B / C).
Lançada publicamente em 2009.

### Onde é usada

github.com/heroku
github.com/ibm
github.com/google
github.com/mercadolibre
github.com/uber
github.com/digitalocean
github.com/twitchtv
github.com/medium

etc ...


## Características

- linguagem de propósito geral.
- Estaticamente tipada.
- Compilada 
- Concorrente
- multiplataforma
- cross compile
- imperativa/estruturada

## compilação / interpretação 

**linguagem compilada:** seus códigos fontes são transformados diretamente em linguagem de máquina (da arquitetura que você está compilando o código).

**Linguagem interpretada:** código fonte transformados em uma linguagem intermediária (específica de cada linguagem), que será interpretada pela **máquina virtual** da linguagem quando o programa for executado.

## tipos:

ver em: https://golang.org/ref/spec#Types

**Tipos básicos:** numéricos, strings, e booleanos.

**Tipos Agregados:** Array e structs.

**Tipos Referência**: ponteiros, slices, maps, functions, e channels.

**Tipo Interface:** tipo interface.

### tipagem dinâmica / tipagem estática

**Dinâmica:** Linguagem escolhe que tipo utilizar dinamicamente para cada variável.
(podendo alterá-lo durante a compilação ou a execução do programa.)

**estática**: Precisa definir os tipos de cada variável e não permite alterar durante a execução/compilação do programa.


### tipagem forte / tipagem fraca

**tipagem fraca:** realiza conversões automaticamente entre tipos diferentes de dados (conversão implicita)

p-r-e-r-i-g-o
![](prerigo.jpg)

**tipagem forte:** não realiza conversão implícita.

----

Uma colinha de Python

## Python

https://docs.python.org/pt-br/3/library/stdtypes.html

### tipos

- int, float, complex, bool, str, list, tuple, dict, set

tipos avançados:

- frozenset, range, bytes, bytearray, memoryview...)


ver tamanho em bytes ocupados pela variável
`sys.getsizeof()`


---

Uma colinha de Lua

https://www.lua.org/manual/5.4/manual.html#2.1

### tipos

8 tipos

- nil, boolean, number, string, function, userdata, thread, and table






