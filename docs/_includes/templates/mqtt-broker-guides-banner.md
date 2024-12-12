{% assign currentGuide = currentGuide | default: "none" %}
{% assign docsPrefix = "mqtt-broker/" %}

{% if currentGuide != "InstallationGuides" %}
* [Installation Guides](/thingsboard-learning/docs/mqtt-broker/install/installation-options/) - learn how to setup TBMQ
{% endif %}

{% if currentGuide != "ConnectingClients" %}
* [Connecting MQTT Clients](/thingsboard-learning/docs/mqtt-broker/user-guide/connect-mqtt-client/) - learn how to connect your MQTT clients
{% endif %}

{% if currentGuide != "Configuration" %}
* [Configuration Guide](/thingsboard-learning/docs/mqtt-broker/user-guide/configuration/) - learn about TBMQ configuration options
{% endif %}

{% if currentGuide != "Monitoring" %}
* [Monitoring Guide](/thingsboard-learning/docs/mqtt-broker/user-guide/monitoring/) - learn how to monitor your TBMQ instance
{% endif %}

{% if currentGuide != "Troubleshooting" %}
* [Troubleshooting Guide](/thingsboard-learning/docs/mqtt-broker/troubleshooting/) - learn how to investigate and solve common issues
{% endif %}
