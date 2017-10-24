FROM jboss/wildfly
# Download the minecraft server and put in /tmp
# https://s3.amazonaws.com/Minecraft.Download/versions/1.12.2/minecraft_server.1.12.2.jar

EXPOSE 9990 25565
ADD /tmp/minecraft_server.1.12.2.jar /opt/jboss/wildfly/standalone/deployments/
