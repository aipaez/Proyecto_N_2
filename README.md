# Informe de Proyecto N°2

Titulo: Circuito Escalera

Nombres:

-Christian Chala  

-Steveen Vallejo

-Ismael Paez

Fecha: 17/01/2023

NRC: 10067

Carrera: Mecatronica

OBJETIVO GENERAL:

Analizar el video propuesto del funcionamiento del circuito y utilizar ingenieria inversa para comprender su funcionamineto asi como que funcion realiza cada componente del mismo.

OBJETIVOS ESPECIFICOS:

-Replicar el circuito del video para verificar su funcionamiento con nuestros propios elementos. 

-Investigar los nuevo componentes utilizados en el video que no se han visto en clase.

-Implementar la materia estudiada para hacer el circuito con componentes que se utilizarian en una estructura real y ya no a pequela escala como lo es en el protoboard.

# 2.	MARCO TEÓRICO (RESUMEN)

![TIPOS DE CABLE EN UNA INSTALACION ELECTRICA](https://user-images.githubusercontent.com/117959424/212802162-0c1dec69-3ad5-4289-9f6f-1099167610dd.png)

![Materiales](https://user-images.githubusercontent.com/117959424/212804414-045f4dfd-75fb-4898-bd78-75d1084ed5aa.png)

# 3.	EXPLICACIÓN DEL PROCEDIMIENTO

1. Primero se recomienda realizar un diagrama esquematico para poder entender el funcionamiento y al aplicar la simulacion virtual tenemos la certeza que el circuito funciona tan solo para armarlo en fisico.
Para esto usaremos proteus desarrollando el siguiente esquema de un cirucuito escalera que se define como un circuito con dos interruptores para encender y apagar un foco o bombilla desde ambos interruptores.

![image](https://user-images.githubusercontent.com/117959424/212805033-e48285fa-609d-489e-96f5-d58d0b21ae1a.png)

2. Dado que los interruptores hacen un papel fundamental, debemos tener previsto que estos cuentan con tres contactos en su parte trasera que nos serviran para hacer las conexiones en el medio tiene un contacto que llamamos comun, este es el que se cerrara segun la posicion del interrumptor en retorno 1 o retorno 2 para encender o apagar la bombilla.

![image](https://user-images.githubusercontent.com/117959424/212805379-c45b0d3c-19d5-47b2-a2d1-db9a31b84a0b.png)

3. Una vez entendido los interruptores procedemos a realizar las conexiones, usaremos un cable blanco para neutro y para fase/linea un cable amarillo, conectamos neutro a la roseta de modo que haga contacto con la rosca de la bombilla ya que neutro se conecta a la rosca.

![WhatsApp Image 2023-01-16 at 2 01 19 PM](https://user-images.githubusercontent.com/117959424/212806084-e7f3f42f-d88a-4632-b443-c02bd0f31b3e.jpeg)

4. Despues procedemos a realizar una conexion del cable fase (amarillo) a uno de los interrumptores al punto comun (el del medio), pero luego a su vez realizar una conexion "puente" entre los contactos de ambos interruptores (RETORNO 1 CON RETORNO 1 Y RETORNO 2 CON RETORNO 2) 

![Puente](https://user-images.githubusercontent.com/117959424/212807170-fe86c693-f89a-4ddd-8542-c739d8446516.jpg)

5. Para completar el circuito del interrumpor que aun tenia el contacto comun libre llevamos un cable al contacto libre en la roseta para cerrar el circuito. A esto lo llamaremos retorno.

![R](https://user-images.githubusercontent.com/117959424/212807689-577d70bb-b912-461b-a19a-f01d10dbe5cd.jpg)

6. Para el funcionamiento del foco, los puntos Retorno 1-Retorno 1 deben estar en contacto para cerrar el circuito. Su funcionamiento interno se veria algo asi.

![image](https://user-images.githubusercontent.com/117959424/212807962-3c54f151-94d1-46a2-9b8e-18f45e183bf8.png)

7. Y en el circuito fisico se veria asi:

![WhatsApp Image 2023-01-16 at 2 01 18 PM](https://user-images.githubusercontent.com/117959424/212808015-7ad0bfea-0b9d-4e91-b141-8673e3382c72.jpeg)

# 4.	RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

NO APLICA.

# 5.	VIDEO

https://www.youtube.com/watch?v=nsBmFUANkJw

# 6.	CONCLUSIONES

-) Este proyecto es del tipo que se pueden aplicar a un escenario real ya que es muy util contar con dos interruptores para un solo bombillo, ya que podria uno estar al entrar a la habitacion y otro cerca de la cama para no levantarse a apagarlo asi que es muy util.

-) Con este tipo de instalaciones ya hay que tener mucho cuidado al armar debido a que este ya no se conecta a una fuente de 9V como los pequeños circuitos sino que la tension sube a 220V y podria ser peligroso si se manipula sin conocimiento previo e imprudencia.

-) Para mayor versatilidad se puede agregar tubos de PVC para poder pasar por ahi los cables y que no esten expuestos

# 7.	BIBLIOGRAFIA

Casa, E. en [@ElectricistaenCasa]. (2020, agosto 28). Circuito Escalera, 924, Vaiven, 3 Vias, pasó a paso. Youtube. https://www.youtube.com/watch?v=q3oUc9_qnyc

Digitales, C. (2020, noviembre 10). ¿Cómo diferenciar un cable de otro? Endesa. https://www.endesa.com/es/blog/blog-de-endesa/luz/tipos-cables-toma-tierra-fase

Olivarex, R. (2021, marzo 23). ¿Qué Es Un Cable Neutro Y Qué Hacer Si No Tiene Uno? Domoticfy. https://domoticfy.com/cable-neutro-y-que-hacer-si-no-tiene-uno/

# 8. RUBRICA

![image](https://user-images.githubusercontent.com/116814096/200999683-fe53d616-5553-4761-bdf4-e15a280451cb.png)








