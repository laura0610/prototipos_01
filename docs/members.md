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

Para mejorar la movilidad en Bogotá, es importante implementar soluciones integrales que aborden la creciente cantidad de vehículos particulares, causada en parte por medidas como el pico y placa que incentivan la compra de un segundo automóvil, y por la falta de una cultura ciudadana orientada al uso compartido del transporte. Además, se debe replantear la infraestructura vial, ya que muchas vías fueron diseñadas de forma deficiente: son estrechas, con pocas alternativas, y presentan fallas como huecos y poca señalización. Además, es crucial fortalecer el sistema de transporte público, que actualmente es ineficiente por los retrasos, la inseguridad, y la escasa articulación entre el SITP, TransMilenio y los medios de transporte alternativos como la bicicleta. Una solución debe considerar un rediseño urbano sostenible, mejoras estructurales en el transporte público y campañas de concientización para fomentar la movilidad compartida.

## Soluciones tecnologícas

* Plataforma de movilidad inteligente para empresas y ciudadanos: Desarrollar una aplicación o sistemas web en el cual incluya las opciones de movilidad como lo son las bicicletas, SITP, Transmilenio y rutas peatonales, optimizados por IA y datos en tiempo real. El cual este dirigido para las empresas que buscan optimizar la movilidad de sus empleados y para los ciudadanos que buscan rutas eficaces sin tráfico.
Se implementarían funciones como rutas multimodales, alerta sobre el trafico en tiempo real, puntos por usar transporte sostenible, integración con pico y placa y horarios con horarios flexibles.

* Software de automatización para pequeños negocios: Desarrollar una plataforma de gestión digital (ERP ligero) para pequeños negocios como panaderías, papelerías, ferreterías que cuentan con soluciones costosas como SAP o Zoho.
Dirigido para los comercios pequeños o informales y profesiones independientes como consultores, contadores, entre otros. Incluiría funciones como el control de inventario y facturación electrónica, módulo de reservas para los negocios, informes automáticos para tomas de decisiones y una aplicación móvil simple e intuitiva.

* Consultora de soluciones tecnológicas personalizadas: Ofrece servicios de desarrollo a la medida para pequeñas y medianas empresas que
requieren soluciones tecnológicas específicas, como por ejemplos la automatización de procesos, apps internas, integración de APIs o migración a la nube.
Esto estaría dirigido para PYMEs, instituciones educativas, ONG, y startups, también para las empresas que no tiene un equipo de desarrollo propio. además, los posibles servicios que tendría serán desarrollo web/app personalizada, integración de sistemas como los son las ventas online con facturación electrónica, automatización de RPA (Robotic Process Automation) y ciberseguridad y mantenimiento de infraestructura digital.

## Consultora de soluciones tecnológicas personalizadas

La idea que más me llamo la atención fue la de consultora de doluciones tecnologicas personalizadas, porque esta dririgo para los diferentes ámbitos, se puede diseñar de la manera en que el usuario comprenda las funciones que se pueden realizar, manteniendo de manera segura la información que se administre, siendo la solcuion que me parece más adecuada de acuerdo con los distintos requisitios que las empresas necesitan, como lo son las ventas onnline, ya que la tecnología es importatnte integrarla en los entornos que existe, como en la automatización de los procesos.
