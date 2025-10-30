# Miniproyecto 4 - Sistemas de Interacción

## Juan David Vasquez Pomar
## Santiago Guevara Idarraga
> LINK: **https://youtu.be/2jnrOZIVCXU**

## P1 - Control de efectos (Sliders, Switches, Botones)
Funcionalidades de control de audio en la primera página:

### 4 Sliders:
- **Velocidad metronomo**: Ajusta la velocidad del metronomo.
- **Velocidad metronomo 2**: Controla la velocidad del otro metronomo.
- **Volumen**: Ajusta el volumen del los sonidos de los botones.
- **Velocidad switches**: Cambia la velocidad de reproducción de la base rítmica en la página 3.

### 3 Switches (ON/OFF):
- **activa metronomo 1**: Habilita el metrónomo para mantener el ritmo.
- **Activar Metrónomo 2**: Habilita el metrónomo dos para mantener el ritmo.
- **Sonido Prueba**: permite sonido.

### 3 Botones:
- **kick**: 
- **beat**: 
- **Sonido**: 

---

## P2 - Modulación Avanzada (Frecuencia y Amplitud)
Página de modulación avanzada mediante los ejes de frecuencia y amplitud.

### 2 Ejes de Control:
- **Eje Y (Frecuencia)**: Ajusta la frecuencia del sonido para cambiar el tono.
- **Eje X (Amplitud)**: Modifica la amplitud del sonido para variar el volumen percibido.

---

## P3 - Gestión de Base (Switches Rítmicos)
Controles de base rítmica que permiten crear patrones de percusión en un compás.

### 24 Switches organizados en 4 columnas (6 instrumentos de percusión por columna):
  
**Función**: Al activar un switch, se programa el instrumento seleccionado para que se reproduzca en el tiempo asignado, permitiendo crear bases rítmicas con variaciones y repeticiones hasta que el usuario lo desee.

---

## P4 - Gestión de Sonidos (Botones de Piano y Efectos de Sonido)
Página dedicada a la reproducción de sonidos específicos por instrumento.


**Función**: Al presionar un botón, se reproduce el sonido asignado, permitiendo explorar diversos timbres y efectos.

---

## Descripción del Proyecto
Usando la app **OSC Controller** (Open Sound Control) y el lenguaje **Pure Data (PD)**, se debe implementar un sistema de DJ. La idea es utilizar todos los widgets disponibles en la app (sliders y botones), asegurando que cada interacción tenga una respuesta auditiva en PD. El objetivo es permitir la creación de piezas de música electrónica al estilo de un DJ.

### Limitantes:
- Debe utilizarse **OSC** y **Pure Data**.  
- Se deben emplear diferentes interacciones ofrecidas por OSC (sliders, botones, etc.).  
- Todas las interacciones deben afectar el audio en PD.  
- Se debe subir un **video a YouTube** de no más de 5 minutos donde se muestre el funcionamiento del sistema (demo con una canción).

