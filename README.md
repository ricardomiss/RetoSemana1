# <center>Reto de semana 1</center>
## :notebook: Guia de estudio para la certicicacion AZ-900: Microsoft Azure Fundamentals

En este repositorio estaremos haciendo actualizaciones sobre diferentes conceptos que necesitemos reforzar relacionadas a inteligencia artificial.
![image](https://user-images.githubusercontent.com/83625063/117548964-67eb6980-affd-11eb-9bb2-8ba916494de5.png)

## Índice
[Modelo OSI](https://github.com/AlexDeal/RetoSemana1#que-es-modelo-osi)

[Protocolo TCP\IP](https://github.com/AlexDeal/RetoSemana1#que-es-protocolo-tcpip)

[Servidor Espejo](https://github.com/AlexDeal/RetoSemana1#que-es-un-servidor-espejo)

[IaaS, Paas y Saas](https://github.com/AlexDeal/RetoSemana1#iaas-paas-y-saas)

[API](https://github.com/AlexDeal/RetoSemana1#que-es-una-api)

[FrameWork](https://github.com/AlexDeal/RetoSemana1#que-es-un-framework)

[CAPEX y OPEX](https://github.com/AlexDeal/RetoSemana1#capex-y-opex)

[Acuerdo de nivel de servicio (SLA)](https://github.com/AlexDeal/RetoSemana1#acuerdo-de-nivel-de-servicio)

[Acuerdo de nivel de servicio en Azure](https://github.com/AlexDeal/RetoSemana1#acuerdo-de-nivel-de-servicio-en-azure)

[DevOps](https://github.com/AlexDeal/RetoSemana1#que-es-un-devops)


## :books: Conceptos
### ¿Que es modelo OSI?
* Es un modelo conceptual, creado por la Organización Internacional para la Estandarización, que permite que diversos sistemas de comunicación se comuniquen entre sí usando protocolos estándar. O dicho con más claridad: OSI proporciona a los diferentes sistemas de ordenadores existentes un estándar para comunicarse entre sí.

![image](https://www.cloudflare.com/img/learning/ddos/what-is-a-ddos-attack/osi-model-7-layers.svg)

### ¿Que es Protocolo TCP\IP?
* Es un conjunto de protocolos que permiten la comunicación entre los ordenadores pertenecientes a una red. La sigla TCP/IP significa Protocolo de control de transmisión/Protocolo de Internet. TCP/IP representa todas las reglas de comunicación para Internet y se basa en la noción de dirección IP, es decir, en la idea de brindar una dirección IP a cada equipo de la red para poder enrutar paquetes de datos.

### ¿Que es un Servidor Espejo?
* Es una copia fiel del servidor original, es decir que incluyen estos mismos ítems:
  * Sistema operativo (Linux, Unix o Windows)
  * Servicios de sistema
  * Aplicaciones
  * Configuraciones
  * Archivos
  * Bases de Datos (MySQL, PostgreSQL, MongoDB, etc)
  * Emails
* Teniendo todo esto replicado en un segundo servidor hace que se pueda tener una cierta «seguridad» respecto a si el servidor primario es presa de una catástrofe natural, hay una rotura de hardware crítica que lleva muchas horas solucionar, hackeo y pérdida de datos, etc.

## IaaS PaaS y SaaS

![image](https://nanobytes.es/web/image/55083/Comparativa%20iaas%20paas%20saas.png?access_token=760263c2-d615-4e27-887f-a463ed1366d0)

### IaaS
* La infraestructura como servicio (IaaS), también conocida como servicios de infraestructura en la nube, es una forma de cloud computing que ofrece a los usuarios finales una infraestructura de TI a través de Internet. Este tipo de infraestructura otorga al usuario el control total de la nube. Es decir, el usuario se encarga de la configuración de equipos, elección del tipo de procesador o de la capacidad memoria, etc. Es un sistema que se adapta a la medida de la empresa quienes utilizan sus propias aplicaciones y plataformas. Pero las mismas se encuentran dentro de una infraestructura propiedad del proveedor del servicio.

<img width="400" alt="portfolio_view" src="https://como-funciona.com/wp-content/uploads/2019/08/c%C3%B3mo-funciona-el-sistema-iaas-768x768.png)">

### PaaS
*  Es una modalidad del cloud computing en la cual un tercero brinda el sistema de hardware y una plataforma de software de aplicaciones. La PaaS es ideal principalmente para los desarrolladores y los programadores, ya que permite que el usuario desarrolle, ejecute y gestione sus propias aplicaciones sin tener que diseñar ni mantener la infraestructura ni la plataforma que suelen estar relacionadas con el proceso.

![image](https://www.teamnet.com.mx/hubfs/PaaS.png)

### SaaS
* Es una forma de cloud computing que ofrece a los usuarios una aplicación en la nube junto con toda su infraestructura de TI y plataformas subyacentes. Puede ser la solución ideal para las empresas, ya sean grandes o pequeñas, o las personas con las siguientes características:
  * No quieren encargarse de las tareas de mantenimiento de la infraestructura, las plataformas y el software.
  * Tienen desafíos que pueden resolverse con una personalización mínima.
  * Prefieren los modelos de suscripción de software.

![image](https://azurecomcdn.azureedge.net/cvt-93da322b8e36592b6fa17faa77857ee4467225501ecd84a7c5466e5d0f790b30/images/page/overview/what-is-saas/what-is-saas.png)

### ¿Que es una API?
* Se trata de un conjunto de definiciones y protocolos que se utiliza para desarrollar e integrar el software de las aplicaciones, permitiendo la comunicación entre dos aplicaciones de software a través de un conjunto de reglas. Así pues, podemos hablar de una API como una especificación formal que establece cómo un módulo de un software se comunica o interactúa con otro para cumplir una o muchas funciones. Todo dependiendo de las aplicaciones que las vayan a utilizar, y de los permisos que les dé el propietario de la API a los desarrolladores de terceros.

### ¿Que es un Framework?
* Es un esquema (un esqueleto, un patrón) para el desarrollo y/o la implementación de una aplicación. Utilizar un framework permite agilizar los procesos de desarrollo ya que evita tener que escribir código de forma repetitiva, asegura unas buenas prácticas y la consistencia del código. Por tanto es un conjunto de herramientas y módulos que pueden ser reutilizados para varios proyectos.

## CAPEX y OPEX
![image](https://blog.aitana.es/wp-content/uploads/2019/11/capex-opex.jpg)

### Capex
* El Capex (capital expenditure o gasto en capital) es el gasto que una compañía realiza en bienes de equipo y que resulta en beneficios que garantizan y miden su crecimiento. Esto se da gracias a la adquisición de activos fijos o bien en el aumento del valor de los que ya existen. Se trata de la caja que una organización gestiona para mantener sus activos estables y en buenas condiciones. Por ejemplo, nuevas computadoras, material de oficina, equipos de transporte, mejores instalaciones, etc.

![image](https://st4.depositphotos.com/13672908/31188/v/600/depositphotos_311885778-stock-illustration-capex-capital-expenditure-concept-with.jpg)

### Opex
* El Opex (Operational expenditures) son los gastos operativos o de explotación son conocidos como Opex, y son gastos que se realizan de forma continuada y están relacionados con las operaciones de la empresa. Es un costo permanente para el funcionamiento de un producto, negocio o sistema. Puede traducirse como gasto de funcionamiento, gastos operativos, o gastos operacionales.

![image](https://image.shutterstock.com/image-vector/opex-operational-expenditure-concept-big-260nw-1519002905.jpg)

## Acuerdo de nivel de servicio
* SLA (Service Level Agreement), es un acuerdo escrito entre un proveedor de servicio y su cliente con objeto de fijar el nivel acordado para la calidad de dicho servicio. El ANS es una herramienta que ayuda a ambas partes a llegar a un consenso en términos del nivel de calidad del servicio, en aspectos tales como tiempo de respuesta, disponibilidad horaria, documentación disponible, personal asignado al servicio, etc.

### Acuerdo de nivel de servicio en Azure

![image](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Microsoft_Azure_Logo.svg/1280px-Microsoft_Azure_Logo.svg.png)

### Azure Active Directory:
* Garantizamos que habrá una disponibilidad del 99,99 % de los servicios de Azure Active Directory Básico y Premium. Los servicios se consideran disponibles en los siguientes escenarios:
 * Los usuarios pueden iniciar sesión en el servicio Azure Active Directory.
 * Azure Active Directory emite correctamente los tokens de autenticación y autorización necesarios para que los usuarios inicien sesión en las aplicaciones conectadas al servicio.
 * No se ofrece un Contrato de nivel de servicio (SLA, Service Level Agreement) para la edición Free de Azure Active Directory.

### Azure Active Directory B2C
* Garantizamos una disponibilidad del 99,9 %, como mínimo, del servicio Azure Active Directory B2C. El servicio se considera disponible para un directorio en los siguientes escenarios:
 * El servicio puede procesar el registro de un usuario, el inicio de sesión, la edición del perfil, el restablecimiento de la contraseña y solicitudes de autenticación multifactor.
 * Los desarrolladores pueden crear, leer, escribir y eliminar entradas en el directorio.
 * No se proporciona ningún SLA para el nivel Gratis de Azure Active Directory B2C.

### ¿Que es un DevOps?
* Es una combinación de los términos ingleses development (desarrollo) y operations (operaciones), designa la unión de personas, procesos y tecnología para ofrecer valor a los clientes de forma constante. Permite que los roles que antes estaban aislados (desarrollo, operaciones de TI, ingeniería de la calidad y seguridad) se coordinen y colaboren para crear productos mejores y más confiables.

