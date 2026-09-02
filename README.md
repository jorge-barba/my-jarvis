# My Jarvis

Panel personal en un solo archivo HTML (sin build, sin backend). Todo se guarda en `localStorage` del navegador.

## Módulos

- **Finanzas** — ingresos, gastos, presupuestos por categoría, resumen mensual y agregar movimientos por voz.
- **Pendientes** — lista de tareas diarias con resumen semanal.
- Ejercicio, Salud, Calendario — en construcción.

## Uso

Abre `index.html` directamente en el navegador, o publícalo con GitHub Pages para tener una URL fija (necesaria para que el reconocimiento de voz funcione, ya que requiere permiso de micrófono que los navegadores no conceden a `file://` de forma consistente ni a iframes de vista previa).

## Respaldo de datos

Los datos viven solo en el navegador donde abras la página. Usa los botones **Exportar JSON** / **Importar JSON** (dentro de Configuración → Datos) para respaldar o mover tu información entre dispositivos o navegadores.
