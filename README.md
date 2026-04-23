# 🎖️ Gestor de Batallón - Sistema de Administración Vehicular

Sistema desarrollado en **Java** diseñado para centralizar y automatizar el control de vehículos y misiones dentro de un batallón militar. El proyecto implementa conceptos avanzados de **Programación Orientada a Objetos (POO)** y garantiza la integridad de los datos mediante pruebas unitarias.

## 🚀 Características Principales

El sistema permite gestionar diferentes tipos de unidades con atributos específicos:
* **Gestión de Vehículos:** Registro, edición, eliminación y consulta de:
    * 🚚 *Transporte de Tropas* (Capacidad de soldados).
    * 🛡️ *Vehículos Blindados* (Nivel de blindaje).
    * 🚑 *Vehículos de Apoyo* (Funciones logísticas, médicas o de comunicación).
* **Control Operativo:** Actualización de kilometraje, estados operativos (Disponible, En Misión, Mantenimiento) y contador de misiones.
* **Misiones:** Registro detallado de misiones, ubicación y personal asignado.
* **Filtros Inteligentes:** Reporte automático de vehículos con alta operatividad (más de 50 misiones).

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Java 17+
* **Interfaz de Usuario:** Swing (`JOptionPane`) para interacción por ventanas.
* **Arquitectura:** POO (Encapsulamiento, Herencia y Polimorfismo).
* **Testing:** JUnit 5 para pruebas unitarias de la lógica de negocio.

## 🧪 Pruebas Unitarias

Para asegurar la fiabilidad del sistema, se implementaron pruebas sobre cada clase del modelo (`Batallon`, `Vehiculo`, `Mision`). Se validaron casos como:
- Registro exitoso de vehículos.
- Lógica de edición y actualización de estados.
- Correcto funcionamiento de los contadores de misiones.
- Validación de IDs únicos.

## 📋 Requisitos e Instalación

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/nombre-repo.git](https://github.com/tu-usuario/nombre-repo.git)
