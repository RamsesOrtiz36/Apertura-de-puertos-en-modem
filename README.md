# Apertura-de-puertos-del-modem
Pasos para apertura de los puertos del modem y poder usar la computadora como broker online
Cada modem tiene su propia forma de ingresar a configuración, por lo que se recomienda ir a la pagina del probeedor de servicios de internet contratado para ver si es posible acceder a  ella.

En algunos casos se puede acceder colocando la dirección IP del modem en el navegador, abrira la ventana de acceso en la que pide la contraseña y nombre, estos valores pueden ser el nombre del proveedor y la contraseña de wifi original.

En las configuraciones de busca las redes LAN o dispositivos conectados mostrando una lista de nombres de equipos y la direcciones Ip asignadas a cada una.

![Apertura de puertos1]()

Pueden ser muy variadas las ventanas de interaccion con el usuario, para esto en cada una se busca la configuración de internet o wifi, hasta encontrar alguna opcion de Range, DMZ o Remap, se aconseja no modificar las opciones pre establecidas y en especifico no usar el modo DMZ = Zona desmilitarizada

![Apertura de puertos2]()

* Se busca agregar una regla para acceso de puertos con rango de 1880 a 1880 uando protocols TCP y UDP o ambos
* Inrterfaz NAT sin modificar
* IP remota vacia.
* Es posible que se tenga que agregar una regla en el firewall del antivirus usado. 
* No se recomienda desactivar el firewall. 
* No se recomienda desactivar el antivirus.

La apertura de puertos de modem nos sirve para que nuestra computadora funcione como servidor, así podrá proveer un servicio por internet sin nuestra intervención, pero se debe tener cuidado para no dejar desprotegido al equipo.

![Apertura de puertos3]()
