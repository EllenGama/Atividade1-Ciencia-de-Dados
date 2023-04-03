# Aula1-Ciencia-de-Dados
Imagina-se que você é um dos programadores responsáveis pela construção de app de vendas para uma determinada empresa X que vende em atacado. Uma das estratégias de vendas dessa empresa X é dar desconto maiores por unidade 

-------INÍCIO-------
print('Bem vindo a loja da Ellen da Silva Gama RU4064718')

valororiginal = float( input('Entre com o Valor do Produto: R$') )

quantidade = int(input('Entre com a quantidade do produto?'))

if 0 <= quantidade < 10:

    desconto = 0

elif 10 <= quantidade < 100:

    desconto = 0.5

elif 100 <= quantidade < 1000:

     desconto = 0.10

else:

   desconto = 0.15

# Resultados:
semdesconto = valororiginal*quantidade

comdesconto = semdesconto - semdesconto*desconto

print('O valor sem desconto foi R${:.2f} ' .format(semdesconto))

print('O valor com desconto foi R${:.2f}   (desconto {:.0f}%)'

.format(comdesconto, 100*desconto))

print('Obrigada pela preferência!')


-------FIM-------
