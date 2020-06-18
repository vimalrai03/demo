# demo
score = input("enter score:")
sc = float(score)
if (sc<0.0 || sc>1.0) :
    print ("error,out of range")
    exit()
elif sc>=0.9 :
    print ("A")

elif sc<0.9&sc>=0.8 :
    print ("B")

elif sc<0.8&sc>=0.7 :
    print ("C")

elif sc<0.7&sc>=0.6 :
    print ("D")

else:
    print ("F")
