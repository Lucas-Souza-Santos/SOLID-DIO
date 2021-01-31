# O que é o SOLID ?
```
SOLID é um acrônimo dos princípios da programação orientada a
objetos descritas por Robert C. martin ("Uncle Bob").

Auxiliam o programador a escrever códigos mais limpos, 
facilitando a refatoração e estimulando o reaproveitamento do 
código.
```
* S.r.p: Single Responsibility Principle ou Principio da Responsabilidade única
* O.c.p: Open Closed Principle ou Princípio Aberto Fechado
* L.s.p: Liskov Substitution Principle ou Princípio da Sbstituição de Liskov
* I.s.p: Interface Segregation Principle ou Principio da Segregação de Liskov 
* D.i.p: Dependency Inversion Principle ou Princípio da Inversaõ da Dependência

## Parte 2: S.R.P Single responsibility Principle
```
"A class should have one, and only one, reason to change."
Uma classe deve ter um, e somente um, motivo para mudar. 
- A classe deve possuir uma única responsabilidade dentro do software
```
## Parte 3: O.C.P Open Closed Principle
```
"You should be able to extend a classes behavior, without modifying it"
Você deve poder estender um comportamento de classe, modifica-lo 
Objetos devem estar abertos para extensão, mas fechados para modificação
Quando novos comportamentos precisam ser adicionados no 
software, *devemos estender e não alterar o código fonte original*.
```
## Parte 4: Liskov Substitution Principle
```
"Derived classes must be substitutable for their base classes."
Classes derivadas devem ser substituíveis por suas classesl base.
O princípio da substituição de Liskov foi introduzido por Barbara Liskov em 1987: 
"Se para cada objeto *o1* do *tipo S* há um objeto *o2* do 
*tipo T* de forma que, para todos os *programas P*, o 
comportamento de *P* é inalterado quando *o1* é substituído por
*o2*, então *S é um subtipo de T*."
```
## Parte 5: I.S.P Interface Segregation Principle
```
"Make fine grained interfaces that are client specific"
Faça interfaces refinadas que são específicas do cliente.
- Uma classe *não deve* ser forçada a *implementar* interfaces e *métodos* que *naõ serão utilizados*.
- É melhor criar *interfaces* mais *específicas* ao *invés de* termos uma única *interface genérica.*
```

## Parte 6: D.I.P Dependency Inversion Principle
```
"Depend on abstractions, not on concretions."
Dependa de abstrações e não de implementações 
- Um módulo de alto nível naõ deve depender de modulos de baixo nível, ambos devem depender da abstração.

- PS: Inversão de Dependência *não é* igual a Injeção de Dependência.
```




