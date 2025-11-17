# Proyecto_github_EDD
# <img src="img/logopokeball.png" width="35" style="vertical-align: middle;"> Tienda Pokémon – Proyecto Web


Este proyecto consiste en una página web temática inspirada en el mundo Pokémon. Incluye tres páginas principales:

- **index.html** → Inicio y catálogo de Pokémon.
- **servicios.html** → Listado de servicios para entrenadores.
- **contacto.html** → Formulario de contacto dentro de una caja estilizada.
- **css/estilos.css** → Estilos generales y específicos de cada sección.
- **img/** → Todas las imágenes usadas en el sitio.

El desarrollo del proyecto sigue el ciclo de vida del software que se detalla a continuación.

---

# 📌 1. Planificación

### ✔ Elección de la temática
Elegimos crear una **Tienda Pokémon**, porque permite trabajar con elementos visuales, tarjetas, formularios, botones animados y fondos temáticos. Además, facilita pensar en servicios, usuarios y contenido que tenga sentido dentro del universo Pokémon.

### ✔ Usuarios definidos
Para el proyecto definimos **dos tipos de usuarios**:

1. **Entrenador Pokémon**
   - Quiere ver Pokémon disponibles.
   - Busca servicios como torneos, curación o entrenamiento.
   - Puede necesitar contactar con la tienda.

2. **Administrador / Personal de la Tienda**
   - Se encarga de ofrecer servicios.
   - Mantiene actualizado el catálogo y atiende mensajes del formulario.
   - Gestiona eventos y torneos.

### ✔ Requisitos funcionales

1. El sistema debe mostrar Pokémon y su tipo en tarjetas visuales.
2. El usuario debe poder navegar entre Inicio, Servicios y Contacto mediante un header fijo.
3. Debe existir un formulario en la página de Contacto para que los usuarios puedan enviar mensajes.
4. La página de Servicios debe incluir un botón que lleve a una web oficial de eventos Pokémon.

---

# 📌 2. Diseño

### ✔ Arquitectura Cliente–Servidor
Nuestra web utiliza una arquitectura **cliente-servidor**, que se puede explicar así:

- **Cliente (Front-end)**:  
  Es el navegador del usuario. Se encarga de mostrar el contenido: HTML, CSS y las imágenes en `/img`.  
  Todo lo que el usuario ve y con lo que interactúa ocurre en el lado del cliente.

- **Servidor (Back-end o Hosting)**:  
  En este caso usamos **GitHub Pages**, que actúa como servidor estático.  
  El servidor guarda los archivos y los entrega cuando el cliente los solicita mediante un enlace.

Esta arquitectura es muy común en sitios web estáticos como este.

---

# 📌 3. Despliegue

### ✔ Experiencia usando GitHub Pages
El proyecto se desplegó usando **GitHub Pages** y un flujo de trabajo colaborativo:

Cada una creó una **rama con su nombre**:
- `rama_Ari`
- `rama_Miranda`

Subíamos los cambios primero a nuestra rama personal, y después hacíamos **merge** a `main` cuando confirmábamos que funcionaba correctamente.

Este método permitió:

- Evitar sobrescribir cambios de la otra persona.
- Mantener `main` siempre estable.
- Practicar un flujo de trabajo real de control de versiones.

GitHub Pages usa automáticamente el archivo `index.html` como página principal.  
Cada merge actualizado se publicaba instantáneamente.

---

# 📌 4. Mantenimiento

### ✔ Errores encontrados
Durante el desarrollo aparecieron varios problemas que fueron corregidos:

- El **header fijo** tapaba el contenido de Contacto y Servicios.
- Las imágenes de las cartas en “Inicio” no eran del mismo tamaño.
- Algunas imágenes no cargaban por problemas de rutas.
- El formulario de Contacto no tenía estructura visual clara.
- Diferentes secciones compartían estilos y provocaban cambios no deseados.
- Los commits no se actualizaban correctamente. A veces, los cambios hechos por una no aparecían al hacer pull, lo que causaba conflictos y archivos desactualizados. 

### ✔ Mejoras futuras

1. Añadir un sistema real de envío de formulario (por ejemplo usando PHP o un backend).
2. Implementar más categorías de Pokémon con filtros por tipo.
3. Añadir animaciones más avanzadas con JavaScript.
4. Crear una página para registrar usuarios (entrenadores).
5. Añadir un carrito de compra y productos reales de la tienda.

---

# ✔ Tecnologías usadas
- **HTML5**
- **CSS3**
- **Git y GitHub (Repositorio + GitHub Pages)**

---

# ✨ Autores
Este proyecto ha sido realizado por:

- **Miranda Martinez**
- **Ariadna Corbaes**

