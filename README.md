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

A Dockerrun.aws.json file is an Elastic Beanstalk–specific JSON file that describes how to deploy a set of Docker containers as an Elastic Beanstalk application.<br> 
You can use a Dockerrun.aws.json v2 file for an ECS managed Docker environment.

Dockerrun.aws.json describes the containers to deploy to each container instance (Amazon EC2 instance that hosts Docker containers) in the environment as well as the data volumes to create on the host instance for the containers to mount.

A Dockerrun.aws.json file can be used on its own or zipped up with additional source code in a single archive. Source code that is archived with a Dockerrun.aws.json is deployed to Amazon EC2 container instances and accessible in the /var/app/current/ directory. Use the volumes section of the config to provide file volumes for the Docker containers running on the host instance.<br>
Use the mountPoints section of the embedded container definitions to map these volumes to mount points that applications on the Docker containers can use.<br></br>

<div align="center">
  <a href="https://github.com/franchialan/aws-webapp-templates/tree/main/templates" rel="templates">
    <h3> 📝 Templates
  </div>