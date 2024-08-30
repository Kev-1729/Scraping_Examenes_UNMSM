# Web Scraping Simulacro UNMSM

Este proyecto realiza un scraping de datos desde la página de simulacro de admisión de la Universidad Nacional Mayor de San Marcos (UNMSM). El objetivo es extraer información sobre las escuelas profesionales y los datos de los estudiantes de una tabla paginada en el sitio web.

## Descripción

El script realiza las siguientes acciones:
1. **Extrae URLs de escuelas profesionales**: Obtiene las URL de las diferentes escuelas a partir de una página que lista todas las escuelas.
2. **Obtiene datos de estudiantes**: Navega a cada URL y extrae información sobre los estudiantes de una tabla paginada. Los datos incluyen la Escuela Profesional y la Nota.
3. **Guarda los datos en un archivo CSV**: Almacena los datos extraídos en archivos CSV para su posterior análisis.

## Requisitos

- Python 3.8 o superior
- Selenium
- pandas

## Instalación

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/Kev-1729/Web_Scraping_Simulacro_UNMSM.git
