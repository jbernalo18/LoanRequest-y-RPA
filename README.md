# LoanRequest y bot RPA

Proyecto de entrega del **Bootcamp Bizagi/RPA** (Sophos Solutions, Ruta N y Alcaldía de Medellín, oct 2022 – ene 2023). Fue mi primer acercamiento a proyectos de desarrollo y me abrió la mente para entender cómo funciona todo conectado.

## El problema

Los procesos manuales de solicitud de créditos tenían errores de redacción y costos de mantenimiento altos.

## La solución

El proyecto tiene dos piezas que se complementan:

**1. LoanRequest (Bizagi)**
Modelé el proceso de solicitud de préstamos con BPMN: procesos, reglas y entidades, autenticación de usuarios, conexión a base de datos (SQL Server Express) para guardar los datos, vistas de administrador y una interfaz fácil de navegar. Le ahorra a la empresa costos de mantenimiento y facilita el proceso del banco.

**2. Bot RPA (Automation Anywhere y UiPath)**
Automatiza tareas repetitivas: busca en internet el valor del euro, el dólar y el yen, extrae los campos necesarios de los PDF de solicitud, arma el informe en Excel y lleva la información a la base de datos.

**Resultado:** la eficiencia aumentó un **65 %**, medida comparando el tiempo que tardaba una persona en el proceso con el del bot.

## Estructura del repositorio

| Carpeta | Contenido |
|---|---|
| [`LoanApplication/`](./LoanApplication) | Archivos XML exportados del paquete de Bizagi (proceso LoanApplication) |
| [`RPA/`](./RPA) | Documentación del orquestador `Main` del bot en Automation 360, con el diagrama de su flujo |

## Tecnologías

Bizagi Studio · BPMN · SQL Server Express · Automation Anywhere (Community Edition) · UiPath · Excel · Microsoft Access

## Autora

**Juliana Bernal** · Desarrolladora Full Stack Java
[Portafolio](https://jbernalo18.github.io/Portafolio-Juliana-Bernal/) · [LinkedIn](https://www.linkedin.com/in/juliana-bernal-ortiz-backend/)
