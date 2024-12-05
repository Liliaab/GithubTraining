curl -sO http://54.183.230.46:8080/jnlpJars/agent.jar
java -jar agent.jar -url http://54.183.230.46:8080/ -secret a0a85e5d0ec13d463310f65830739013a5fc0dc7abec0b7f93e25f8fc7371daa -name "test-node" -webSocket -workDir "/home/jenkins"
