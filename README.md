# Dashboard_DataAnalisis 

Esta aplicación web, desarrollada con **Streamlit**, permite visualizar y analizar ingresos diarios de apartamentos turísticos a partir de datos de reservas almacenados en un archivo CSV.  

## Funcionalidades principales  
- **Procesamiento de datos**:  
  Convierte las fechas de check-in y check-out en ingresos diarios distribuidos por noche.  

- **Filtros interactivos**:  
  Permite seleccionar año, apartamento, plataforma de reservas y meses concretos.  

- **Visualizaciones**:  
  - Gráfico de barras con los ingresos mensuales por apartamento.  
  - Gráfico de distribución de países de origen de los clientes (con agrupación en "Otros" para porcentajes bajos).  

- **Interactividad**:  
  Uso de **Altair** para gráficos dinámicos con tooltips y adaptación al ancho de la pantalla.  

## Tecnologías utilizadas  
- Python (Pandas, Numpy)  
- Streamlit  
- Altair (visualización de datos)  

## Ejecución  
1. Instalar dependencias:  
   ```bash
   pip install -r requirements.txt
2. Ejecutar la aplicacion:
streamlit run app.py