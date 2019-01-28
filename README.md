# Instruction to run it

First you need to make sure that you have `centos7` docker image. If you don't, run:
`docker pull centos:centos7`

Then you need to run the image:
`docker build --tag="localhost/shibboleth-idp" .`

and run it:
`docker run -p 8080:8080 localhost/shibboleth-idp`

Then visit `localhost:8080/idp`
