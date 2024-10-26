##Como rodar o projeto
- BUILDAR O AMBIENTE
	./mvnw -T1C -q --batch-mode -DskipTests --also-make -pl zipkin-server clean package

- RODAR O SERVIDOR ZIPKIN
	java -jar ./zipkin-server/target/zipkin-server-*exec.jar

- VERSAO SLIM DO SERVIDOR 
	java -jar ./zipkin-server/target/zipkin-server-*slim.jar

- RODAR O FRONT 
	npm start
