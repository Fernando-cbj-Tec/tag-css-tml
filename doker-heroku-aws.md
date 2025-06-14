# Docker, Heroku e AWS mais utilizados

## Docker

### Comandos Básicos

  * `docker build -t nome_da_imagem .`: constrói uma imagem a partir do Dockerfile.
  * `docker run -d -p porta_host:porta_container nome_da_imagem`: executa um container a partir da imagem.
  * `docker start nome_do_container`: inicia um container parado.
  * `docker stop nome_do_container`: para um container em execução.
  * `docker rm nome_do_container`: remove um container.
  * `docker rmi nome_da_imagem`: remove uma imagem.

### Gerenciamento de Containers

  * `docker ps -a`: lista todos os containers (executando e parados).
  * `docker ps`: lista containers em execução.
  * `docker exec -it nome_do_container /bin/bash`: entra no terminal do container.
  * `docker logs nome_do_container`: exibe os logs do container.
  * `docker stats`: mostra estatísticas de recursos em tempo real.
  * `docker top nome_do_container`: exibe processos em execução dentro do container.

### Gerenciamento de Imagens

  * `docker images`: lista todas as imagens disponíveis localmente.
  * `docker pull nome_da_imagem`: baixa uma imagem do Docker Hub.
  * `docker push nome_da_imagem`: envia uma imagem para o Docker Hub.
  * `docker tag nome_da_imagem:tag nome_do_registro:tag`: marca a imagem para o registro de contêiner.

### Docker Compose

  * `docker-compose up`: inicia os serviços definidos no docker-compose.yml.
  * `docker-compose down`: para e remove os serviços, redes e volumes.
  * `docker-compose build`: constrói ou rebuild as imagens dos serviços.
  * `docker-compose exec serviço comando`: executa um comando em um serviço.
  * `docker-compose logs serviço`: exibe os logs de um serviço.

### Dockerfile

  * `FROM imagem_base`: define a imagem base para o container.
  * `RUN comando`: executa um comando durante a construção da imagem.
  * `COPY arquivo_origem arquivo_destino`: copia arquivos/diretórios para o container.
  * `ADD arquivo_origem arquivo_destino`: similar ao COPY, mas também suporta arquivos remotos e descompactação automática.
  * `ENV variavel valor`: define variáveis de ambiente.
  * `EXPOSE porta`: indica que o container escutará em uma porta.
  * `CMD ["comando"]`: define o comando padrão a ser executado no container.

## Heroku

### Comandos Básicos

  * `heroku login`: faz login na conta do Heroku.
  * `heroku create nome_do_app`: cria um novo aplicativo no Heroku.
  * `heroku destroy nome_do_app`: exclui um aplicativo do Heroku.
  * `heroku apps`: lista todos os aplicativos associados à conta.
  * `heroku config:set variavel=valor --app nome_do_app`: define variáveis de configuração.
  * `heroku config:unset variavel --app nome_do_app`: remove uma variável de configuração.
  * `heroku config --app nome_do_app`: exibe variáveis de configuração.

### Implantação e Gerenciamento

  * `git push heroku main`: envia o código para o Heroku (após configurar o repositório).
  * `heroku deploy:container --app nome_do_app`: implanta usando Docker.
  * `heroku restart --app nome_do_app`: reinicia os dynos do aplicativo.
  * `heroku ps --app nome_do_app`: exibe os processos em execução.
  * `heroku logs --tail --app nome_do_app`: segue os logs do aplicativo.
  * `heroku run comando --app nome_do_app`: executa um comando no ambiente do Heroku.

### Banco de Dados e Add-ons

  * `heroku addons:create add-on_nome --app nome_do_app`: adiciona um add-on.
  * `heroku addons:destroy add-on_nome --app nome_do_app`: remove um add-on.
  * `heroku pg:backups capture --app nome_do_app`: cria um backup do banco de dados PostgreSQL.
  * `heroku pg:backups restore url_do_backup --app nome_do_app`: restaura um backup do banco de dados.
  * `heroku pg --app nome_do_app`: exibe informações do banco de dados PostgreSQL.

### Gerenciamento de Pipeline

  * `heroku pipelines:create pipeline_nome --app nome_do_app`: cria um pipeline.
  * `heroku pipelines:add pipeline_nome --app nome_do_app`: adiciona um aplicativo a um pipeline.
  * `heroku pipelines:promote --app nome_do_app`: promove uma versão de um pipeline para o ambiente de produção.
  * `heroku pipelines:list`: lista todos os pipelines associados à conta.

## AWS

