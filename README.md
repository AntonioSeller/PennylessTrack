# PennylessTrack

## 1. Título del proyecto

PennylessTrack

## 2. Descripción del proyecto

Aplicación orientada al seguimiento y control de finanzas personales, desarrollada bajo un flujo de trabajo seguro, control de versiones con Git y trazabilidad criptográfica.

## 3. Tecnologías utilizadas

- Java / Spring Boot
- Maven
- Git & GitHub (control de versiones con firma GPG)
- JUnit (pruebas unitarias)

## 4. Instrucciones para instalar y ejecutar el proyecto

```bash
# Clonar el repositorio en tu entorno local
git clone https://github.com/AntonioSeller/PennylessTrack.git
cd PennylessTrack

# Compilar y arrancar la aplicación
mvn spring-boot:run
```

## 5. Instrucciones para ejecutar los tests

```bash
# Ejecutar la suite de pruebas unitarias del sistema
mvn test
```

## 6. Instrucciones para contribuir al proyecto

- Está prohibido realizar cambios directamente en la rama `main`.
- Crea una rama dedicada para cada tarea (ej. `feature/nombre-tarea`).
- Firma obligatoriamente todos tus commits con tu clave GPG (`git commit -S`).
- Abre una Pull Request hacia `main` para su revisión.

## 7. Licencia del proyecto

Este proyecto se distribuye bajo los términos de la licencia MIT.