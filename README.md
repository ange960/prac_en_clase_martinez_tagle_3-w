# prac_en_clase_martinez_tagle_3-w

def verificar_numero(): """ Esta función solicita al usuario que ingrese un número entero y determina si el número es par, impar o cero. """

print("Martinez Tagle Luis Angel practica en clase 3-w")


try:
    #solicitar al usuario que ingrese un número
    
    numero = int(input("Por favor, ingresa un número entero: "))
    
    
    #verificar si el número es cero
    
    if numero == 0:
    
        print("El número es cero")
        
        
    #verificar si el número es par
    
    elif numero % 2 == 0:
    
        print("El número es par")
        
        
    #si no es par ni cero, es impar
    
    else:
    
        print("El número es impar")
        
        
except:

    #imprime el texto que esta entre comillas 
    
    print("Por favor, ingresa un número entero válido.")
    
#función para ejecutar el programa verificar_numero()

![image](https://github.com/user-attachments/assets/1bb414b4-683d-4800-bfd1-3bcc80a8b4c0)
