[Yeni Metin Belgesi.txt](https://github.com/user-attachments/files/25367657/Yeni.Metin.Belgesi.txt)
import random

rsi=random.randint(1,100)

def trade(rsi):
    if rsi<20:
        print("..............alım yap")
    elif rsi>80:
        print("satış yap.................")
    else:
        print("==pozisyonunu koru.===")


a=45
b='hasan'
def alper1(arr):
    try:
        SAYAÇ=0

        while True:

            X=arr[SAYAÇ]
            SAYAÇ+=1
    except:
         print(SAYAÇ)

def alper2(arr):
    try:
        SAYAÇ=0

        while True:

            X=arr[SAYAÇ]
            SAYAÇ+=1
    except:
         pass
    return SAYAÇ

from main import *
a=['doğa','alperen','mahmut','baki','yusuf']
z=alper2(a)
print(z)
print(type(z))

from cacık2 import *
import random
while True:
    rsi_=random.randint(1,100)
    print(rsi_)
    trade(rsi_)
