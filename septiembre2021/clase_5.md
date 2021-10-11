# Clase Septiembre 30 del 2021

## Ciclos 

###  For

En la clase de este día se trató el tema de ciclos. El bucle _For_, el cual nos permite indicar un número de iteraciones en nuestro código. Esto hace que los programadores tengan un mejor código y sea menos complicado repetir la misma instrucción una gran cantidad de veces. 


#### Ejemplo

```
Sub prueba()
    For i = 1 to 10
        MsgBox = "Sena" & i
    Next i
End Sub
```

## Práctica Individual

Crear programa que calcule 20 números en dos columnas de una hoja de excel y de resultado en la tercera. 

```
Sub sumas()
    For i = 2 To 21
    
    Hoja1.Cells(i, 3) = Hoja1.Cells(i, 1) + Hoja1.Cells(i, 2)
    
    Next i

End Sub
```