# 📊 Proyecto de Estadística: Relación entre Sueño y Rendimiento Académico 💤

## 📚 Información del Proyecto

- **Asignatura**: Estadística
- **Carrera**: GISI (Grado en Ingeniería de Sistemas de Información)

## 📋 Descripción

Este proyecto realiza un análisis estadístico exhaustivo para evaluar la relación entre las horas y la calidad del sueño y el rendimiento académico (nota media del curso anterior) de estudiantes de GISI. Además, se examinan otros factores que pueden influir en el desempeño académico como la actividad física, la edad y el sexo.

## 🎯 Objetivos

- **Objetivo Principal**: Evaluar la relación entre las horas y la calidad del sueño y el rendimiento académico (nota media del curso anterior) de estudiantes de GISI
- **Objetivos Secundarios**:
  - Analizar el impacto de la calidad del sueño en el rendimiento académico
  - Evaluar la influencia de la actividad física en las calificaciones
  - Examinar diferencias por sexo y curso académico
  - Identificar la relación entre edad y rendimiento académico

## 🧩 Metodología

- **Población**: Estudiantes matriculados en GISI
- **Muestra**: ~200 participantes
- **Muestreo**: Por curso
- **Nivel de significancia**: α = 0.05

## 📊 Variables del Estudio

| Variable | Descripción | Clasificación | Tipo |
|----------|-------------|---------------|------|
| `nota_media_0_10` | Nota media del curso anterior (escala 0-10) | **Dependiente** | Numérica continua |
| `horas_sueno_cat` | Categorías de horas de sueño (<5h, 5-7h, 7-8h, 8-10h, >10h) | **Principal** | Categórica ordinal |
| `calidad_sueno_1_10` | Calidad del sueño percibida (escala 1-10) | **Principal** | Numérica continua |
| `actividad_fisica_1_10` | Nivel de actividad física (escala 1-10) | Covariable | Numérica continua |
| `edad_categoria` | Edad del estudiante | Covariable | Categórica |
| `sexo` | Sexo del estudiante | Covariable | Categórica |
| `curso` | Curso académico | Covariable | Categórica |


## 📁 Estructura del Proyecto

```
Estudio_Estadistico/
│
├── README.md                      
├── Análisis Estadístico.Rmd     
├── Datos Estadística.xlsx
├── Estudio Estadistica-Analisis Estadistico.pdf
└── Estudio Estadistica-Metodologia.pdf
```

## 📊 Resultados Principales

### Hallazgos Significativos

✅ **Calidad del Sueño**
- Correlación positiva y significativa con la nota media
- **r = 0.465, p < 0.001**
- Mayor calidad de sueño se asocia con mejor rendimiento académico

✅ **Horas de Sueño**
- Dormir **7-10 horas** se asocia con una **mejora de ~1.2 puntos** en la nota media
- **p < 0.001** (altamente significativo)
- Categorías extremas (<5h o >10h) muestran rendimiento inferior

✅ **Actividad Física**
- Relación positiva leve con la nota media
- **r = 0.178, p = 0.017**
- Efecto menor pero estadísticamente significativo

❌ **Variables sin Influencia Significativa**
- **Edad**: No se encontró relación significativa con el rendimiento
- **Sexo**: No se observaron diferencias significativas entre géneros

### Interpretación

Los resultados indican que:
- La calidad del sueño es el predictor más fuerte del rendimiento académico
- Mantener un horario de sueño regular de 7-10 horas optimiza el desempeño
- La actividad física contribuye positivamente, aunque en menor medida
- El rendimiento es independiente de la edad y el sexo en esta muestra

## ⚠️ Limitaciones del Estudio

Es importante considerar las siguientes limitaciones al interpretar los resultados:

- **Encuestas incompletas**: Algunas respuestas presentaban datos faltantes que fueron excluidos del análisis
- **Variables subjetivas**: La calidad del sueño y la actividad física son medidas auto-reportadas y pueden estar sujetas a sesgos de percepción
- **Muestra limitada**: El estudio se realizó únicamente con estudiantes de GISI, lo que limita la generalización de los resultados a otras carreras o universidades
- **Diseño transversal**: Al ser un estudio de corte transversal, no se pueden establecer relaciones causales definitivas
- **Correlación ≠ Causalidad**: Aunque se encontraron asociaciones significativas, no implican necesariamente relaciones causa-efecto

## 📝 Conclusiones

Este estudio proporciona evidencia estadística sólida sobre la importancia del sueño en el rendimiento académico de estudiantes universitarios. Los hallazgos sugieren que:

1. Promover buenos hábitos de sueño podría mejorar el desempeño académico
2. La calidad del sueño es tan importante como la cantidad de horas
3. Mantener un equilibrio entre descanso, actividad física y estudios puede optimizar el rendimiento

## 👥 Equipo de Trabajo

- Pedro Varona
- Francisco Javier Martínez
- Alfredo Martínez
- Juan García Obregón

---