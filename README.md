# Tarjeta electrónica multipropósito

🚧 **Proyecto en desarrollo — esquemático preliminar pendiente de revisión y validación.**

## Descripción

Proyecto personal de diseño electrónico realizado en EasyEDA.
La propuesta reúne alimentación, control con microcontrolador,
accionamiento de un relevador, comunicación inalámbrica y entrada
para sensor en una tarjeta.

Este repositorio documenta el avance y las futuras revisiones del diseño.

## Bloques del diseño propuesto

- Entrada de alimentación AC con fusible y filtrado.
- Conversión AC a 5 V mediante módulo IRM-20-5.
- Regulación de 5 V a 3.3 V mediante AMS1117-3.3.
- Control con módulo ESP32-S3-WROOM-1-N16R8 (16 MB de Flash y 8 MB de PSRAM), con botones RESET y BOOT.
- Etapa de relevador con optoacoplador PC817 y transistor 2N2222.
- Comunicación RF de 433 MHz mediante módulo HC-12.
- Interfaz UART.
- Entrada para sensor y botón de prueba.

## Estado actual

Se cuenta con una versión preliminar del esquemático.
Los circuitos y componentes están sujetos a revisión y cambios.

La publicación de este diseño no implica que su funcionamiento,
protecciones o seguridad eléctrica hayan sido validados.

## Documentación

[Consultar esquemático preliminar](./esquematico-preliminar.pdf)

## Próximos pasos

- Revisar conexiones, componentes y dimensionamiento.
- Continuar el desarrollo del diseño de PCB.
- Desarrollar el firmware.
- Realizar pruebas y documentar resultados.

## Autor

José Rodolfo Molina Rodríguez  
Ingeniería en Electrónica — Instrumentación y Control
