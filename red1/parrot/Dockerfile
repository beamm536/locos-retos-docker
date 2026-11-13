# Usamos la imagen oficial de Parrot Security OS
FROM parrotsec/security:latest

# Actualizar e instalar herramientas
RUN apt-get update && apt-get install -y \
    metasploit-framework \
    nmap \
    burpsuite \
    wireshark \
    john \
    hydra \
    git \
    vim \
    wget

# Establecer el punto de entrada
CMD ["/bin/bash"]