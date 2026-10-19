# ud01_proyect_alvaro_mora_cabrera
## Exercise:
### Write a program that converts euros to USD.
```"""EUR/USD converter
AUTHOR: Álvaro Mora Cabrera
DATE: 2026-10-5
Version: 1.0
"""


moneda = input("Inserte una moneda para realizar la conversion (1: Dólar E.E.U.U., 2: Euro): ")

""" I put an input variable for asking to the user the currency he wants to convert. 1 equals to dollars and 2 equals to euros  """

conversion1 = 0.89
conversion2 = 1.13

""" I declare two constants with the conversion factors of each currency    """

if moneda == "1":
    dolar = int(input("Inserte la cantidad que desee: "))
    print (f"{dolar} dolares son {dolar * conversion1} euros")
elif moneda == "2":
    euro = int(input("Inserte la cantidad que desee: "))
    print (f"{euro} euros son {euro * conversion2} dolares")
else:
    print ("Por favor, seleccione 1 o 2")

""" I put a condition here where it says to select 1 or 2. If the variable "moneda" equals 1, then it will convert dollars to euros
    If the variable equals to 2, it converts euros to dollars
    And if the variable isn't 1 or 2, it finishes the code
"""

hola