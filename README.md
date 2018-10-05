
## Interview Question 1 of 1

### Crie um eficiente algoritmo para encontrar um item em uma lista ordenada de itens.
### Deve retornar -1 se não for encontrado nada ou deve retornar o item que encontramos e o seu índice

```
<<<
Exemplo: Dada a seguinte lista ordenada [9, 10, 21, 30, 50] e o iten que procuramos (50)

Deve retornar 50 (O iten encontrado) e o índice do vector/lista onde foi encontrado o mesmo, 50, 4

Exemplo 2: Dada a seguinte lista ordenada [9, 10, 21, 30, 50] e o iten que procuramos (521)

Deve retornar -1

O algoritmo deve ser O log(n) e não O(n)

<<<

```
## Search Algorithm

```ruby

list = [1,3,5,7,23,56,71,75,91,96]
chave = 91

def bSearch(list, k) 
    n = list.count
    
end

puts bSearch(list, chave)

```