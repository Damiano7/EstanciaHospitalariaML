## 馃彞 **Estancia hospitalaria** 馃彞

La hospitalizaci贸n, o estancia hospitalaria, cuando es prolongada constituye una preocupaci贸n a nivel mundial debido a sus efectos negativos en el sistema de salud, aumentando los costos, generando deficiencia en la accesibilidad de prestaci贸n de servicios de salud, saturaci贸n de unidades de hospitalizaci贸n y urgencias, por consiguiente, mayores efectos adversos como lo son las enfermedades intrahospitalarias.

El estudio de los procesos de atenci贸n en salud, as铆 como el conocimiento de las caracter铆sticas y perfiles de los usuarios con el objetivo de predecir la ocupaci贸n hospitalaria, es uno de los aspectos al que las autoridades de salud han prestado gran inter茅s, pues permite no s贸lo garantizar los recursos necesarios para la atenci贸n del paciente, sino realizar ajustes respecto a la oferta y demanda de los servicios de salud y los implementos asociados.

## **Descripci贸n del problema**

Un importante Centro de Salud lo ha contratado con el fin de poder predecir si un paciente tendr谩 una estancia hospitalaria prolongada o no, utilizando la informaci贸n contenida en el dataset asociado, la cual recaba una muestra hist贸rica de sus pacientes, para poder administrar la demanda de camas en el hospital seg煤n la condici贸n de los pacientes recientemente ingresados.

Para esto, se define que un paciente posee estancia hospitalaria prolongada si ha estado hospitalizado m谩s de 8 d铆as. Por lo que debe generar dicha variable categ贸rica y luego categorizar los pacientes seg煤n las variables que usted considere necesarias, justificando dicha elecci贸n.

## **M茅trica a utilizar**

Como m茅todo de evaluaci贸n del desempe帽o del modelo, se utilizar谩 la m茅trica de Exhaustividad (Recall) para las estad铆as hospitalarias largas, a partir de la matriz de confusi贸n (Confusion Matrix).

$$
Recall=\frac{TP}{TP+FN}
$$

Donde TP son los verdaderos positivos y FN los falsos negativos.

Como m茅trica adicional para verificar el desempe帽o de su modelo, tambi茅n se utilizar谩 la m茅trica de precisi贸n (Accuracy) para las estad铆as hospitalarias largas.

$$
Accuracy=\frac{TP+TN}{P+N}
$$

siendo TP los verdaderos positivos, TN verdaderos negativos y P+N poblaci贸n total.

## **Archivos provistos**

Se proveen los siguientes archivos para realizar el proyecto:

* 'hospitalizaciones_train.csv': Contiene 410000 registros y 15 dimensiones, el cual incluye la informaci贸n **num茅rica** de la cantidad de d铆as de estancia hospitalaria.
* 'hospitalizaciones_test.csv': Contiene 90000 registros y 14 dimensiones, el cual no incluye la informaci贸n de la cantidad de d铆as de estancia hospitalaria.

## **Descripci贸n de las dimensiones**

* Available Extra Rooms in Hospital: Habitaciones adicionales disponibles en el hospital. Una habitaci贸n no es igual a un paciente, pueden ser individuales o compartidas.
* Department: 脕rea de atenci贸n a la que ingresa el paciente.
* Ward_Facility_Code: C贸digo de la habitaci贸n del paciente.
* doctor_name: Nombre de el/la doctor/a a cargo del paciente.
* staff_available: Cantidad de personal disponible al momento del ingreso del paciente.
* patientid: Identificador del paciente.
* Age: Edad del paciente.
* gender: G茅nero del paciente.
* Type of Admission: Tipo de ingreso registrado seg煤n la situaci贸n de ingreso del paciente.
* Severity of Illness: Gravedad de la enfermedad/condici贸n/estado del paciente al momento del ingreso.
* health_conditions: Condiciones de salud del paciente.
* Visitors with Patient: Cantidad de visitantes registrados para el paciente.
* Insurance: Indica si la persona posee o no seguro de salud.
* Admission_Deposit: Pago realizado a nombre del paciente, con el fin de cubrir los costos iniciales de internaci贸n.
* Stay (in days): D铆as registrados de estancia hospitalaria.
