FROM perl:5.18.2
MAINTAINER Peter Martini <PeterCMartini@GMail.com>

WORKDIR /root

# YAML is a "soft" dependency, but its apparently needed for even the default CMD below
RUN curl -L http://cpanmin.us | perl - YAML

# Install Dancer itself
RUN curl -L http://cpanmin.us | perl - Dancer

EXPOSE 3000

# If no arguments passed, create a HelloWorld
CMD dancer -a Hello::World; cd Hello-World; ./bin/app.pl
