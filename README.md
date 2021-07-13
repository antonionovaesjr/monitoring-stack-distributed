# monitoring-stack-distributed

# ElasticSearch com APM e Kibana

### Pré-requisito:
1. Docker instalado
2. Docker-Compose instalado

### Como usar:
1. faça o git clone deste repo da branch master
2. dentro do diretório docker execute 'docker-compose up -d'
3. use o comando 'docker-compose logs -f' e acompanhe o setup
4. acesso o IP do kibana seguido de 5601, caso seja seu próprio PC/Notebook acesso por http://localhost:5601
5. Usuário e senha padrão: elastic/PassW0rd
6. Verifique se as portas 5601, 9200, 8200, 5044, 3000 estão liberadas, caso não, faça
