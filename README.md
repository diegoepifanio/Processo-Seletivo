# Processo Seletivo
 EXERCICIOS  RESPOSTAS .

QUESTAO 1  


def pertence_sequencia_fibonacci(n):
  
    fib = [0, 1]
    
    while fib[-1] < n:
        fib.append(fib[-1] + fib[-2])
   
    if n in fib:
    return f"O número {n} pertence à sequência de Fibonacci."
    else:
        return f"O número {n} NÃO pertence à sequência de Fibonacci."


numero = 21 
print(pertence_sequencia_fibonacci(numero))


QUESTAO 2 


def verifica_letra_a(string):

    string_lower = string.lower()
    
  
    contagem = string_lower.count('a')
    
   
    if contagem > 0:
        return f"A letra 'a' aparece {contagem} vezes na string."
    else:
        return "A letra 'a' não aparece na string."


string_teste = "Amanhã é outro dia"
print(verifica_letra_a(string_teste))


QUESTAO 3 









QUESTAO 4

 
a) 1, 3, 5, 7, __   9
b) 2, 4, 8, 16, 32, 64, ____ 128
c) 0, 1, 4, 9, 16, 25, 36, ____  49
d) 4, 16, 36, 64, ____ 100
e) 1, 1, 2, 3, 5, 8, ____ 13
f) 2,10, 12, 16, 17, 18, 19, ____ 20



QUESTAO 5 


Ligue o primeiro interruptor e espere alguns minutos.
Desligue o primeiro interruptor e ligue o segundo interruptor.
Entre na sala.



Quando você entrar na sala, uma lâmpada estará acesa, outra estará desligada e uma terceira estará apagada mas quente.
 A lâmpada que está acesa estará ligada ao interruptor que você deixou ligado. A lâmpada que está desligada estará conectada 
ao interruptor que você ligou e desligou. E a lâmpada que está apagada mas quente estará conectada ao interruptor que você
 nunca mexeu. Dessa forma, você pode determinar qual interruptor controla qual lâmpada.














