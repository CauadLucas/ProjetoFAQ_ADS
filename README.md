# ProjetoFAQ_ADS
Projeto voltado para a criação de um sistema de satisfação dos alunos do curso de Análise e Desenvolvimento de Sistemas da Unifaat

# Ambiente e Estrutura

O projeto conta com alguns componentes essenciais:

- **Containers Docker**: Temos 03 dockers na nossa aplicação, sendo eles o docker de PostgresSQL que é o nosso banco relacional para armazenar os dados estruturados, o MongoDB que é o nosso banco NoSQL para armazenar os dados escaláveis, flexíveis e o Node.js que é o nosso servidor que executa a aplicação

Além dos dockers, também temos o código fonte com os arquivos `package.json` e (`app.js`) que gerenciam essas dependências

# Como executá-lo

**Primeiro, clone o seu repositório remoto na sua máquina:**

```bash
   git clone <repository-url>
```

**Em seguida, é preciso criar a imagem dentro do arquivo Dockerfile:**

```
docker build -t <nome_da_imagem>
```

**Dentro do diretório raiz, precisamos executar o docker-compose, responsável pela orquestração desses containers:**

```
docker-compose up -d 
```

**Após executar os containers, você pode entrar em `http://localhost:3000` para acessar a aplicação**
