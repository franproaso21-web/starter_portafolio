ingreso_mensual = 100000
gasto_mensual =  60000

#if anidado y else if (elif)

if ingreso_mensual > 10000:
    if ingreso_mensual - gasto_mensual < 0:
        print("Gayo estas broke ")
    elif ingreso_mensual - gasto_mensual < 6000:
        print("Eres rico y gastas razonablemente")
    else:
        "Eres rico y derrochas mucho dinero"

elif ingreso_mensual > 1000:
    print("No eres rico, pero tampoco pobre")

elif ingreso_mensual > 500:
    print("Eres casi pobre")

elif ingreso_mensual > 200:
    print(" Hermano realmente necesitas un trabajo...")

else
    print("Eres pobre")
