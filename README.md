# Caso de Estudio 2 — Sistema de Puntos MyMcDonald's Rewards
**Machine Learning Engineering (CC3105)**

Diagnóstico y propuesta de optimización de la arquitectura de datos del sistema de recompensas
de McDonald's, realizado por un equipo de consultoría externo.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `diagrama_arquitectura.html` | Diagrama de arquitectura de datos del sistema (Mermaid), capas Bronze/Silver/Gold. |
| `Propuesta_ML_LLM_Caso_2.pdf` | Propuesta de integración de modelos de ML, AI y LLM en el pipeline de datos. |
| `notebook/poc_sistema_puntos.ipynb` | Notebook con la réplica en miniatura del pipeline (extracción, limpieza, filtrado, agregación). |

## Cómo ejecutar el notebook

```bash
pip install pandas numpy matplotlib jupyter
jupyter notebook notebook/poc_sistema_puntos.ipynb
```

## Resumen

MyMcDonald's Rewards otorga 100 puntos por cada $1 gastado en canales elegibles (excluye
delivery de terceros), con bono de bienvenida y niveles de canje crecientes. El diagnóstico
identifica la arquitectura de datos necesaria para sostener esta mecánica a escala (cientos de
millones de usuarios activos) y propone puntos de integración de ML/AI/LLM sobre la capa curada
del pipeline.

## Equipo
Equipo consultor de datos — Caso de Estudio 2, CC3105.
