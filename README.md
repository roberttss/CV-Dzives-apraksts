# CV-Dzives-apraksts

### citats
>Ja vēlies, lai citi ir laimīgi, esi līdzcietīgs. Ja vēlies pats būt laimīgs, esi līdzcietīgs.
 
### koda gabals 
n = int(input("Ievadiet Fibonačī sērijas vērtību skaitu (ieskaitot pirmo vērtību 0): "))

summa = 0 # Sagatavo vērtību summas saskaitīšanai
skaitlis1 = 0   # Ievada pirmās vērtības pirmajiem apreiķiniem
skaitlis2 = 1

for x in range(n):
    summa = summa + skaitlis1
    print(x,":",skaitlis1)
    skaitlis3 = skaitlis1 + skaitlis2 # 3 skaitlis = iepriekšējo 2 skaitļu summa.

    skaitlis1 = skaitlis2   # pārvada vērtības uz priekšu lai apreiķinātu nākošo skaitli.
    skaitlis2 = skaitlis3

print(summa)


