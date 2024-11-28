# PROYECTO3_VSP_20241128
PROYECTO3 ENTREGABLE DIA 28 11 2024

Proyecto

Descripcion: Consta basicamente de 6 microservicios o unidades de negocio (accountservice, creditservice, customer, transactionservice, apiregistry, gateway).

Objetos:

UML: -BorradorSistemaAPPProyecto1.drawio (modelo general del sistema draft) -DiagramaSecuenciaAPPBanco_GENERALSISTEMA.drawio -DiagramaSecuenciaAPPBanco_PORMICROSERVICIO.drawio -UMLAPPBanco.drawio -DIAGRAMADESECUENCIAAPPBANCARIO_GENERALSISTEMA.png -DIAGRAMASECUENCIAAPPBANCARIO_PORMICROSERVICIO.png

contratos (open api diseño de app a nivel de interface rest): -accounts.yml -credits.yml -customers.yml -transactions.yml

App (codigo fuente): -accountservice -creditservice -customer -transactionservice -apiregistry (eurekaserver) - gateway

Avances por dia:

Primer avance (Dia 11-11-2024) -Diagrama UML -Diagrama de Secuencia

Segundo avance (Dia 12-11-2024) - Unidades de servicio accountservice, creditservice, customer. -Mejoras Diagramas UML y Secuencia. -Contratos no integrados de Open Api para las unidades de negocio.

Tercer avance (Dia 13-11-2024) - Se agrega la Unidad de servicio transactionservice, se agregan las funcionalidades obligatorias requeridas, se finalizan el diagrama UML y los diagramas de secuencia, se agrega LockBack y comentarios a uno de los proyectos.

Cuarto dia avance (Dia 14-11-2024) - Se generan los contraton open api en limpio y se hacen ultimos ajustes a los proyectos.

Avance PROYECTO2, funconalidades añadidas, eureka server (apiregystry), docker compose, checkstyle, llamadas entre microservicios con feignclient.

Avance PROYECTO3, se agregam pruebas unitarias de la capa controlador con mockito para los mircoservicios -accountservice -creditservice -customer -transactionservice , se ajustan funcionalidades


Otras consideraciones adicionales:

NO hay orquestacion de servicios, deberia realizarse con Kafka o con algun sistema de orquestacion. Para las funcionalidades requeridas se presentan metodos que se van a ir desarrollando. CRUD completo por microservicio. Consideradas las reglas de negocio. Considerados metodos adicionales como retiro, pago, consulta de movimientos etc. Queeda pendiente la integracion de Open api con las capas de servicio de cada microservicio, se integrara para la siguiente presentacion. Se usa mongodb, database perservice LockBack log (acccuntservice) y otras caracteristicas.
