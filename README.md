# docker-dancer

Repository for build scripts for dancer. This installs module
[YAML](https://metacpan.org/pod/YAML) and [Dancer](http://perldancer.org/).
Port 3000 is exposed to connect to a dancer web application. A simple
"Hello-World" application is started unless another command is given.

There are different tags for different versions of Perl,
corresponding to the tags in library/perl.

## Usage

1. Pull the repository from [docker hub](https://registry.hub.docker.com/u/petermartini/docker-dancer/):

   `docker pull petermartini/docker-dancer`

2. Start the container, exposing the web application at local port 3000:

   `docker run -d -p 3000:3000 petermartini/docker-dancer`

## See also

* <http://perldancer.org/>
* <https://www.docker.com/>
* <http://robn.io/docker-perl/>

