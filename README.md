# agazati_doga

<img src="frog.gif" alt="GIF kép leírása"> <img src="frog.gif" alt="GIF kép leírása"> <img src="frog.gif" alt="GIF kép leírása"> <img src="frog.gif" alt="GIF kép leírása"> <img src="frog.gif" alt="GIF kép leírása">

```python


'''
Irj egy függvényt melyik_nagyobb() néven ami bemenettként kát számot kap
és eldönti hogy melyik szám a nagyobb és azzal
a számmal tér vissza amelyik szám a nagyobb!
'''

a = 4
b = 7

def melyik_nagyobb(a,b):
    pass


'''
Fejleszd tovább a melyik_nagyobb() függvényt azzal hogy döntetlen esetén
jelezze hogy a két szám egyenlő az alábbi kimenettel:
A két szám egyenlő!
'''

def melyik_nagyobb2(a,b):
    pass



'''
5.
irj egy függvényt oszthato_3_mal() néven, amely bekér felhasználótól egy számot és ha a szám osztható hárommal akkor térjen vissza a függvény, hogy:
A szám 3-mal osztható.
Ha a szám nem osztható hárommal, akkor:
A szám 3-mal nem osztható.
'''

def oszthato_3_mal():
    pass


'''
6.
Készíts függvényt harommal_oszthato(p) néven. 
Ha p osztható hárommal, akkor a függvény visszatérési értéke: True
Ha p nem osztható hárommal, akkor a függvény visszatérési értéke legyen False.
'''

p = 3

def harommal_oszthato(p):
    pass



'''
1.
Készíts egy programot, ami bekér egy számot a felhasználótól. 
Ha ez a szám páros, akkor írja ki hogy:
A szám páros.
Ha a szám páratlan, akkor írja ki, hogy: 
A szám páratlan.
'''




'''
2.
Készíts függvényt paros(p) néven. 
Ha p páros, akkor a függvény térjen vissza True értékkel,
ha p páratlan, akkor a függvény visszatérési értéke legyen False.
'''

p = 2

def paros(p):
    pass

"""
3.
Készíts függvényt abszolut(p) néven. 
A függvénybe beirt szam abszolut értékével térjen vissza
"""

xd = -2

def abszolut(xd):
    pass
    







# Nehézségi szint: bolondos szamuráj

lista = [1,2,3,4,5,6,7,8,9,10]
'''
1. Hány szám van a listában?
Készíts függvényt lista_elemek_szama() néven,
amely visszatér egy lista elemeinek a számával
'''


def lista_elemek_szama(lista):
    pass 







'''
2. Melyik a legkisebb szám a listában?
Készíts függvényt legkisebb() néven,
amely visszatér egy számokat tartalmazó lista legkisebb számával.
'''

def legkisebb(lista):
    pass
    


'''
3. Mennyi a lista számainak összege?
Készíts függvényt osszeg() néven,
amely visszatér egy számokat tartalmazó lista számainak összegével.
'''

def osszeg(lista):
    pass


'''
4. Mennyi a lista számainak szorzata?
Készíts függvényt szorzat() néven,
amely visszatér egy számokat tartalmazó lista számainak szorzatával.
'''

def szorzat(lista):
    pass



'''
5. Melyik a legnagyobb szám a listában?
Készíts függvényt legnagyobb() néven,
amely visszatér egy számokat tartalmazó lista legnagyobb számával.
'''

def legnagyobb():
    pass


'''
6. Melyik a legelső szám a listában?
Készíts függvényt legelso() néven,
amely visszatér egy számokat tartalmazó lista legelső számával.
'''

def legelso():
    pass


'''
7. Melyik a utolsó szám a listában?
Készíts függvényt utolso() néven,
amely visszatér egy számokat tartalmazó lista utolsó számával.
'''

def utolso():
    pass

'''
8. Mennyi a páros számok száma a listában?
Készíts függvényt parosok_szama() néven,
amely visszatér egy számokat tartalmazó lista páros számainak számával.
'''


def parosok_szama():
    pass

'''
9. Első kettő.
Készíts függvényt elso_ketto() néven,
amely visszatér egy számokat tartalmazó lista első két számával mint listával.
'''

def elso_ketto():
    pass

'''
10. Első és utolsó
Készíts függvényt elso_utolso() néven,
amely visszatér egy számokat tartalmazó lista első ás utolsó számával mint listával.
'''

def elso_utolso():
    pass



# nehézségi szint: DOOM eternal

filename = "lorem.txt"

"""11. olvasd be a 'lorem.txt' szöveges állományt és állapitsd meg hogy:
Irj egy hany_karakter() függvényt ami megszámolja hogy, hány darab karakter
van benne
"""

def hany_karakter(filename):
    with open(filename) as f:
        pass


"""12. olvasd be a 'lorem.txt' szöveges állományt és állapitsd meg hogy:
Irj egy hany_szo() függvényt ami megszámolja hogy, hány darab szó van benne
"""

def hany_szo():
    pass



"""13. olvasd be a 'lorem.txt' szöveges állományt és állapitsd meg hogy:
Irj egy hany_r_betu() függvényt ami megszámolja hogy, hány darab 'r' betű van benne
"""

def hany_r_betu():
    pass


"""12. olvasd be a 'lorem.txt' szöveges állományt és állapitsd meg hogy:
Irj egy hany_lorem() függvényt ami megszámolja hogy, hány darab 'lorem' szó van benne
"""



def hany_lorem():
    pass



c = [0,1,2,3,4,5,-12,6,7,8,9,10]
c1 = [1,2,3,4,5,6,7,8,9,10]
p2 = 1
p3 = 2
xd4 = -4
haromocska = 9
haromocska2 = 9


assert lista_elemek_szama(c) == 12, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert legkisebb(c) == -12, f"Hiba: legkisebb() függvény rosszul müködik"

assert osszeg(c) == 43, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert szorzat(c1) == 3628800, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert legnagyobb(c) == 10, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert legelso(c) == 0, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert utolso(c) == 10, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert parosok_szama(c) == 7, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert elso_ketto(c) == [0,1], f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert elso_utolso(c) == [0,10], f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert paros(p2) == False, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert paros(p3) == True, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert abszolut(xd4) == 4, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert oszthato_3_mal(p2) == "A szám 3-mal nem osztható.", f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert oszthato_3_mal(haromocska) == "A szám 3-mal osztható.", f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert harommal_oszthato(p2) == False, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert harommal_oszthato(haromocska) == True, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert melyik_nagyobb(haromocska,xd4) == 9, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert melyik_nagyobb2(haromocska,xd4) == 9, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert melyik_nagyob2(haromocska,haromocska2) == "A két szám egyenlő!", f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert hany_karakter(filename) == 8397, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert hany_szo(filename) == 1100, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert hany_r_betu(filename) == 391, f"Hiba: lista_elemek_szama() függvény rosszul müködik"

assert hany_lorem(filename) == 15, f"Hiba: lista_elemek_szama() függvény rosszul müködik"



```
