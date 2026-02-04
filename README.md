# Planilla HTML para Evaluación Económica de Voluminosos en Vacas Lecheras

https://josefernandoguarin.github.io/AlimentacionForrajera/

## Descripción general

Esta aplicación es una **planilla interactiva en HTML y JavaScript** diseñada para evaluar el **costo–beneficio de diferentes voluminosos** utilizados en la alimentación de vacas lecheras.

El modelo permite comparar alternativas forrajeras bajo una **vaca estandarizada**, estimando:

- Costo diario de la dieta  
- Costo por litro de leche producido  
- Eficiencia de uso del suelo (vacas sostenidas por hectárea)  

La herramienta está orientada a **docencia, extensión rural y planeación forrajera**, y no pretende sustituir programas de formulación nutricional.

---

## Objetivo del modelo

Responder de forma explícita y transparente a la pregunta:

> **¿Cuál voluminoso ofrece el mejor equilibrio entre costo económico, aporte de materia seca y eficiencia por hectárea, manteniendo constante la producción de leche?**

---

## Supuestos principales

- Vaca estándar:
  - Producción fija de leche (L/día)
  - Consumo objetivo de materia seca (kg MS/día)
- La producción de leche **no varía entre dietas**
- La ración concentrada:
  - Tiene 100% de MS
  - Precio constante
- No se consideran explícitamente:
  - Digestibilidad
  - FDN efectiva
  - Límite físico de consumo
  - Efectos metabólicos o reproductivos

Estos supuestos hacen del modelo una **herramienta de análisis económico preliminar**, no un modelo fisiológico.

---

## Parámetros de entrada

### Parámetros generales (editables por el usuario)

- Producción de leche (L/día)
- Consumo objetivo de MS (kg/día)
- Precio de la ración ($/kg)

### Parámetros por voluminoso

- Cantidad ofrecida (kg fresco/día)
- Porcentaje de materia seca (% MS)
- Precio por kg fresco
- Productividad forrajera (kg fresco/ha/año)

Se incluyen **valores sugeridos** para forrajes tropicales comunes, que pueden ser modificados libremente.

---

## Cálculos realizados

### Nivel animal (diario)

1. Materia seca aportada por el voluminoso  
2. Materia seca faltante para alcanzar el consumo objetivo  
3. Cantidad de ración requerida  
4. Costo del voluminoso  
5. Costo de la ración  
6. Costo total de la dieta  
7. Costo por litro de leche producido  

### Nivel forrajero (por hectárea)

8. Producción anual de materia seca  
9. Días-vaca soportados por hectárea  
10. Número de vacas alimentadas durante 180 días por hectárea  

---

## Salidas del modelo

Por cada voluminoso, la planilla muestra:

- MS consumida (kg/día)
- Kg de ración necesarios
- Costo total de la dieta ($/día)
- Costo por litro de leche ($/L)
- Vacas alimentadas por hectárea durante 180 días

---

## Uso de la aplicación

1. Abrir el archivo `planilla_alimentacion.html` en cualquier navegador moderno  
2. Modificar los parámetros generales según el sistema evaluado  
3. Ajustar valores de cada voluminoso si es necesario  
4. Presionar el botón **“Calcular”**  
5. Analizar y comparar resultados entre alternativas

No requiere instalación ni conexión a internet.

---

## Público objetivo

- Docentes universitarios  
- Estudiantes de zootecnia y ciencias animales  
- Extensionistas rurales  
- Productores con formación técnica  
- Planificadores de sistemas forrajeros  

---

## Alcances y limitaciones

### Alcances

- Comparación económica clara entre voluminosos  
- Evaluación integrada animal–forraje  
- Alta transparencia de supuestos y cálculos  
- Ideal para análisis de sensibilidad  

### Limitaciones

- No sustituye modelos nutricionales completos  
- No evalúa desempeño productivo real  
- No considera calidad de fibra ni consumo voluntario  

---

## Posibles extensiones futuras

- Inclusión de FDN y digestibilidad  
- Combinación de múltiples voluminosos en una dieta  
- Exportación de resultados a Excel  
- Versión web avanzada (Shiny, Streamlit)  
- Adaptación a sistemas de trópico alto o templado  

---

## Licencia y uso

Uso libre con fines académicos, educativos y de extensión.  
Se recomienda **citar la fuente** si se utiliza en materiales docentes o publicaciones técnicas.
