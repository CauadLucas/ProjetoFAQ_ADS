# ProjetoFAQ_ADS
Projeto voltado para a criação de um sistema de satisfação dos alunos do curso de Análise e Desenvolvimento de Sistemas da Unifaat

# Ambiente

O projeto conta com 03 dockers diferentes, sendo 01 docker de Node.js e os outros de MongoDB e Postgres, respectivamente. Eles são conectados entre si através de uma rede (network). Com o docker-compose.yml, é possível iniciar e controlar esses ambientes

# Como executá-lo

É preciso criar um Dockerfile com a "receita" da imagem e, para criar a imagem, é necessário usar o comando docker build -t

Já o docker-compose orquestra todos os contâineres e, para executá-lo, é preciso usar o comando docker-compose up -d
