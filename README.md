# SmartCart - Lista de Compras Inteligente

Una aplicación web progresiva (PWA) para gestionar tu lista de compras, despensa y presupuesto mensual, todo desde el navegador sin necesidad de instalación.

## Funcionalidades

### Lista de compras
- Añadir productos rápidamente con Enter
- Filtrar por categoría (Lácteos, Proteínas, Frutas, Verduras, Granos, Snacks, Bebidas, Limpieza, Otros)
- Buscar productos por nombre
- Ordenar por nombre, categoría o prioridad
- Fijar productos importantes
- Gestos de deslizamiento para marcar como comprado o eliminar

### Modo compras
- Vista optimizada para usar en el supermercado
- Productos agrupados por categoría
- Barra de progreso con avance de la compra
- Marcar ítems conforme se van tomando del estante

### Despensa
- Seguimiento de consumo y stock en casa
- Predicción de cuándo se agotará cada producto
- Barra visual del nivel de consumo

### Estadísticas
- Gasto total del mes vs. presupuesto
- Barra de presupuesto con indicador de alerta
- Gráfico de gasto por categoría
- Historial de compras anteriores

### Configuración
- Presupuesto mensual con selección de moneda (USD, COP, EUR, MXN)
- Notificaciones push para productos próximos a agotarse
- Modo oscuro (manual o automático según el sistema)
- Exportar e importar datos en JSON

## Tecnología

- HTML + CSS + JavaScript vanilla (sin frameworks)
- PWA con Service Worker para uso sin conexión
- `localStorage` para persistencia de datos local
- Instalable en Android e iOS como app nativa

## Uso

Abre `index.html` en cualquier navegador moderno. No requiere servidor ni dependencias externas.

Para instalarlo como app en móvil, abre la página en Chrome/Safari y selecciona **"Añadir a pantalla de inicio"**.
