# Dashboard de recursos humanos utilizando Tableau - Proyecto de visualización de datos

Este proyecto tiene como objetivo analizar la información de recursos humanos de una compañía que tiene sucursales que se encuentran ubicadas en diferentes departamentos de Nicaragua. Para poder facilitar la toma
de decisiones de la compañía al entender mejor sus RRHH, se realizaron dos dashboards, el primero ofrece una vista general de los RRHH y el otro provee información específica de empleados. Los datos fueron generados
de manera sintética usando la libreria Faker de Python. El dashboard se encuentra [aquí](https://public.tableau.com/views/DashboardRRHH_17271281026740/RRHHResumen?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link")

<div class='tableauPlaceholder' id='viz1727918442354' style='position: relative'><noscript><a href='#'><img alt='RRHH | Resumen ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DashboardRRHH_17271281026740&#47;RRHHResumen&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DashboardRRHH_17271281026740&#47;RRHHResumen' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DashboardRRHH_17271281026740&#47;RRHHResumen&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1727918442354');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1400px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1400px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='4077px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>



**Conjunto de datos:**

En este caso, hemos utilizado un set de datos que incluye información de 8950 empleados de la compañía. Para este conjunto de
 datos hemos trabajado con 24 columnas que contienen información importante para el análisis de recursos humanos, incluyendo: 

1. Apellido

2. Calificación de desempeño

3. Ciudad

4. Departamento (Atención al Cliente, TI, Operaciones, Ventas, Marketing, Finanzas, RRHH)

5. Estado (Terminado, Contratado)

6. Fecha de contratación

7. Fecha de terminación

8. Grupos de edad (<25, 25-34, 35-44, 45-54, 55+)

9. Género (Hombre, Mujer)

10. Horas extra (Sí, No)

11. ID de Empleado

12. Localización (OC (Oficina central), Sucursal)

13. Nivel de Educación (Sec. (Secundaria), Lic. (Licenciatura), M.C. (Maestría en Ciencias), Dr. (Doctor))

14. Nombre

15. Nombre completo

16. Provincia (Managua, Rivas, Estelí, Granada, León, Chinandega, Matagalpa)

17. Puesto de trabajo

18. Duración del contrato (1, 2, 3, etc.)

19. Edad

20. Salario

21. Total de activos

22. Total de contratados

23. Total de terminados


**Dashboard 1: Vista general de recursos humanos:**

Este dashboard presenta datos sobre la fuerza laboral de la compañía, incluyendo:

- Distribución de los empleados por provincia: Mapa de Nicaragua mostrando la cantidad de empleados por departamento.

- Composición de la fuerza laboral: Gráficos que muestran la distribución de los empleados por géneros, grupos de edad, nivel educativo y departamento.

- Tendencias de contratación y terminación: Gráficos de líneas que muestran la evolución de las contrataciones y terminaciones a lo largo del tiempo.

- KPIs: Tarjetas donde se muestra el total de empleados activos, contratados y terminados.

Filtros interactivos: Permite filtrar la información por provincia, departamento, género, grupo de edad, etc.

**Dashboard 2: Vista Detallada de Empleados:**

Este dashboard permite profundizar en los datos de empleados específicos, incluyendo:

- Datos del empleado: Nombre completo, ID de empleado, puesto de trabajo, departamento, provincia, salario, fecha de contratación, etc.

- Historial del empleado: Visualización de la duración del contrato, evaluación del desempeño a lo largo del tiempo.

- Filtros interactivos: Permite buscar empleados por nombre, ID o filtrar por distintos criterios.


**Resultados del proyecto:**

Este proyecto representa un análisis de recursos humanos contundente al desarrollar paneles de control. La dirección tendrá una visión panorámica de la fuerza laboral e identificación de oportunidades en la gestión del talento, tomando decisiones estratégicas basadas en datos.

**Mejoras posibles:**

- Se puede añadir más información, como datos de evaluación del desempeño, capacitación recibida, etc.

- Utilizar análisis predictivos para prever la rotación de personal, o úsalo para desarrollar una lista de personas que podrían ser promovidas.

- Integrar los paneles de control con otras herramientas utilizadas para un análisis profundo.

Este proyecto es inspirado por el dashboard creado por [Baraa Khatib Sakini en este video](https://www.youtube.com/watch?v=UcGF09Awm4Y).