# Repositório para ensinar e aprender o básico sobre WireMock

O WireMock é uma ferramenta HTTP mock server, onde entrega requisições estáticas para diferentes end-points.

Para executar o serviço pode-se utilizar o Gitbash com o comando `sh ./server-standalone/start.sh` ou então o comando java `java -cp "server-standalone/wiremock-standalone-2.11.0.jar;server-standalone/wiremock-body-transformer-1.1.6.jar" com.github.tomakehurst.wiremock.standalone.WireMockServerRunner --verbose --https-port=8081 --extensions com.opentable.extension.BodyTransformer`.

O serviço está configurado para ser executado nas portas 8080 (http) e 8081 (https).