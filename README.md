# Sistema de Actas de Examenes 📝

![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)

El sistema de actas de examenes es un sistema que permite la consulta y evaluación de actas de las escuelas incorporadas a la UNAM.

## Tipos de usuarios

- Profesores
- Directivos

## Profesores 👨‍🏫️

Los profesores pueden:

- Iniciar sesión: Los profesores pueden iniciar sesión con su CURP, CLAVE DEL PLANTEL, PLAN Y TIPO DE EXAMEN.
- Consultar resumen de actas: Los profesores pueden consultar el resumen de las actas que tienen.
- Consultar actas: Los profesores pueden concultar las actas de los grupos que tienen asignados a ese plantel.
- Calificar actas: Los profesores pueden calificar las actas de los grupos que tienen asignados a ese plantel.
- Imprimir actas: Los profesores pueden imprimir las actas de los grupos que tienen asignados a ese plantel.

## Directivos 👔

Los directivos pueden:

- Iniciar sesión: Los directivos pueden iniciar sesión con su CLAVE DEL PLANTEL, CONTRASEÑA desde otra vista.
- Dar su Vo.Bo.: Los directivos pueden dar su Vo.Bo. a las actas que tienen asignadas.

## MEJORAS 🔧

- [ ] Agregar un sistema de roles para los usuarios.
- [ ] Manejar una misma ventana para inicio de sesión.
- [ ] Agregar un diseño responsivo.
- [ ] Rediseñar pagina completa.
- [ ] Agregar un boton de cerrar sesión.
- [ ] Poder navegar por los diferentes planteles sin la necesidad de cerrar sesión.
- [ ] Poder Volver a consultar el resumen de actas de Exámenes.

## Diagrama de casos de Uso 📊

![DiagramaCasosDeUso](https://user-images.githubusercontent.com/41756950/205379533-532cc18b-8846-4914-89d8-0812e5061608.png)

## Wireframes de navegación 🏄 🖼️

En esta sección se muestran los posibles wireframes de navegación de la aplicación.

### Login

![ACTAS - LOGIN](https://user-images.githubusercontent.com/41756950/206012798-038b96f1-48b9-4efa-adc0-04ac11c3afcc.png)

### Resumen de actas

![ACTAS - RESUMENES_Profesor](https://user-images.githubusercontent.com/41756950/206012920-80c03094-2939-4cb3-ba47-54c1cffa0e22.png)

### Consultar actas

![ACTAS - ACTAS_PROFESOR](https://user-images.githubusercontent.com/41756950/206013048-d202be68-c896-4cae-ba7b-d2583e21aa84.png)

### Calificar actas/Detalles

![ACTAS - DETALLES ACTAS_PROFESOR](https://user-images.githubusercontent.com/41756950/206013191-8e4f54f5-9d2e-4931-8dd9-1d91392623b0.png)

### Ayuda

![ACTAS - AYUDA _PROFESOR](https://user-images.githubusercontent.com/41756950/206013526-d166c15a-1826-4b7f-8e6d-8a89687f5926.png)
