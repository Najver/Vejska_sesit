

# Matematika
---
### Vektor 
def(vektor) uspořádaná n-tice reálných čísel 
zápis/notace : (a1 ,a2 ,aX), a1, ... € R
![[Fotky/Pasted image 20250917144126.png]]

(1,2) + (3,0) = (4,2)

![[Fotky/Pasted image 20250917144337.png]]

5 * (1,2) = (5,10)
(1,2) * 5 = (5,10)

Skalární součin

(X1 ,X2 , ..., Xn) * (Y1 ,Y2 , ...y Yn) = X1 * Y1 + X2 * Y2 + ... + Xn * Yn
(1,2) * (3,0) = 3 + 0 = 3

X s šipkou nahoře je značka pro vektor 
![[Fotky/Pasted image 20250917144731.png]]


## Definice lineární kombinace vektorů

Př: (11,4) je LK (1,2) (3,0)
(11,4) = 2(1,2) + 3(3,0)

(11,4) není LK (0,1), (0,2)

(11,4) = C1(0,1) + C2(0,2)
	  = (0,C1 + 0, 2C2)
	Nelze

Def(Nulový vektor) : značí se O s šipkou = (01 , ... ,0 )

**Triviální LK** : C1 = C2 = ... = Cn = 0

Koeficient LK

## Definice lineární závislost a nezávislost

Př: (0,1), (0,2) Jsou LZ
(0,0) = -2(0,1) + 1(0,2)

Př:(1,2),(3,0) jsou LN
(0,0) = C1(1,2) + C2(3,0)
(0,0) = (C1 + 3C2, 2C1)

0 = C1 + 3C2
0 = 2C1 -> C1 = 0    C2 = 0

Př: (0,2) je LN
(0,0) = C1(0,2)
(0,0) = (0,2C1)
0 = 0
0 = 2C1 -> C1 = 0

Př: (0,0) je LZ
(0,0) = C1(0,0)
(0,0) = (0,0) platí pro C1 € R

ZK € NAT   : Nutná podmínka : alespoň 30 bodů
		 : Postačující podmínka : alespoň 80 bodů
		 : Nutná a postačující: alespoň 60 bodů

## Matice

![[Pasted image 20250917152155.png]]

Aij € R 
m x n 
Ř x S

Značení : A, A m x n, [a4], [aij]m x n

![[Pasted image 20250917152605.png]]
Hlavní diagonála je přes čísla 1, 5 a 9

![[Pasted image 20250917152707.png]]
Hlavní diagonála je přes čísla 1 a 5

![[Pasted image 20250917152805.png]]
Hlavní diagonála je přes čísla 1 a 4

### Čtvercová matice:
- A typu n x n

### Jednotková matice:
- čtvercová, na hl diagonále má 1
![[Pasted image 20250917153020.png]]

### Trojúhelníková matice:
![[Pasted image 20250917153130.png]]
nebo
![[Pasted image 20250917153142.png]]

A ještě pro m x n
![[Pasted image 20250917153446.png]]
nebo
![[Pasted image 20250917153456.png]]

### Nulová matice
![[Pasted image 20250917153323.png]]

### Schodovitá/V Gausově tvaru matice
![[Pasted image 20250917153646.png]]
Má tvar schodů(Schody jsou z nul)
Trojúhelníkové jsou schodové

### Matice:

![[Pasted image 20250917154110.png]]
LN
hodnost matice = 2

![[Pasted image 20250917154132.png]]
LZ
hodnost matice = 1

Hodnost nulové matice = 0

Hodnost je počet nenulových řádků

!Nesmíme násobit matici/řádek matice nulou!