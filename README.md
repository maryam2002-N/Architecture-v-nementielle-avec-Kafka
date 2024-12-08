# Architecture Événementielle avec Kafka - Activité Pratique

Ce projet met en œuvre une architecture événementielle utilisant Apache Kafka et Spring Cloud Streams, avec un traitement des données en temps réel. L'application inclut des services Kafka pour la production, la consommation, la fourniture de données, et l'analyse en temps réel.

Installation de Kafka
    
    Téléchargez Kafka depuis le site officiel Apache Kafka.
    Démarrez les services suivants :
        Zookeeper : bin/zookeeper-server-start.sh config/zookeeper.properties
        Broker Kafka : bin/kafka-server-start.sh config/server.properties
    Testez Kafka avec :
        Producteur Console : bin/kafka-console-producer.sh --topic [NOM_DU_TOPIC] --bootstrap-server localhost:9092
        Consommateur Console : bin/kafka-console-consumer.sh --topic [NOM_DU_TOPIC] --from-beginning --bootstrap-server localhost:9092