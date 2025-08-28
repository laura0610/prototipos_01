# prototipos_01

# INTEGRANTES 

* lalquichides

* nagarzon

* pauladgarcia

* surango
-------------------------------------

# Laura Valentina Alquichides Barrera

## Contexto problemática

Un familiar tiene un negocio en el cual se realizan domicilios, sin embargo, cuando ya se realizaron los domicilios a un lugar específico, y la persona que realiza los domicilios vuelve a el negocio después de realizar un domicilio, puede volver a salir otro pedido cerca al lugar donde se había realizado el último. Considero que se podría crear una aplicación en la cual, conectando las ubicaciones más cercanas, también integrando un mapa para que le indique a cuál lugar debe ir primero e indicándole en que dirección debería dirigirse. Para que las entregas se realizan de manera correcta y rápida, sin tener que volver a ir a la misma ubicación para el siguiente pedido. Teniendo en cuenta que para volver a realizar los domicilios se vuelva a tener en cuenta la ubicación para realizar una entrega del domicilio de manera óptima.

## Árbol de problemas

graph TD

%% Niveles
subgraph Efectos
    E1[Perdida de tiempo]
    E2[Demora en la entrega]
    E3[Reiteración en el lugar de entrega]
    E4[Clientes disgustados]
    E5[Disgustos en los clientes]
    E6[Menos pedidos]
end

subgraph Problema Principal
    P[Gestión inadecuada de los lugares para los domicilios]
end

subgraph Causas
    C1[Incorrecta organización de la entrega de domicilios]
    C2[Nuevos domicilios cercanos al mismo lugar]
    C1A[No organizar los lugares de entrega cercanos]
    C1B[No implementar la automatización]
    C2A[No tener una buena planificación]
    C2B[Priorizar la entrega antes de la organización]
end

%% Relaciones Causa -> Problema
C1 --> P
C2 --> P

%% Subcausas
C1A --> C1
C1B --> C1
C2A --> C2
C2B --> C2

%% Problema -> Efectos
P --> E1
P --> E2
E1 --> E3
E1 --> E5
E2 --> E4
E2 --> E6

## prompt


