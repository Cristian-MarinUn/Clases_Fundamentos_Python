nombre = "pedro"
>>> numero1 =  23
>>> numero = 29.4343453
>>> type(nombre)
<class 'str'>
>>> type(numero1)
<class 'int'>
>>> type(numero)
<class 'float'>
>>> cadena = "pablo estuvo ayer en el parque"
>>> cadena.len()
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
AttributeError: 'str' object has no attribute 'len'
>>> len(cadena)
30
>>> cadena.fin("y")
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
AttributeError: 'str' object has no attribute 'fin'. Did you mean: 'find'?
>>> cadena.find("y")
14
>>> cadena.find("el")
21
>>> cadena.replace("parque","casa")
'pablo estuvo ayer en el casa'
>>> cadena
'pablo estuvo ayer en el parque'
>>> cadena = cadena.replace("parque","casa")
>>> cadena 
'pablo estuvo ayer en el casa'
>>> cadena = "  pablo estuvo ayer en el parque   "
>>> cadena.strip()
'pablo estuvo ayer en el parque'
>>> cadena.lstrip()
'pablo estuvo ayer en el parque   '
>>> cadena.rstrip()
'  pablo estuvo ayer en el parque'
>>> cadena.upper()
'  PABLO ESTUVO AYER EN EL PARQUE   '
>>> cadena.lower()
'  pablo estuvo ayer en el parque   '
>>> cadena = cadena.lstrip()
>>> cadena.capitalize()
'Pablo estuvo ayer en el parque   '
>>> cadena.split(" ")
['pablo', 'estuvo', 'ayer', 'en', 'el', 'parque', '', '', '']
>>> cadena2 = "asdfghhjklñzxcvbn qwert"
>>> ",".join(cadena2)
'a,s,d,f,g,h,h,j,k,l,ñ,z,x,c,v,b,n, ,q,w,e,r,t'
>>> cadena.title()
'Pablo Estuvo Ayer En El Parque   '
>>> #comnetario 
>>> #comenta
>>> """ comenta
... 
... 
... 
... 
... """
' comenta\n\n\n\n\n'
>>> 
>>> cadena1 = "cadena\nde texto\nde varias\nlineas"
>>> cadena1
'cadena\nde texto\nde varias\nlineas'
>>> print(cadena1)
cadena
de texto
de varias
lineas
>>> print("texto"*4)
textotextotextotexto
>>> #concatenacion 
>>> texte1 = "mundo"
>>> texte2 = "vez"
>>> print("hola" + texte1 + "otra" + texte2)
holamundootravez
>>> print("hola " + texte1 + " otra " + texte2)
hola mundo otra vez
>>> print("hola {0} otra {1}".format(texte1,texte2))
hola mundo otra vez
>>> num = 3
>>> text3 = "es el numero "
>>> print(text3 + num)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: can only concatenate str (not "int") to str
>>> print(text3 + str(num))
es el numero 3
>>> "x" in cadena
False
>>> "a" in cadena
True
>>> "ayer" in cadena
True
>>> cadena
'pablo estuvo ayer en el parque   '
>>> cadena[1:23]
'ablo estuvo ayer en el'
>>> cadena[0:8]
'pablo es'
>>> cadena[:8]
'pablo es'
>>> cadena[:2387]
'pablo estuvo ayer en el parque   '
>>> cadena[-1]
' '
>>> cadena[-2]
' '
>>> cadena[-6]
'q'
>>> cadena[-9:-4]
'parqu'
>>> +
  File "<stdin>", line 1
    +
     ^
SyntaxError: invalid syntax
>>> """ +
... -
... *
... /
... %
... **
... //
... """
' +\n-\n*\n/\n%\n**\n//\n'
>>> """
... >
... <
... ==
... >= 
... <=
... != diferente de """
'\n>\n<\n==\n>= \n<=\n!= diferente de '
>>> a = 23
>>> b = 7
>>> a + b
30
>>> a - b
16
>>> a % b
2
>>> a ** b
3404825447
>>> a < b 
False
>>> a > b
True
>>> a == b
False
>>> a != b
True
>>> if a == b:
... print("a es igual a b")
  File "<stdin>", line 2
    print("a es igual a b")
    ^
IndentationError: expected an indented block after 'if' statement on line 1
>>> if a == b:
... 	print("a es igual a b")
... 	
... 
>>> if a == b:
... 	print("a es igual a b")
... else:
... 	print("a y b no son iguales")
... 
a y b no son iguales
>>> if (a!=b) and (a > b):
... 	print("a es diferente y mayor que b")
... else:
... 	print("a y b son iguales")
... 
a es diferente y mayor que b
>>> if a!=b:
... print("a es diferente de b")
  File "<stdin>", line 2
    print("a es diferente de b")
    ^
IndentationError: expected an indented block after 'if' statement on line 1
>>> if a!=b:
... 	print("a es diferente de b")
... elif a > b:
... 	print("a es mayor que b")
... elif a < b:
... 	print("a es menor que b")
... elif a == "23": 
... 	print("a es un caracter")
... else: 
... 	print("a y b no existe")
... 
a es diferente de b
>>> t = (1,"a",3.5,6)
>>> type(t)
<class 'tuple'>
>>> t[1]
'a'
>>> t=(1,"a",("b",4,8),52)
>>> t
(1, 'a', ('b', 4, 8), 52)
>>> t.index(8)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ValueError: tuple.index(x): x not in tuple
>>> 
>>> t.index(1)
0
>>> t = (1,2,4,6,4,7)
>>> t.index(4)
2
>>> t.count(4)
2
>>> len(t)
6
