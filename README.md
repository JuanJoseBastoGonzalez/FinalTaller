# 🚀 Taller de Programación Orientada a Objetos (POO)

## 📝 Descripción del Proyecto

Este proyecto es una solución desarrollada como parte de un **taller práctico** para la materia de **Programación Orientada a Objetos (POO)**. El objetivo principal es demostrar los conceptos fundamentales de POO, como **encapsulamiento**, **herencia**, **polimorfismo** y **abstracción**, mediante la implementación de un sistema de gestión básico. 

El proyecto está construido con **Java**, un lenguaje ampliamente utilizado en la enseñanza de POO por su claridad y robustez. Está dirigido a **estudiantes** y **desarrolladores** que deseen reforzar sus conocimientos en programación orientada a objetos y aplicar estos conceptos en un proyecto real.

---

## 📌 Tabla de Contenidos

- [Instalación](#-instalación)
- [Uso](#-uso)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Contribución](#-contribución)
- [Licencia](#-licencia)
- [Contacto](#-contacto)

---

## 🛠️ Instalación

Sigue estos pasos para instalar y configurar el proyecto en tu entorno local.

### Requisitos previos

Asegúrate de tener instaladas las siguientes herramientas:

- [Java JDK 11 o superior](https://www.oracle.com/java/technologies/javase-downloads.html)
- [Git](https://git-scm.com/)
- Un IDE como [IntelliJ IDEA](https://www.jetbrains.com/idea/) o [Eclipse](https://www.eclipse.org/)

### Pasos de instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu-usuario/taller-poo.git

1. Navega al directorio del proyecto:

   bash

   Copy

   ```
   cd taller-poo
   ```

2. Abre el proyecto en tu IDE favorito.

3. Compila y ejecuta el proyecto desde el IDE o usando la terminal:

   bash

   Copy

   ```bash
   javac src/main/Main.java
   java src/main/Main
   ```

------

## 🚦 Uso

Este proyecto es un sistema de gestión básico que permite realizar  operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre una lista de  entidades (por ejemplo, estudiantes, productos, etc.). Aquí te  explicamos cómo usarlo:

### Ejecución del proyecto

1. Compila y ejecuta la clase `Main`:

   bash

   Copy

   ```bash
   javac src/main/Main.java
   java src/main/Main
   ```

2. Sigue las instrucciones en la consola para interactuar con el sistema.

### Ejemplo de uso

java

Copy

```bash
// Crear un nuevo objeto
Estudiante estudiante = new Estudiante("Juan", "Pérez", 20);

// Mostrar información del estudiante
System.out.println(estudiante.getNombreCompleto());
```

------

## 🗂️ Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

Copy

```
taller-poo/
├── src/
│   ├── main/
│   │   ├── Main.java          # Punto de entrada del programa
│   ├── models/
│   │   ├── Estudiante.java    # Clase que representa a un estudiante
│   │   ├── Profesor.java      # Clase que representa a un profesor
│   ├── services/
│   │   ├── GestorEstudiantes.java # Lógica de negocio para gestionar estudiantes
├── README.md                  # Este archivo
```

------

## 🤝 Contribución

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto, sigue estos pasos:

1. Haz un fork del repositorio.

2. Crea una rama para tu contribución:

   bash

   Copy

   ```bash
   git checkout -b mi-contribucion
   ```

3. Realiza tus cambios y haz commit:

   bash

   Copy

   ```bash
   git commit -m "Añade nueva funcionalidad"
   ```

4. Sube tus cambios a GitHub:

   bash

   Copy

   ```
   git push origin mi-contribucion
   ```

5. Abre un Pull Request y describe tus cambios.

------

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](https://chat.deepseek.com/a/chat/s/LICENSE). Esto significa que puedes usarlo, modificarlo y distribuirlo  libremente, siempre y cuando incluyas la atribución correspondiente.

------

## 📧 Contacto

Si tienes preguntas, sugerencias o simplemente quieres ponerte en contacto, no dudes en escribirme:

- **Nombre**: Juan Jose Basto Gonzalez
- **Email**: [jjosebasto@tus.edo.co](jjosebasto@tus.edo.co)
- **GitHub**: [@JuanJoseBastoGonzalez](https://github.com/JuanJoseBastoGonzalez)
- **LinkedIn**: [Juan Jose Basto Gonzalez](https://www.linkedin.com/in/juan-jose-basto-gonzalez-49945023a/) 
