# Company Choice — TrackFlow

## Empresa elegida

**TrackFlow**

## ¿Por qué elegí esta empresa?

Elegí Track flow, debido a que me motiva todo el mundo logístico y los desafios que estos conllevan. tengo muchos clientes del rubro, he implementado proyectos a empresas logísticas y hay ciertos problemas comunes en todos ellos que creo puedo dar una gran solucion debido a mi background.

En particular me interesa mucho como construir una infraestructura completa, y en este caso enfrentar el desafio de una empresa multinacional me abrirá mas la mente a como enfrentar este tipo de empresas multitenant.

Poder plantearme soluciones, automatizaciones y poder darle una propuesta de valor unica es lo que me parece atractivo de seguir mi proyecto con Trackflow.

## Departamentos cuyos problemas me parecen más interesantes

1. Operaciones de almacén: me parece un gran desafío el poder construir una infraestructura que soporte un multitenant, y que sea la base de toda la información que nutre las demás áreas.
2. Ultima milla: En este caso en particular, no tengo conocimiento de como contruir aplicaciones que puedan consumir informacion en tiempo real constante, que pueda dar respuestas concretas y actualizadas a los clientes y al equipo de trabajo. esto ayudara a la toma de decisiones en momentos no contemplado por ejemplo en el caso de accidentes.

## Reto de automatización / IA que más quiero construir

**Reto concreto: el motor de selección de transportista de Última Milla.**

Hoy en TrackFlow la asignación de transportista por envío es manual y no existen datos históricos de rendimiento (ni tasa de entrega a tiempo, ni incidencias por ruta, ni costo por kg). El briefing pide un motor que recomiende la opción óptima según destino, peso y urgencia, y ese es el reto que más quiero construir.

Lo que más me motiva es que es la base que puede alimentar al resto de las áreas. Si logro alinear la recepción de los paquetes con los clientes, coordinar la mejor ruta, elegir al transportista indicado y hacer seguimiento y control en todo momento, además de un posventa eficiente, aparecen muchos espacios donde la IA puede tomar decisiones autónomas. Así la experiencia del cliente se siente cercana y eficaz.

## My AI Agent Idea

<!-- Sin códeigo: un párrafo corto o bullets. -->

Agente de selección de Transportista,

**Qué haría el agente:**,
Toma todos los pedidos agendados, los ordena por fecha de entrega, genera una ruta optima y elige al transportista considerando criterios de costo, prioridad, categoria del cliente y ranking del transportista.
**Qué información necesita:**,
Necesita conocer las ordenes de despacho, el mapa de la ciudad, informaciondel cliente, historial transportista.
**Qué produce o dispara:**,
Dispara una agenda personalizada y los documentos de ordenes de despacho para cada transportista.
