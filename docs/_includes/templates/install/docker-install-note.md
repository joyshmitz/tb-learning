{% capture docker_install_note %}
**Note:** Make sure you have completed the following steps:

1. Docker is installed and running on your system
2. You have permissions to run Docker commands (added to docker group or running as root/sudo)
3. Docker Compose is installed if you plan to use the docker-compose method

For detailed Docker installation instructions, please refer to the [official Docker documentation](https://docs.docker.com/get-docker/).
{% endcapture %}
{{ docker_install_note | markdownify | safe }}
