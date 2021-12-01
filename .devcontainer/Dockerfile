FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

# Defining default Java and Maven version 
ARG JAVA_VERSION="17.0.0.fx-zulu"

# Installing Java and Maven, removing some unnecessary SDKMAN files 
RUN bash -c "yes | sdk install java $JAVA_VERSION"
