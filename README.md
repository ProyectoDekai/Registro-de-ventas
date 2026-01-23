# Registro-de-ventas

https://proyectodekai.github.io/Registro-de-ventas/
# Sistema de Gestión de Ventas Semanal

Este es un sistema personalizado de registro de ventas diseñado para funcionar de forma rápida en dispositivos móviles, con almacenamiento local y respaldo automático en la nube.

## Características Principales

* **Persistencia Local:** Los datos se guardan en el navegador (`LocalStorage`), permitiendo que el sistema funcione aunque se cierre la pestaña.
* **Sincronización en la Nube:** Conectado mediante Google Apps Script a una hoja de cálculo de Google Sheets para un respaldo permanente.
* **Organización Semanal Inteligente:** Las ventas se agrupan automáticamente en bloques de **Lunes a Sábado**.
* **Resúmenes Automáticos:** Cada bloque semanal muestra el total de dinero recaudado y la cantidad de productos vendidos por tipo.
* **Gestión de Estados:** Control de estados "Pendiente", "Pagado" y "Consumo Propio" con actualización en tiempo real en la nube.

## Guía de Uso Rápido

### 1. Registrar una Venta
1.  Ingresa el nombre del **Cliente**.
2.  Selecciona el **Producto** (el precio se carga automáticamente).
3.  Elige el **Estado** (Pendiente o Pagado).
4.  Marca **Consumo Propio** si el producto no será cobrado ($0).
5.  Presiona **Guardar venta**.

### 2. Control Semanal
* Las ventas se agrupan por semanas. 
* La **semana actual** siempre aparece abierta al principio de la lista.
* Las **semanas anteriores** se muestran contraídas en barras negras para mantener el orden. Toca la barra para ver el detalle.

### 3. Edición y Limpieza
* **Marcar pagado:** Usa este botón en las ventas pendientes cuando recibas el dinero.
* **Borrar venta:** Usa el botón rojo para eliminar registros erróneos. El sistema pedirá confirmación antes de proceder.

## Configuración Técnica
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla).
- **Backend:** Google Apps Script (V8 Engine).
- **Base de Datos:** Google Sheets API.
- **Despliegue:** GitHub Pages.

---
*Desarrollado para optimización de flujo de trabajo diario.*
