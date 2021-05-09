# Informática en la nube
![image](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.redix.com.br%2Fsolucoes%2Fcloud-nuvem-publica-hibrida-privada-gestao-ti&psig=AOvVaw3fbggTYuE_jZ5M_E98QbHj&ust=1620610206402000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCIDRv9K5u_ACFQAAAAAdAAAAABAS)


### ¿Qué es la nube?

La **nube** es un término que se utiliza para describir una red mundial de servidores, cada uno con una función única. La nube no es una entidad física, sino una red enorme de servidores remotos de todo el mundo que están conectados para funcionar como un único ecosistema. Estos servidores están diseñados para almacenar y administrar datos, ejecutar aplicaciones o entregar contenido o servicios, como streaming de vídeos, correo web, software de ofimática o medios sociales.

Existen 3 tipos **publicas**, **privadas** e **híbridas**.

**PRIVADAS**, este tipo de nube son comunes en empresas cuya infraestructura se localiza directamente en la compañia, ellos mismos dan el mantenimiento necesario y la programan manualmente, aunque también es posible que sea alojada por terceros pero manteniendo el uso exclusivo de esta.

**PUBLICAS**, aunque su nombre puede conotar una idea de que cualquiera puede acceder a ella realmente este no es el caso, sino se le conoce como publica ya que no es de uso exclusivo para nadie, por el contrario, los servicios de este tipo de nube se ofrecen a través de la red de internet pública y están disponibles para cualquiera que quiera comprarlos.

Dentro de la nube pública, existen diferentes **modelos de servicios en la nube**, los cuales definen los diferentes niveles de responsabilidad compartida que tienen el proveedor de nube y su respectivo inquilino. Estos se dividen en tres, y son:
- **IaaS**, o Infrastructure as a Service. Este modelo de servicio en la nube es el que más se parece a los servidores físicos, ya que en él un proovedor de servicios en la nube es quien mantiene actualizado el hardware, pero tanto el mantenimiento del sistema operativo como la configuración de red es responsabilidad únicamente del inquilino de la nube.
- **PaaS**, o Platform as a Service. Este modelo es en pocas palabras un host. En él, el proovedor de servicios en la nube administra las máquinas virtuales y los recursos de red, mientras que el inquilino de nube implementa sus aplicaciones en el entorno de hospedaje.
- **Saas**, o Software as a Service. En este modelo de servicio en la nube, el proveedor de servicios en la nube es quien administra todos los aspectos del entorno de la aplicación, como las máquinas virtuales, los recursos de red, el almacenamiento de datos y las aplicaciones; el inquilino de nube solo necesita proporcionar sus datos a la aplicación administrada por su proveedor de servicios en la nube. 

La imagen que se muestra a continuación explica de manera más concisa los servicios que puede ejecutar cada uno de los modelos explicados.

