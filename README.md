<!-- SECCIÓN SUPERIOR: BANNERS SVG (TÍTULO Y LLUVIA LARGA) -->
<p align="center">
  <img src="./jack-villa.svg" alt="Jaqui Villa" width="100%">
</p>
<p align="center">
  <img src="./matrix-rain.svg" alt="Matrix Rain" width="100%">
</p>

<!-- SECCIÓN MEDIA: TABLA DE DOS COLUMNAS (CÓDIGO VS GATITOS) -->
<!-- Usamos una tabla para forzar el diseño de dos columnas. align="center" centra la tabla entera. -->
<table align="center" style="border-collapse: collapse; border: none; width: 100%;">
  <tr style="border: none;">
    
    <!-- COLUMNA IZQUIERDA: EL CÓDIGO C -->
    <td width="55%" valign="top" style="border: none; padding-right: 20px;">
    
    <h3 style="color: #ff2a85; font-family: monospace;">// Struct de Presentación</h3>
    
```c
#include <stdio.h>

typedef struct {
    char* nombre;
    char* carrera;
    char* universidad;
    char* estado;
} Dev;

int main() {
    Dev me = {
        .nombre = "Jacqueline Villa",
        .carrera = "Licenciatura en Ciencias de la Computación",
        .universidad = "UNSL",
        .estado = "Cargando nuevos proyectos..."
    };

    printf("==========================================\n");
    printf(" USER: %s\n", me.nombre);
    printf(" DEGREE: %s @ %s\n", me.carrera, me.universidad);
    printf(" STATUS: %s\n", me.estado);
    printf("==========================================\n");

    return 0;
}
```

<!-- COLUMNA DERECHA: LOS GATITOS BAILARINES (ACHICADOS) -->
<td width="45%" valign="middle" align="center" style="border: none; padding-left: 20px;">
  
  <h3 style="color: #ff2a85; font-family: monospace;">// El Toque Importante</h3>
  
  <!-- Ajustamos el ancho al 100% de ESTA COLUMNA, eliminando el height="400" fijo para que no se deforme -->
  <img src="https://github.com/user-attachments/assets/15cce71b-d01b-4364-985a-b7759ca25369" 
       alt="Gatitos Bailarines Achicados" 
       width="100%" 
       style="border-radius: 12px; border: 1px solid #30363d; object-fit: contain; max-width: 350px;" />
</td>
