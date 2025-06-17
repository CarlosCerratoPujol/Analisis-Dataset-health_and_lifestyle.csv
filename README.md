Análisis de Salud y Estilo de Vida con Tidyverse
Este proyecto consiste en un análisis exploratorio y visual del dataset health_and_lifestyle.csv, realizado con herramientas del ecosistema Tidyverse en R. El análisis abarca variables relacionadas con la salud y hábitos de vida para detectar patrones, correlaciones y posibles implicaciones a nivel poblacional.

📊 Objetivos del Proyecto
Limpiar y transformar el conjunto de datos utilizando dplyr y tidyr.

Visualizar la relación entre hábitos de vida (como el ejercicio, la dieta o el consumo de alcohol) y variables de salud.

Identificar insights relevantes usando gráficos y estadísticas descriptivas.

Aplicar principios de análisis reproducible con RMarkdown.

🛠️ Herramientas Utilizadas
R

Tidyverse (dplyr, ggplot2, readr, tidyr)

RMarkdown – Para generar informes reproducibles en HTML.

📁 Estructura del Repositorio
bash
Copiar
Editar
health-lifestyle-analysis/
├── data/
│   └── health_and_lifestyle.csv   # Dataset original
├── health_proyecto_FINAL.Rmd      # Código fuente del informe
├── health_proyecto_FINAL.html     # Informe final en HTML
├── README.md                      # Este archivo
📈 Contenidos del Análisis
Exploración de variables categóricas (sexo, estado civil, etc.)

Análisis de variables continuas (IMC, edad, horas de sueño…)

Gráficos de dispersión, boxplots y correlaciones

Uso de facet_wrap para comparar grupos

Limpieza de valores atípicos y datos faltantes

👤 Autor
Carlos Cerrato Pujol

🔁 Reproducibilidad
Para reproducir el análisis:

Abre el archivo health_proyecto_FINAL.Rmd en RStudio.

Asegúrate de tener instalado el paquete tidyverse.

Haz clic en “Knit” para generar el informe HTML.

r
Copiar
Editar
install.packages("tidyverse")
rmarkdown::render("health_proyecto_FINAL.Rmd")
📄 Licencia
Este proyecto se ha desarrollado con fines educativos y de aprendizaje. No está destinado para uso comercial o clínico.
