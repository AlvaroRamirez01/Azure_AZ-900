## Descripción de la informática en la nube
https://learn.microsoft.com/es-mx/training/modules/describe-cloud-compute/

* ¿Qué es la informática en la nube?: Es la prestación de servicios informáticos a través de internet.
*  ¿Qué tipos de nube existen?
	* Existe 3 tipos de nube (Nube Publica, Nube Privada, Nube Hibrida), la publica es la que se comparte con todo mundo, la privada es la que esta dedicada a un cliente y la hibrida es una combinación de ambas.
* Descripción del modelo de responsabilidad compartida
En un centro de datos tradicional es responsable de la seguridad y mantenimiento el cliente, en un centro de datos en la nube el responsable es el proveedor del servicio.
El modelo de responsabilidad compartida está muy vinculado a los tipos de servicio en la nube (que se tratan más adelante en esta ruta de aprendizaje): infraestructura como servicio (IaaS), plataforma como servicio (PaaS) y software como servicio (SaaS). IaaS sitúa la mayor responsabilidad en el consumidor y el proveedor de servicios en la nube es el responsable de los conceptos básicos de seguridad física, energía y conectividad. En el extremo opuesto, SaaS sitúa la mayor parte de la responsabilidad en el proveedor de servicios en la nube. PaaS, siendo un punto intermedio entre IaaS y SaaS, se encuentra en algún lugar del medio y distribuye uniformemente la responsabilidad entre el proveedor de nube y el consumidor.

![[Pasted image 20231027133827.png]]

Siempre será responsabilidad suya lo siguiente:

- La información y los datos almacenados en la nube.
- Los dispositivos que pueden conectarse a la nube (teléfonos móviles, equipos, etc.).
- Las cuentas e identidades de las personas, servicios y dispositivos de la organización

El proveedor de nube siempre es el responsable de lo siguiente:

- El centro de datos físico
- La red física
- Los hosts físicos

El modelo de servicio determinará la responsabilidad de cosas como lo siguiente:

- Sistemas operativos
- Controles de red
- APLICACIONES
- Identidad e infraestructura
## Modelos basados en consumo

Los gastos de capital suelen ser un gasto por adelantado único para comprar o proteger recursos tangibles. Un edificio nuevo, volver a pavimentar el aparcamiento, crear un centro de datos o comprar un coche de empresa son ejemplos de gastos de capital.

En cambio, los gastos operativos es gastar dinero en servicios o productos a lo largo del tiempo. Alquilar un centro de convenciones, alquilar un vehículo de empresa o suscribirse a servicios en la nube son ejemplos de gastos operativos.


## Extras
## Azure Arc

Azure Arc es un conjunto de tecnologías que ayudan a administrar el entorno en la nube. Azure Arc puede ayudar a administrar el entorno de nube, tanto si se trata de una nube pública exclusiva de Azure, una nube privada en el centro de datos, una configuración híbrida o incluso un entorno de varias nubes que se ejecuta en varios proveedores de la nube a la vez.

## Azure VMware Solution

¿Qué ocurre si ya está establecido con VMware en un entorno de nube privada, pero quiere migrar a una nube pública o híbrida? Azure VMware Solution le permite ejecutar las cargas de trabajo de VMware en Azure con una integración y escalabilidad perfectas.