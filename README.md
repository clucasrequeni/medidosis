# Medidosis

Herramienta web para consultar la compatibilidad de fármacos intravenosos administrados en Y (por la misma luz del catéter).

- **Consulta rápida**: añada todos los fármacos del paciente (sin límite), con diluyente y concentración opcionales. La app calcula cuántas luces hacen falta y qué fármacos pueden ir juntos por cada una. Puede añadir constantes del paciente para recibir avisos.
- **Fármacos**: ficha de cada fármaco con diluyentes, velocidad de infusión, estabilidad y compatibilidades en Y.

- **Tabla compatibilidad** (enlace al pie): matriz de colores de 44 fármacos de UCI con leyenda, concentraciones máximas compatibles (tabla 2) y concentraciones estándar de referencia (tabla 1).

Toda la app está en `index.html`. No usa servidor ni guarda datos: lo que se escribe desaparece al cerrar la página.

## Fuentes

- Castells Lao G et al. Compatibilidad de los fármacos administrados en «Y» en las unidades de cuidados intensivos: revisión sistemática. *Med Intensiva.* 2020;44(2):80-87.
- Espinosa Franco B et al. Guía de compatibilidades de fármacos en vía parenteral para un hospital de segundo nivel. UNAM FES Zaragoza, 2010.
- Marsilio NR et al. Incompatibilidades medicamentosas en una UCI de adultos de un hospital universitario (clasificación Micromedex). *Rev Bras Ter Intensiva.* 2016;28(2):147-53.

- Vasopresina (argipresina)*, añadida fuera de la tabla original: ficha técnica de Empressin (CIMA, AEMPS); IUCPQ, *Guide d'administration intraveineuse des médicaments critiques*, 16.ª ed., 2025; ANMF Consensus Group, Argipressin v2.0, 2021 (Micromedex y Australian Injectable Drugs Handbook); Trissel 25.ª ed.; Ramaley et al. *Int J Pharm Compd.* 2014.

## Aviso

Herramienta de apoyo. No sustituye el juicio clínico ni la consulta con Farmacia. Una combinación sin datos no significa que sea compatible.
