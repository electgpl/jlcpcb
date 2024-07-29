# Switch PMOS High-Side

El circuito presentado utiliza un transistor PMOS SE9435 configurado como un interruptor en el lado de alta (high side) para controlar la alimentación de una carga. Este tipo de configuración es útil cuando se necesita conectar y desconectar la carga desde el positivo de la fuente de alimentación. En este diseño, el SE9435 se controla mediante un transistor NPN 2N2222 en el lado de baja (low side). El PCB se ha diseñado en un formato flexible (FPC) para facilitar la disipación de calor y mantener un tamaño compacto.

El funcionamiento del circuito es el siguiente: cuando se aplica una señal de control al transistor 2N2222, éste entra en conducción, permitiendo que la corriente fluya a través de su colector hacia tierra. Esto crea un voltaje de caída en la resistencia de gate del SE9435, haciendo que su voltaje de gate-source (Vgs) sea negativo y poniendo el PMOS en conducción. Como resultado, la corriente fluye desde la fuente de alimentación, a través del SE9435, hacia la carga, energizándola.

El uso de un PCB flexible en este diseño proporciona varias ventajas, especialmente en aplicaciones donde el espacio y la gestión térmica son críticos. La flexibilidad del PCB permite una mejor integración en dispositivos compactos y móviles, mientras que su capacidad de disipar el calor de manera eficiente ayuda a mantener los componentes dentro de sus límites de temperatura operativa segura. Además, la capacidad de adaptar la forma del PCB flexible facilita su uso en aplicaciones donde los PCBs rígidos serían imprácticos o imposibles de montar.

## Screenshots

![](https://raw.githubusercontent.com/electgpl/jlcpcb/main/switchpmos/Captura%20de%20pantalla%202024-07-29%20103144.png)
![](https://github.com/electgpl/jlcpcb/blob/main/switchpmos/Sin%20nombre.png)
![](https://github.com/electgpl/jlcpcb/blob/main/switchpmos/0x0.png)
