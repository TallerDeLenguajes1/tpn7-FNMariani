# Trabajo Practico N°7
## Ejercicio 2:
### ¿Qué es la propiedad TabIndex? ¿Para qué se utiliza?
La propiedad Tablndex indica el orden Tab (0, 1, 2, etc.) de un
control (label, textbutton, button, etc.). Este valor determina el orden en el que los controles
reciben el foco cuando el usuario navega por ellos utilizando la tecla
Tab. Un control con un indice de tabulación más bajo recibe el foco
antes que un control con un indice más alto. Por omisión, los
controles reciben el foco en el orden en el orden que se añadieron al
contenedor.
    
### ¿Cómo funciona el foco en un control en particular?
Cuando un control tiene el foco, está enfocado, es
cuando puede recibir las acciones del teclado.
Por ejemplo se puede "presionar", como si se hubiese hecho "clic" en el botón, al apretar la tecla Enter.

### ¿Qué son los eventos? ¿Cómo se utilizan los eventos del teclado?

Un controlador de eventos es un método que está enlazado a un evento. Cuando se genera el evento, se ejecuta el código dentro del controlador de eventos. 
En el ejemplo siguiente se muestra un controlador de eventos para el evento "Click" de un "Button".


```csharp
private void button1_Click(object sender, System.EventArgs e)
{  
  
}
```
**Eventos de teclado:**
Windows Forms proporciona dos eventos que se producen cuando el usuario presiona una tecla del teclado y un evento cuando el usuario suelta una tecla del teclado:

- El evento KeyDown, que se produce una vez.
- El evento KeyPress, que se puede producir varias veces cuando un usuario mantiene presionada la misma tecla.
- El evento KeyUp, que se produce una vez cuando el usuario suelta una tecla.