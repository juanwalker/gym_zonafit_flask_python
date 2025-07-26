Para ejecutar este proyecto sse requiere:

* instalar mysql en docker (Instrucciones por chatGPT). Crear la tabla clientes en la base de datos zona_fit_db:

CREATE TABLE `cliente` (
  `id` int NOT NULL AUTO_INCREMENT,
  `nombre` varchar(100) DEFAULT NULL,
  `apellido` varchar(100) DEFAULT NULL,
  `membresia` varchar(100) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=4 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

* instalar flask y flask-wtf usando pip. pip install flask, pip install flask-wtf 