### AWS EC2 (Elastic Compute Cloud)

  * `aws ec2 describe-instances`: lista informações sobre instâncias EC2.
  * `aws ec2 run-instances --image-id ami-id --instance-type tipo --count 1 --key-name nome_chave`: inicia uma nova instância EC2.
  * `aws ec2 stop-instances --instance-ids id_da_instância`: para uma instância EC2.
  * `aws ec2 terminate-instances --instance-ids id_da_instância`: encerra uma instância EC2.
  * `aws ec2 create-key-pair --key-name nome_chave`: cria um par de chaves SSH.
  * `aws ec2 describe-key-pairs`: lista pares de chaves disponíveis.

### AWS S3 (Simple Storage Service)

  * `aws s3 mb s3://nome_do_bucket`: cria um bucket S3.
  * `aws s3 rb s3://nome_do_bucket`: remove um bucket S3.
  * `aws s3 cp arquivo_local s3://nome_do_bucket/caminho`: carrega arquivo para S3.
  * `aws s3 sync diretório_local s3://nome_do_bucket/caminho`: sincroniza diretório com S3.
  * `aws s3 ls s3://nome_do_bucket`: lista objetos no bucket.
  * `aws s3 rm s3://nome_do_bucket/caminho/para/arquivo`: remove arquivo do S3.

### AWS RDS (Relational Database Service)

  * `aws rds create-db-instance --db-instance-identifier identificador --db-instance-class classe --engine engine --master-username usuario --master-user-password senha`: cria uma instância de banco de dados RDS.
  * `aws rds delete-db-instance --db-instance-identifier identificador`: exclui uma instância de banco de dados RDS.
  * `aws rds describe-db-instances`: lista informações sobre instâncias RDS.
  * `aws rds start-db-instance --db-instance-identifier identificador`: inicia uma instância RDS.
  * `aws rds stop-db-instance --db-instance-identifier identificador`: para uma instância RDS.

### AWS Lambda

  * `aws lambda create-function --function-name nome --runtime runtime --role arn_da_role --handler handler --zip-file arquivo_zip`: cria uma função Lambda.
  * `aws lambda update-function-code --function-name nome --zip-file arquivo_zip`: atualiza o código de uma função Lambda.
  * `aws lambda delete-function --function-name nome`: exclui uma função Lambda.
  * `aws lambda invoke --function-name nome arquivo_saida`: invoca uma função Lambda.
  * `aws lambda list-functions`: lista todas as funções Lambda.

### AWS ECR (Elastic Container Registry)

  * `aws ecr create-repository --repository-name nome_repositorio`: cria um repositório ECR.
  * `aws ecr delete-repository --repository-name nome_repositorio`: exclui um repositório ECR.
  * `aws ecr get-login-password | docker login --username AWS --password-stdin aws_account_id.dkr.ecr.region.amazonaws.com`: autentica com o ECR.
  * `docker push aws_account_id.dkr.ecr.region.amazonaws.com/nome_repositorio:tag`: envia uma imagem para o ECR.

### AWS VPC (Virtual Private Cloud)

  * `aws vpc create-vpc --cidr-block cidr_block`: cria uma nova VPC.
  * `aws vpc delete-vpc --vpc-id vpc-id`: exclui uma VPC.
  * `aws vpc describe-vpcs`: lista informações sobre VPCs.
  * `aws ec2 create-security-group --group-name nome_grupo --description descrição --vpc-id vpc-id`: cria um grupo de segurança.
  * `aws ec2 authorize-security-group-ingress --group-id grupo-id --protocol protocol --port porta --cidr cidr_block`: adiciona regra de entrada a um grupo de segurança.

### AWS IAM (Identity and Access Management)

  * `aws iam create-user --user-name nome_usuario`: cria um usuário IAM.
  * `aws iam delete-user --user-name nome_usuario`: exclui um usuário IAM.
  * `aws iam attach-user-policy --user-name nome_usuario --policy-arn arn_da_politica`: associa uma política a um usuário.
  * `aws iam detach-user-policy --user-name nome_usuario --policy-arn arn_da_politica`: desassocia uma política de um usuário.
  * `aws iam list-users`: lista todos os usuários IAM.

### AWS Route 53

  * `aws route53 create-hosted-zone --name nome_domain --caller-reference referencia`: cria uma zona hospedada no Route 53.
  * `aws route53 change-resource-record-sets --hosted-zone-id id_zona --change-batch arquivo_json`: altera registros de recursos.
  * `aws route53 list-hosted-zones`: lista todas as zonas hospedadas.
  * `aws route53 delete-hosted-zone --id id_zona`: exclui uma zona hospedada.

### AWS CloudFront

  * `aws cloudfront create-distribution --origin-domain-name nome_domain --default-root-object arquivo`: cria uma distribuição CloudFront.
  * `aws cloudfront delete-distribution --id id_distribuicao`: exclui uma distribuição CloudFront.
  * `aws cloudfront list-distributions`: lista todas as distribuições CloudFront.
  * `aws cloudfront invalidate --distribution-id id_distribuicao --paths caminho`: invalida objetos no CloudFront.