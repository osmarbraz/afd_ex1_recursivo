# AFD Exercício 1

Implementação java recursivo de um AFD, que reconhece a linguagem:

aba, abba, abbba, abbbba, .... 

x &isin; {a,b}
A1 = <{a, b} , { s0, s1, s2}, s0, δ, {s2}>, onde δ é:
δ{s0,a) = s1
δ{s1,b) = s1
δ{s1,a) = s2

AFD:
![AFD imagem](/assets/images/afdex1.png)
