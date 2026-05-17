<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/2772/2772128.png" />

# 🗄️ Car Rental Database System

### Base de datos para sistema de renta de automóviles 🚗

<p align="center">
  <b>Car Rental Database System</b> es una base de datos relacional diseñada para administrar procesos de alquiler de vehículos, clientes, reservas, pagos y operaciones administrativas dentro de una plataforma de renta automotriz.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Database-CarRental-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/MySQL-RelationalDB-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/SQL-DataManagement-F29111?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-Academic-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-estructura-de-la-base-de-datos">Estructura</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-modelo-relacional">Modelo Relacional</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Car Rental Database System** es una base de datos diseñada para gestionar toda la información necesaria dentro de un sistema de renta de automóviles.

La estructura permite controlar clientes, vehículos, reservas, contratos, pagos y reportes administrativos mediante relaciones SQL optimizadas y normalizadas.

La base de datos fue diseñada para:

- 🚗 Gestionar vehículos
- 👥 Administrar clientes
- 📅 Controlar reservas
- 💳 Registrar pagos
- 📋 Gestionar contratos
- 📊 Generar reportes
- 🔐 Administrar usuarios
- 🌐 Centralizar información

---

# ✨ Características

## 🚘 Gestión vehicular

- 🚗 Registro de automóviles
- 📍 Control de disponibilidad
- 🛠️ Estado de vehículos
- 💰 Tarifas de alquiler
- 📋 Información detallada

---

## 👥 Gestión de clientes

- 👤 Registro de clientes
- 📄 Información personal
- 📞 Datos de contacto
- 🪪 Licencias de conducir
- 📊 Historial de alquileres

---

## 📅 Gestión de reservas

- 📆 Registro de reservas
- 🚗 Asignación de vehículos
- 📋 Contratos de renta
- ⚡ Confirmaciones rápidas
- 📄 Historial de operaciones

---

## 💳 Gestión financiera

- 💰 Registro de pagos
- 📊 Facturación
- 📋 Historial financiero
- ⚡ Métodos de pago
- 📄 Reportes administrativos

---

# 🏗️ Estructura de la base de datos

## 📂 Tablas principales

### 🚗 Vehicles

Tabla encargada de almacenar la información de los vehículos.

#### Campos principales:

- ID del vehículo
- Marca
- Modelo
- Año
- Placa
- Estado
- Precio por día

---

### 👥 Customers

Tabla encargada de almacenar la información de los clientes.

#### Campos principales:

- ID del cliente
- Nombre completo
- Correo electrónico
- Teléfono
- Dirección
- Licencia de conducir

---

### 📅 Reservations

Tabla encargada de registrar las reservas realizadas.

#### Campos principales:

- ID de reserva
- Cliente asociado
- Vehículo asociado
- Fecha de inicio
- Fecha de devolución
- Estado de reserva

---

### 💳 Payments

Tabla encargada de registrar pagos y facturación.

#### Campos principales:

- ID de pago
- Reserva asociada
- Método de pago
- Total pagado
- Fecha de pago
- Estado financiero

---

### 👨‍💼 Users

Tabla encargada de administrar usuarios del sistema.

#### Campos principales:

- ID de usuario
- Nombre de usuario
- Contraseña
- Rol administrativo
- Estado de acceso

---

# 🛠️ Tecnologías utilizadas

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- SQL Relacional
- Normalización de datos
- Integridad referencial

---

## ⚙️ Gestión y desarrollo

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- SQL Scripts
- MySQL Workbench
- phpMyAdmin
- Visual Studio Code

---



# ⚡ Instalación

## 📋 Requisitos

- MySQL 5.7+
- MySQL Workbench o phpMyAdmin
- Navegador moderno
- Editor SQL

---

# 🚀 Configuración de la base de datos

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/DB-SisRentaAutos.git
```

---

## 2️⃣ Crear base de datos

```sql
CREATE DATABASE car_rental_db;
```

---

## 3️⃣ Seleccionar base de datos

```sql
USE car_rental_db;
```

---

## 4️⃣ Importar scripts SQL

```bash
database/schema.sql
```

---

## 5️⃣ Insertar datos de prueba

```bash
database/inserts.sql
```

---

# 📊 Relaciones principales

## 🔗 Relaciones SQL

- Un cliente puede tener múltiples reservas
- Un vehículo puede pertenecer a múltiples contratos
- Una reserva genera pagos
- Los administradores gestionan operaciones
- Los contratos almacenan historial de rentas

---



# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Diseño de bases de datos relacionales
- Modelado entidad-relación
- SQL avanzado
- Gestión de alquileres
- Integridad referencial
- Automatización mediante triggers
- Administración de sistemas vehiculares

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- ☁️ Integración cloud database
- 📊 Reportes avanzados
- 🔐 Seguridad y cifrado
- 🤖 Automatización inteligente
- 🌐 API REST integrada
- 📱 Compatibilidad móvil
- 📈 Analítica avanzada

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Database Developer

Desarrollador apasionado por bases de datos relacionales, sistemas administrativos y arquitectura SQL moderna 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source orientado al aprendizaje de bases de datos y sistemas de renta automotriz.

---

<div align="center">

### 🗄️ Car Rental Database System — administración inteligente de datos y alquileres 🚗

</div>
