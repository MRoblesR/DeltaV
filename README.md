# DeltaV

# Tecnología usada

En esta web se utiliza la siguientes tecnologías
- HTML, CSS, JS
- Bootstrap
- Hugo
- Netlify
- Git

# Cómo crear nuevas páginas

## Nuevos miembros del equipo

1. Accedes a la carpeta deltav/content/nosotros
2. Creas una carpeta con un nombre identificativo **sin espacios**
3. Dentro creas un archivo llamado index.md
4. Rellenas los siguientes campos de la siguiente manera respetando los espacios y las comillas:
  ```
  ---
Title: "marcos"
nombre: "Marcos Robles"
foto: "foto.jpeg"
descripcion: "Soy el ingeniero de software que hizo la página"
puesto: "desarrollador"
linkedin: "https://www.linkedin.com/in/marcos-robles-rodr%C3%ADguez-b867031b7"
---
  ```
  5. Compruebas que el title se corresponde con el nombre de la carpeta y que está en minúscula el título
  6. Actualmente se aceptan los siguientes campos
  - linkedin
  - whatsapp
  - instagram
  7. Pones la foto en la misma carpeta y la pones en el campo foto
  
  
## Nueva entrada de proyecto
1. Accedes a la carpeta de content que corresponda
2. Creas una carpeta con un nombre identificativo
3. Creas un archivo dentro de esa carpeta llamado index.md
4. Se aceptan los siguientes campos
```
---
title: "primero"
description: "Este es el primer texto"
date: 2021-08-07
cover: "1.png"
---
```
5. Se rellena con el texto después de los 3 guiones con HTML o markdown
6. Para poner fotos a la izquiera usas {{% leftImage NOMBREDELAIMAGEN %}}{{ /leftImage %}}
7. Para poner fotos a la derecha igual pero con right
8. Vas a config.toml y añades una nueva entrada con el resto así, cambias todo lo que sea proyecto1 por lo que sea
```
[[menu.main]]
            name = "Proyecto 1"
            identifier = "proyecto 1"
            url = "/proyectos/proyecto1/index.html"
            weight = 1
            parent = "proyectos"
```
## Nueva revista

Sigue los siguientes pasos:
1. En revistas crea una carpeta con la posición de la revista de nombre
2. Crea un archivo index.md con

```
---
title: "primera"
date: 2021-08-07
cover: "images/1.png
description: "Una descripcion de cualquier longitud"
ossuu: "link a la web de ossuu"
---
```
4. Crea una carpeta dentro de la anterior llamada images
5. Pon todas las imagenes en la carpeta images
6. Te aseguras de que la fecha está bien

# Consideraciones

1. Todas las imagenes deberían estar en formato webP

