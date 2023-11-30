# Getting started

This repository is a sample application for users following the getting started guide at https://docs.docker.com/get-started/.

The application is based on the application from the getting started tutorial at https://github.com/docker/getting-started

Login Command used to bypass 

Error: Cannot perform an interactive login from a non TTY device

cat ~/getting-started-app/pass.txt | docker login --username magnusjw --password-stdin
