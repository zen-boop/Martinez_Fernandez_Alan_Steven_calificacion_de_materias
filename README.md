print("");m=["pensamiento matematico","español","ingles","quimica","civismo","frances"]; a=str("");c=[10,6,8,9,6,10] #defino las variables
while(a!="salir"):#mientas "a" sea diferente a salir se repetira
    print(m);print("")#imprime la variable y separa 
    a=str(input("coloca la matreia, en caso de querer ver tus calificaciones coloca salir "));print(""); """separa define como str 
    hace posible modificar la variable y da una instruccion"""
    if a=="pensamiento matematico":#si "a" es igua a "pensamiento matematico"se imprimira la instruccion
        print("estoy cursando la materia ",m[0]);print("")#da instruccion y imprime la primera opccion de la lista y separa
    elif a=="español":#si "a" es igua a "español"se imprimira la instruccion
        print("estoy cursando la materia",m[1]);print("")#da instruccion y imprime la segunda opccion de la lista
    elif a=="ingles":#si "a" es igua a "ingles"se imprimira la instruccion
        print("estoy cursando la materia",m[2]);print("")#da instruccion y imprime la tercera opccion de la lista y separa
    elif a=="quimica":#si "a" es igua a "quimica"se imprimira la instruccion
        print("estoy cursando la materia",m[3]);print("")#da instruccion y imprime la cuarta opccion de la lista y separa
    elif a=="civismo":#si "a" es igua a "civismo"se imprimira la instruccion
        print("estoy cursando la materia",m[4]);print("")#da instruccion y imprime la quinta opccion de la lista y separa
    elif a=="frances":#si "a" es igua a "frances"se imprimira la instruccion
        print("estoy cursando la materia",m[5]);print("")#da instruccion y imprime la sexta opccion de la lista y separa
    elif a=="salir":#si "a" es igua a "salir"se imprimira la instruccion
        print("en ",m[0],"sacaste ",c[0]);print("")#imprime la calificacion y separa
        print("en ",m[1],"sacaste ",c[1]);print("")#imprime la calificacion y separa
        print("en ",m[2],"sacaste ",c[2]);print("")#imprime la calificacion y separa
        print("en ",m[3],"sacaste ",c[3]);print("")#imprime la calificacion y separa
        print("en ",m[4],"sacaste ",c[4]);print("")#imprime la calificacion y separa
        print("en ",m[5],"sacaste ",c[5]);print("")#imprime la calificacion y separa
    else:#en caso de que no se cumpla alguna condicion se imprimira esto
        print("esa opccion no exsiste");print("")#imprime una instruccion y separa
        ![image](https://github.com/user-attachments/assets/ae809747-848f-4ac0-8650-37c7f52de772)
