# Amethyst — actualizaciones

Índices y paquetes de actualización de **Amethyst**, ROM basada en LineageOS 23 para el
REDMI Note 15 Pro 4G (`charoite`).

- `charoite/<incremental>.json`: lo que consulta el actualizador del teléfono. Cada versión
  instalada busca el suyo (`ro.build.version.incremental`); contiene la actualización desde
  esa versión a la siguiente, o `[]` si ya es la última.
- Los paquetes OTA están en **Releases**.

Antes de instalar con root: Magisk → Desinstalar → **Restaurar imágenes**. Después de instalar
y antes de reiniciar: Magisk → Instalar → **Instalar en el slot inactivo**.
