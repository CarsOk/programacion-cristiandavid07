## Clase 8 noviembre 2021

### Ciclo While

la sentencia while (condición o expresión) instrucciones; es seguramente la más utilizada. La sentencia, o grupo de sentencias o instrucciones se ejecutan mientras la evaluación de la expresión sea verdadera.

Ejemplo 

Sub prueba_ciclo()

    opcion = "S"
    While opcion = "S"

        a = Int(InputBox("Numero a sumar"))
        b = Int(InputBox("Segundo numero a sumar"))

        suma = a + b 
        MsgBox ("La suma es " & suma)

        option = InputBox("¿Quiere continuar S/N?")

    Wend

End Sub