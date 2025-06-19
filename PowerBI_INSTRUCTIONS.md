# Power BI Dashboard

Este repositorio contiene un archivo de Excel con los datos de auditoría. Para crear un panel en Power BI que replique el dashboard solicitado, siga estos pasos en Power BI Desktop:

1. **Conectar al Excel**: Seleccione *Obtener datos → Excel* y elija `Analisis Gratificacion 2024 - Prosegur V2.xlsx`.
2. Importe las hojas **Resumen x Soc** y **Resumen x Pers**.
3. En *Power Query* verifique que los encabezados coincidan y aplique tipos de datos.
4. Cierre y aplique los cambios para cargar las tablas al modelo.
5. Cree visualizaciones:
   - Tabla o matriz con la información consolidada por sociedad (renta imponible, factor de reparto, 30 % recalculado, etc.).
   - Tabla por colaborador mostrando las diferencias detectadas.
   - Gráficos de barras que comparen valores declarados versus recalculados.
   - Indicador o *gauge* para el factor de reparto.
6. Agregue segmentadores (*slicers*) para filtrar por **Sociedad**, **Tipo de Grat.** y **Colaborador**.
7. Organice las visualizaciones en una página de reporte denominada **Dashboard**.
8. Guarde el archivo como `dashboard.pbix`.
9. (Opcional) Para vincular el archivo PBIX dentro del Excel, abra el libro, elija *Insertar → Objeto*, seleccione **Crear desde archivo** y busque `dashboard.pbix`.

Al abrir el PBIX el usuario podrá actualizar los datos desde el Excel y consultar el panel interactivo.
