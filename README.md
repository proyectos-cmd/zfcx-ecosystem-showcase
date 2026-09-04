# Ind. O&C · Ecosistema Estocástico

Vitrina pública de demostración del ecosistema de **Ind. O&C Ingeniería**.
Muestra, en vivo, cómo un único motor estocástico potencia presupuesto (Budget 360),
inspecciones de campo (Dossier 360), modelo 3D/CAD (Viewer 360) y gestión de datos.

> **Aviso de seguridad:** este repositorio es **solo la vitrina (presentación)**.
> Consume únicamente endpoints públicos de métricas anónimas. No contiene código
> del motor, credenciales, datos de clientes ni acceso a bases de datos.

## Cómo funciona

La página consume dos endpoints públicos (solo lectura, métricas agregadas):

- `GET /api/public/showcase/overview` — métricas anónimas del ecosistema
- `GET /api/public/benchmark/modules` — scores del benchmark por módulo

Los datos se muestran agregados y anonimizados: **nunca** se exponen nombres de
clientes, obras, usuarios, credenciales ni ninguna fila de base de datos.

## Despliegue

Publicada como GitHub Pages (rama `main`, carpeta raíz).

## Repositorios relacionados

- `zfcx2engine` — **privado**. Motor estocástico (no se incluye aquí por seguridad).
