FROM ubuntu
MAINTAINER santos <qlgasntos@tip.edu.ph>

# Skip prompts
ARG DEBIAN_FRONTEND=noninteractive

# Update packages
RUN apt update; apt dist-upgrade -y

# Install packages
RUN apt install -y apache2 vim-nox

# Set entrypoint
ENTRYPOINT apache2ctl -D FOREGROUND
