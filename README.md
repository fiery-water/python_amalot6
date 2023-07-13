# python_amalot6
pythonda for operatori bilan ishlash

ismlar=["ali","vali","soli","mavlon","dilsuz"]
for ism in ismlar:
    print(f"Salom {ism.title()}")
print("Kod ",len(ismlar)," marotaba takrorlandi")

sonlar=list(range(11,100,2))
for son in sonlar:
    print(son**3)

kursdoshlar=["Og'abek","Muslim","Shuhrat","Mirolim","Xushvaqt"]
for kursdosh in kursdoshlar:
    print("Assalomu alaykum",kursdosh,"sog'liklar yaxshimi")
    print(f"Assalomu alaykun , hurmatli {kursdosh} kursdosh sizni tug'lgan kuninggiz bilanchin qalbdan tabriklayman. ")
    print("Hurmat bilan kursdoshingiz Mavlon\n")


sonlar=list(range(-5,6))
sonlarning_kivadrati=[]
for son in sonlar:
    sonlarning_kivadrati.append(son**2)
print(sonlar)
print(sonlarning_kivadrati)
print(f"{son} sonining kivadrati {son**2} ga teng")
            
mevalar=[]
print("Qanday mevalar olmoqchisiz?")
for olinadigan_mevalar in range(6):
    mevalar.append(input(f"{olinadigan_mevalar+1}- mevani kiriting: "))
print("mevalar ro'yxati",mevalar)
    
