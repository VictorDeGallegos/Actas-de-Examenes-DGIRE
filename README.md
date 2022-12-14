# Sistema de Actas de Examenes 馃摑

![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)

El sistema de actas de examenes es un sistema que permite la consulta y evaluaci贸n de actas de las escuelas incorporadas a la UNAM.

## Tipos de usuarios

- Profesores
- Directivos

## Profesores 馃懆鈥嶐煆笍

Los profesores pueden:

- Iniciar sesi贸n: Los profesores pueden iniciar sesi贸n con su CURP, CLAVE DEL PLANTEL, PLAN Y TIPO DE EXAMEN.
- Consultar resumen de actas: Los profesores pueden consultar el resumen de las actas que tienen.
- Consultar actas: Los profesores pueden concultar las actas de los grupos que tienen asignados a ese plantel.
- Calificar actas: Los profesores pueden calificar las actas de los grupos que tienen asignados a ese plantel.
- Imprimir actas: Los profesores pueden imprimir las actas de los grupos que tienen asignados a ese plantel.

## Directivos 馃憯

Los directivos pueden:

- Iniciar sesi贸n: Los directivos pueden iniciar sesi贸n con su CLAVE DEL PLANTEL, CONTRASE脩A desde otra vista.
- Dar su Vo.Bo.: Los directivos pueden dar su Vo.Bo. a las actas que tienen asignadas.

## MEJORAS 馃敡

- [ ] Agregar un sistema de roles para los usuarios.
- [ ] Manejar una misma ventana para inicio de sesi贸n.
- [ ] Agregar un dise帽o responsivo.
- [ ] Redise帽ar pagina completa.
- [ ] Agregar un boton de cerrar sesi贸n.
- [ ] Poder navegar por los diferentes planteles sin la necesidad de cerrar sesi贸n.
- [ ] Poder Volver a consultar el resumen de actas de Ex谩menes.

## Diagrama de casos de Uso 馃搳

![DiagramaCasosDeUso](https://user-images.githubusercontent.com/41756950/205379533-532cc18b-8846-4914-89d8-0812e5061608.png)

## Wireframes de navegaci贸n 馃弰 馃柤锔?

En esta secci贸n se muestran los posibles wireframes de navegaci贸n de la aplicaci贸n.

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
