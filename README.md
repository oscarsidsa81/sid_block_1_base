# sid_block_1_base

Metamódulo técnico para Odoo que agrupa dependencias base del ecosistema SID.

## Descripción

`sid_block_1_base` no incorpora modelos, vistas ni datos propios.
Su propósito es facilitar instalaciones y despliegues asegurando que un conjunto de módulos fundamentales quede instalado de forma conjunta.

## Información del módulo

- **Nombre técnico:** `sid_block_1_base`
- **Versión:** `15.0.1.0.0`
- **Autor:** SIDSA
- **Licencia:** LGPL-3
- **Instalable:** Sí
- **Aplicación:** No
- **Auto-instalable:** No

## Dependencias (según manifest)

Este metamódulo declara como dependencias los siguientes módulos:

1. `sid_stock_cfg`
2. `sid_product_base`
3. `sid_product_legacy`

Al instalar `sid_block_1_base`, Odoo resolverá e instalará también estos módulos si aún no están presentes.

## Instalación

1. Copiar el módulo en la ruta de addons disponible para Odoo.
2. Actualizar la lista de aplicaciones desde el modo desarrollador.
3. Buscar e instalar **sid_block_1_base**.

## Notas de uso

- Está pensado para centralizar requisitos funcionales/técnicos comunes.
- Es útil como punto de entrada para entornos nuevos donde se quiera garantizar una base homogénea de módulos SID.
