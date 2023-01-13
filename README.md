<p align="center">
  <a href="https://docs.aws.amazon.com/pt_br/elastic-beanstalk/index.html" rel="aws-elastic-beanstalk">
 <img width=200px height=200px src="beanstalk_logo.png" alt="Project logo"></a>
</p>
<div align="center">

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<div align="center"> 
    <h1>AWS Elastic Beanstalk Templates</h1>
</div>

<br>

Um arquivo Dockerrun.aws.json é um arquivo JSON específico do Elastic Beanstalk que descreve como implantar um conjunto de contêineres do Docker como uma aplicação do Elastic Beanstalk. Você pode usar um arquivo Dockerrun.aws.json v2 para um ambiente do Docker gerenciado pelo ECS. <br>
Dockerrun.aws.json descreve os contêineres a serem implantados em cada instância de contêiner (instância do Amazon EC2 que hospeda os contêineres do Docker) no ambiente, bem como os volumes de dados a serem criados na instância do host para os contêineres que devem ser montados.<br>
Um arquivo Dockerrun.aws.json pode ser usado sozinho ou zipado com o código-fonte adicional em um único arquivo. O código-fonte arquivado com um Dockerrun.aws.json é implantado nas instâncias do contêiner do Amazon EC2 e fica acessível no diretório /var/app/current/. <br>
Use a volumes seção do config para fornecer volumes de arquivos para os contêineres do Docker em execução na instância do host. Use a mountPoints seção de definições de contêineres incorporados para mapear esses volumes para pontos de montagem que os aplicativos em contêineres do Docker podem usar.
