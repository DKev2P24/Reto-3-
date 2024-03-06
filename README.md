# Reto 3: Números Primos y Raices

## Logo del team:
***

 [![Logo-equipo.webp](https://i.postimg.cc/Z5BYw1Tx/Logo-equipo.webp)](https://postimg.cc/9D2jMgwD)

## En este repositorio estan los algoritmos para:
1. Algoritmo para saber la cantidad de números primos hasta un número natural n en..
  - Pseudocodigo
  - Diagrama de Flujo 
2. Algoritmo para sacar raiz cuadrada a un número n en...
	 
  - Pseudocodigo
   - Diagrama de Flujo   

## 

Plantear el algoritmo para obtener los números primos hasta un valor dado **n**. Para ello:

## Algoritmo 
### (Diagrama de Flujo)
```mermaid
flowchart TD
    A[Inicio] -->B(Numero n Natural)
    B --> C{Lista de impares}
    C --> D[I= 3-n]-->F
    C --> E[N= 1-√n]-->F 
    F{Iₓ/Nₑ}-->H[¿cociente ≠ 1 o Iₓ?]
    H-->|si|S{¿Es natural?}-->|si|WW{Iₓ no pertenece a P}
    S-->|NO|J
H-->|no|J[¿Nₑ es el ultimo elemento de N?]-->|no|L
J-->|si|Y{Iₓ Pertence a P}-->N-->|SI|P{"Elementos de P" + 1}
L(Nₑ₊₁)-->F
N{¿Iₓ es el ultimo elemento de I?}-->|no|O{Iₓ₊₁}-->x{N₁}-->F
P-->Q{Cantidad de numeros primos hasta n}
Q-->R{Fin}
```
### (Pseudocódigo)
```pseudocode
n : numero ℕ cualquieraa
I : Impares [3,n]
N : Impares [1,√n]
M : (Iₓ/Nₑ)
 Inicio
   Para n entonces
    Para (Iₓ,Nₑ) hacer
     M 
     si M ∈ ℕ ; M ≠ 1 ; M ≠ Iₓ
      entonces Iₓ ∉ P
     Si no si  M = 1 o M = Iₓ
      entonces
         Si Nₑ es el ultimo elemento de N
           entonces Iₓ ∈ P
             si Iₓ es el ultimo elemento de I
             entonces
             z : "Elementos de P" + 1 
             escribir (" hay z numeros primos hasta n ")
             si no  
             (Iₓ₊₁/N₁)
             entonces 
             M
             Fin Si
         si no
             entonces Nₑ₊₁
             M
         Fin Si
     Fin Si
    Fin Para
   Fin Para
 Fin
```
## 

Plantear el algoritmo para conocer la raiz de un numero n natural
## Algoritmo 
### (Diagrama de Flujo)
![](https://github.com/DKev2P24/Reto-3-/blob/main/%20raices.png)

### (Pseudocódigo)
  #### no me alcanzó :´(

