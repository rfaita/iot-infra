FROM rabbitmq:management

RUN rabbitmq-plugins enable --offline rabbitmq_mqtt
RUN rabbitmqctl add_user mqtt-sender <CHANGEIT_PASS> &&\
    rabbitmqctl set_permissions -p / mqtt-sender ".*" ".*" "" &&\
    rabbitmqctl set_topic_permissions -p / mqtt-sender "amq.topic" ".*" ""

EXPOSE 15671 15672 1883
