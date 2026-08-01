# node-red-concesionario
# 🚗 Sistema de Gestión de Concesionaria - Node-RED

## 📖 Descripción

Este proyecto consiste en el desarrollo de un sistema para la gestión de una concesionaria de automóviles utilizando **Node-RED** como plataforma principal de automatización y **MySQL** como base de datos.

El sistema permite consultar el inventario de vehículos, registrar clientes y realizar búsquedas mediante una interfaz gráfica desarrollada con Dashboard 2.0.

---

# 🎯 Objetivos

Desarrollar una aplicación que permita administrar una concesionaria utilizando Node-RED conectado a una base de datos MySQL.

---

# 🛠 Tecnologías utilizadas

- Node-RED
- Dashboard 2.0
- MySQL Server
- MySQL Workbench
- GitHub
- Draw.io
- Notion

---

# 📂 Base de datos

Base de datos:

```
concesionario
```

Tablas principales:

- auto
- cliente
- usuario
- promotor
- venta

---

# 📋 Casos de uso implementados

## Caso de uso 1

Consultar inventario de vehículos.

---

## Caso de uso 2

Registrar un cliente nuevo.

---

## Caso de uso 3

Buscar vehículos según distintos criterios.

---

# 🖥 Interfaz gráfica

La interfaz fue desarrollada utilizando Dashboard 2.0 de Node-RED.

Incluye:

- Botón para consultar inventario
- Formulario para registrar clientes
- Menús desplegables para búsqueda
- Tabla para visualizar resultados
- Notificaciones de operaciones exitosas

---

# 🗄 Base de datos

El sistema utiliza una base de datos MySQL denominada:

```
concesionario
```

La información se almacena mediante consultas SQL ejecutadas desde Node-RED.

---

# 📁 Contenido del repositorio

```
README.md
flows.json
BaseDatos.sql
Drawio/
Capturas/
Documentacion/
```

---

# ▶ Cómo ejecutar el proyecto

1. Instalar Node-RED.
2. Instalar MySQL Server.
3. Crear la base de datos **concesionario**.
4. Importar las tablas SQL.
5. Importar el archivo **flows.json** en Node-RED.
6. Configurar la conexión MySQL.
7. Presionar Deploy.
8. Abrir el Dashboard desde:

```
http://localhost:1880/dashboard
```

---

# 📊 Arquitectura

Usuario

↓

Dashboard Node-RED

↓

Funciones JavaScript

↓

Nodo MySQL

↓

Base de datos Concesionario

---

# 📌 Requerimientos funcionales

- Consultar inventario.
- Registrar clientes.
- Buscar vehículos.
- Mostrar resultados.
- Conectarse con MySQL.

---

# 📌 Requerimientos no funcionales

- Interfaz amigable.
- Fácil utilización.
- Tiempo de respuesta bajo.
- Integridad de los datos.
- Disponibilidad del sistema.

---

# 📚 Documentación

La documentación del proyecto incluye:

- Casos de uso (Draw.io)
- Requerimientos funcionales
- Requerimientos no funcionales
- Proceso Unificado de Desarrollo
- Manual de uso
- Diagrama del sistema

---

# 👨‍💻 Autor

Pablo Rivero

Proyecto académico desarrollado para la materia Taller de Desarrollo.
