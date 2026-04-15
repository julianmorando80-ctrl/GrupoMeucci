# Proyecto: Dashboard Comercial Automotor — Grupo Meucci

## Contexto
Herramienta de Business Intelligence comercial desarrollada como propuesta de valor 
para el puesto de Gerente Comercial en Grupo Meucci (sector automotor).
Será presentada en entrevista laboral. El objetivo es demostrar capacidad analítica, 
visión estratégica y liderazgo basado en datos.

## Objetivo del proyecto
Dashboard HTML single-file index.html, sin dependencias externas (salvo CDN), que 
permita al Gerente Comercial tomar decisiones informadas por segmento de negocio.

## Navegación
1. Pantalla de inicio → dos cards grandes: AUTOS y MOTOS
2. Al seleccionar categoría → cards de concesionarias con su logo
3. Al seleccionar concesionaria → dashboard con KPIs de esa marca

## Estructura del negocio

### AUTOS
- **Meucci Automotores** → marcas: Jeep, RAM, Fiat, KIA, DFSK, Shineray, JMC
- **Dallas** → marcas: Jeep, RAM
- **Scuderia** → marcas: Fiat
- **KIA Del Norte** → (marca propia)
- **Alliance** → (marca propia)

### MOTOS
- **Meucci Motos** → marcas: Benelli, Motomel, Suzuki, Royal Enfield
- **Royal Enfield Nordeste** → (marca propia)
- **Benelli Nordeste** → (marca propia)
- **Keeway** → (marca propia)
- **Morbidelli** → (marca propia)

## Archivos de logos (todos .png en carpeta /Logos/)

### Concesionarias
- logo-meucci.png
- logo-alliance.png
- meucci-automotores.png
- meucci-motos.png
- dallas.png
- scuderia.png
- kia-del-norte-azul.png
- keeway.png
- morbidelli.png
- royal-enfield.png
- benellis.png

### Fabricantes
- jeep.png, ram.png, fiat.png, dfsk.png, jmc.png, shneray.png
- motomel.png, suzuki.png

## KPIs por concesionaria
- Unidades vendidas (mes actual vs mes anterior vs objetivo)
- Rentabilidad por modelo (bruta y neta)
- Mix de modelos vendidos (gráfico torta)
- Ranking de vendedores
- Tasa de conversión leads → ventas
- Financiación: % contado vs crédito vs plan de ahorro

## Stack técnico
- HTML + CSS + JavaScript vanilla — un solo archivo index.html
- Chart.js via CDN para gráficos
- Datos simulados realistas del mercado automotor argentino
- Diseño oscuro, ejecutivo, apto para presentación ante directivos

## Audiencia
Gerencia comercial, directores. Presentación en entrevista laboral mañana.
Tono: ejecutivo, limpio, orientado a decisión rápida.

## Restricciones
- Sin backend, sin base de datos
- Todo funciona offline (CDN permitido)
- Un solo archivo HTML deployable
