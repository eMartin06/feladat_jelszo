
felhasznalo=False
jelszavacska=False

while felhasznalo_nev !="bori99" and jelszo != "Szivecske<3":
    felhasznalo_nev=input('Adja meg a felhasználónevét! ')
    jelszo=input('Adja meg a jelszavát! ')
    print('Engedély megtagadva.')

if felhasznalo_nev =="bori99":
    felhasznalo=True
    
if jelszo == "Szivecske<3":
    jelszavacska=True
    
if felhasznalo ==True and jelszavacska ==True:
    print('Belépés engedélyezve.')

    