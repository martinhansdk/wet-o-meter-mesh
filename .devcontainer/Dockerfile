# Derive from Nordic's image, SDK version 2.5
FROM nordicplayground/nrfconnect-sdk:v2.7-branch
# Update the distro
RUN apt-get -y update
# Install git and GDB
RUN apt-get -y install git gdb-multiarch
# Create the workspace folder
RUN mkdir /workdir/workspace
