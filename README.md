----- Mutant Detector API -----

Este proyecto permite detectar si un humano es mutante basado en su secuencia de ADN. El proyecto se divide en tres niveles:

Nivel 1: Implementa un método isMutant(String[] dna) que analiza secuencias de ADN para detectar mutantes.

Nivel 2: Expone un endpoint REST /mutant/ que permite verificar secuencias de ADN.

Nivel 3: Agrega persistencia en base de datos y estadísticas de ADN verificadas, con soporte para alta concurrencia.





----- Descripción -----

Este proyecto está diseñado para determinar si una persona es mutante en función de su ADN, mediante una API REST en Java Spring Boot. La API permite:

Verificar si un ADN es mutante.

Registrar cada ADN verificado en una base de datos H2.

Obtener estadísticas sobre las verificaciones realizadas.
