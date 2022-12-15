![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

​
# <h1 align="center">**`Proyecto Individual 2`**

<p align="center">
<img src="https://www.ibm.com/blogs/client-voices/wp-content/uploads/2019/09/Glinnt.jpg"   
>
</p>

​
## **¡Bienvenidos!**

En este nuevo proyecto vamos a estar practicando e introduciendonos al campo de Machine Learning.
​
## **Descripción del problema**

Un importante Centro de Salud nos ha contratado para poder predecir si un paciente tendrá una estancia hospitalaria prolongada o no, utilizando la información contenida en el dataset asociado, la cual recaba una muestra histórica de sus pacientes, para poder administrar la demanda de camas en el hospital según la condición de los pacientes recientemente ingresados. 

Para esto, se define que un paciente posee estancia hospitalaria prolongada si ha estado hospitalizado más de 8 días. Nuestro objetivo como Data Scientist es que podamos estimar a partir de los datos historicos, que pacientes son los mas propensos a una estancia larga en internacion. 

## 🏥 **¿Que es la Estancia Hospitalaria?** 🏥

La hospitalización, o estancia hospitalaria, cuando es prolongada constituye una preocupación a nivel mundial debido a sus efectos negativos en el sistema de salud, aumentando los costos, generando deficiencia en la accesibilidad de prestación de servicios de salud, saturación de unidades de hospitalización y urgencias, por consiguiente, mayores efectos adversos como lo son las enfermedades intrahospitalarias.

El estudio de los procesos de atención en salud, así como el conocimiento de las características y perfiles de los usuarios con el objetivo de predecir la ocupación hospitalaria, es uno de los aspectos al que las autoridades de salud han prestado gran interés, pues permite no sólo garantizar los recursos necesarios para la atención del paciente, sino realizar ajustes respecto a la oferta y demanda de los servicios de salud y los implementos asociados.

## **Descripcion del trabajo**

El trabajo realizado durante este proyecto, consiste en realizar un analisis exploratorio de los datos para ver su comportamiento, revisar si hay datos duplicados, nulos, etc. Luego pasamos a verificar las relaciones entre los datos, entre las columnas y como se modifican mutuamente. Aqui podemos descartar columnas como el nombre del doctor o los id de paciente ya que podrian sesgar nuestro modelo y no aportarian informacion relevante para nuestro analisis.
Por ultimo se procede a elegir las features que utilizaremos para el modelo, separar los datos en datos de entrenamiento y de testeo e instanciar el modelo, en ultima instancia se generara un archivo cuya unica columna llevara los datos de predicciones. 
​
## **Descripción de las columnas**
- Available Extra Rooms in Hospital: Habitaciones adicionales disponibles en el hospital. Una habitación no es igual a un paciente, pueden ser individuales o compartidas.
- Department: Área de atención a la que ingresa el paciente. 
- Ward_Facility_Code: Código de la habitación del paciente.
- doctor_name: Nombre de el/la doctor/a a cargo del paciente.
- staff_available: Cantidad de personal disponible al momento del ingreso del paciente.
- patientid: Identificador del paciente.
- Age: Edad del paciente.
- gender: Género del paciente.
- Type of Admission: Tipo de ingreso registrado según la situación de ingreso del paciente.
- Severity of Illness: Gravedad de la enfermedad/condición/estado del paciente al momento del ingreso.
- health_conditions: Condiciones de salud del paciente. 
- Visitors with Patient: Cantidad de visitantes registrados para el paciente.
- Insurance: Indica si la persona posee o no seguro de salud. 
- Admission_Deposit: Pago realizado a nombre del paciente, con el fin de cubrir los costos iniciales de internación. 
- Stay (in days): Días registrados de estancia hospitalaria. 
​
## Disclaimer  ##
De parte del equipo de Henry se quiere aclarar y remarcar que los fines de los proyectos propuestos son exclusivamente pedagógicos, con el objetivo de realizar proyectos que simulen un entorno laboral, en el cual se trabajen diversas temáticas ajustadas a la realidad.
 No reflejan necesariamente la filosofía y valores de la organización. Además, Henry no alienta ni tampoco recomienda a los alumnos y/o cualquier persona leyendo los repositorios (y entregas de proyectos) que tomen acciones en base a los datos que pudieran o no haber recabado. Toda la información expuesta y resultados obtenidos en los proyectos, nunca deben ser tomados en cuenta para la toma real de decisiones (especialmente en la temática de finanzas, salud, política, etc.).