![image](https://docs.microsoft.com/es-mx/learn/azure-fundamentals/fundamental-azure-concepts/media/iaas-paas-saas.png)

**HÍBRIDA**, Este entorno informático combina una nube pública y una nube privada, lo que permite compartir datos y aplicaciones entre ellas. Puede referirse a cualquier combinación de soluciones de nube que funcionen conjuntamente en entornos locales y externos para proporcionar servicios de informática de nube a una empresa. Los proveedores de servicios de nube pueden proporcionar opciones tanto de nube privada como pública en un servicio de nube híbrida, y la nube privada se puede alojar de forma local o externa.

La informática en la nube cuenta con varias **ventajas** en comparación con los entornos físicos, entre ellas:
- **Alta disponibilidad.** La experiencia que se ofrece al usuario al momento de utilizar aplicaciones en la nube es continua, por lo que no hay un tiempo de inactividad perceptible que pueda afectar en los parámetros del contrato de nivel de servicio elegido.
- **Escalabilidad.** Aumenta la capacidad de proceso para adaptarse a las necesidades de rendimiento. Existen dos maneras de lograr esto: mediante la escalabilidad vertical o la escalabilidad horizontal (o ambas). La escalabilidad vertical hace crecer el hardware utilizando uno más potente, como un disco duro una memoria; es fácil de implementar y no implica riesgos para el software. Por otro lado, la escalabilidad horizontal utiliza varios servidores gestionados desde un servidor primario que permita que trabajen en conjunto como un todo. Este método soporta la alta disponibilidad y un crecimiento ilimitado debido a que es posible la adición de nuevos servidores si son requeridos.
- **Elasticidad.** Las aplicaciones basadas en la nube permiten el escalado automático para disponer de los recursos necesarios.
- **Agilidad.** Es posible la configuración de los recursos ofrecidos en la nube según las necesidades del usuario.
- **Distribución geográfica.** Permite un rendimiento óptimo para los usuarios independientemente de su ubicación.
- **Recuperación ante desastres.** En caso de desastre o de error, los datos en la nube se encuentran respaldados por lo que no existe el riesgo de pérdida de información.
- **Modelo basado en el consumo.** El usuario se encarga únicamente de cubrir los gastos relacionados con los recursos que utilizó, sin necesidad de pagar cuotas por adelantado o por recursos que ya no le son útiles.
- **Gastos operativos.** Se refiere a la inversión en servicios y productos que se facturan al instante o a medida con la que se usa; es un modelo basado en el consumo. Tiene grandes ventajas sobre los gastos de capital pues al contrario de estos, no requiere de infraestructura, mantenimiento o soporte técnico continuo, lo que se refleja en el beneficio neto.



### ¿Qué es Azure?
![image](https://user-images.githubusercontent.com/83620226/117554874-f83aa600-b01f-11eb-9315-9957456b4a80.png)
Azure es una nube pública de pago por uso que te permite compilar, implementar y administrar rápidamente aplicaciones en una red global de datacenters (centros de datos) de Microsoft.

La plataforma Azure está compuesta por más de 200 productos y servicios en la nube diseñados para ayudarle a dar vida a nuevas soluciones que permitan resolver las dificultades actuales y crear el futuro. Cree, ejecute y administre aplicaciones en varias nubes, en el entorno local y en el perímetro, con las herramientas y los marcos que prefiera.

En el portal Microsoft Azure existen diferentes servicios de infraestructura y de plataforma para que puedas “montar” los servicios que necesites de manera sencilla, con unos cuántos clics. En tu portal dispones de un botón [New +] y a partir de ahí, sólo tienes que elegir la región de los datacenter donde estará tu servicio y, a continuación, el tipo de servicio con sus características. Por ejemplo, en el caso de querer crear una máquina virtual podrías seleccionar el tipo de máquina como Windows Server 2016 Datacenter, a continuación, rellenar todos sus características (espacio de disco, RAM…). En este proceso de creación, se define un nombre de usuario y contraseña específica para poder iniciar sesión en esta máquina virtual.

![image](https://user-images.githubusercontent.com/83620226/117554969-ba8a4d00-b020-11eb-871a-fcc5613f5757.png)


Entre los servicios, dispones de infraestructuras (IaaS: almacenamiento, redes, máquinas virtuales…) y plataformas (PaaS: bases de datos de alta disponibilidad SQL, CMS para desarrollo de web, backend para aplicaciones móviles…). Son compatibles con todo tipo de tecnología: bases de datos Oracle, Linux, php, iOs, My SQL, Android, php…

Estos servicios están garantizados con una disponibilidad del 99.99%, y en caso de fallo en disponibilidad superior, Microsoft se compromete a indemnizar por los daños. Además, cuenta con todas las certificaciones en materia seguridad y protección de datos. 

**¿Cuándo usar Microsoft Azure?**

1. En el despliegue de una solución en la que el incremento de uso va a ser exponencial (o desconocido) y no podemos definir con garantías el pico de demanda máximo.
2. Cuando sabes que la demanda del servicio va a fluctuar en el tiempo.
3. En entornos de desarrollo o pruebas que posteriormente podrían seguirse utilizando o no, o que pueden “apagarse” puntualmente y después volverse a activar.
