# bachelor-thesis-report

“Layers 2 and 3 vulnerability detection tool in the scope of a corporate network”

This document includes an extensive research work on multiple network protocols. Thanks to the information collected, a tool is created to make the layers 2 and 3 pentesting of the corporate network easier for the administrator. All of this through a user-friendly GUI. The main points of this project are:

•	Analysis of most common protocols used in corporate networks and identification of those which can be potencially dangerous: ARP, STP, CDP, DTP, VTP, RIP, OSPF, DHCP and HSRP.

•	Description of the reasons why these protocols can be a threat to the security of the corporate network.

•	Set the guidelines for the assurance of the corporate network.

•	Implementation of a tool which detects a bad configuration or a possible network attack through any of the previously mentioned protocols. To do this, a sniffer is created with the aid of Scapy tool.

•	In case of detection of any risk in the network, in order to speed up the response, the tool sends immediately to the administrator an SNMP trap to the server IP indicated in the GUI.

•	Lastly, the tool includes a user-friendly GUI (created with Qt) which allows any user with basic knowledge of network protocols to run the program and understand the information returned by it. This information helps the administrator to know in more detail where the problem is located, thus making easier its correction. 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

“Herramienta de detección de vulnerabilidades en capas 2 y 3 en el ámbito de una red corporativa”

Este documento recoge una extensa labor de investigación de múltiples protocolos de red. Gracias a la información recabada, se crea una herramienta que facilita al administrador la realización del pentesting de las capas 2 y 3 de una red corporativa. Todo ello a través de una interfaz gráfica intuitiva y fácil de utiilizar. Los principales puntos de este proyecto son:
 
•	Análisis de los protocolos de uso más frecuente en redes corporativas, identificando aquellos que puedan ser potencialmente peligrosos: ARP, STP, CDP, DTP, VTP, RIP, OSPF, DHCP y HSRP. 

•	Descripción de los motivos por los cuales estos protocolos pueden resultar una amenaza para la seguridad de la red corporativa. 

•	Determinación de pautas para que la red corporativa deje de ser vulnerable. 

•	Implementación de una herramienta que detecte una mala configuración o un posible ataque a la red mediante alguno de los protocolos mencionados previamente. Para ello, se crea un analizador de paquetes con ayuda de la herramienta Scapy.

•	Con el fin de agilizar la respuesta en caso de detectar alguna anomalía, la herramienta avisa al administrador de la red de forma inmediata mediante el envío de una notificación del protocolo SNMP a la dirección IP del servidor indicada en la interfaz gráfica. 

•	Por último, la herramienta incluye una interfaz (creada con Qt) sencilla de utilizar que permite que cualquier usuario con conocimientos básicos a cerca de protocolos de red pueda ejecutar el programa y comprender la información devuelta por el mismo. Esta información ayuda al administrador a conocer de forma más detallada donde se localiza el problema, agilizando así su respuesta y facilitando su corrección. 
