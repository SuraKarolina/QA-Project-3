# DevOps Final Project

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project:

The main objective of this project is to apply the knowledge gained from the course to deploy the recommended open source application:

#### Front-end: https://github.com/spring-petclinic/spring-petclinic-angular<br />
#### Back-end: https://github.com/spring-petclinic/spring-petclinic-rest

The team will need to plan, design and implement a solution for automating the development workflows and deployments of the application.


<!-- PROJECT PLANNING -->
## Project planning

To achieve our goal, we have set our sprint planning meeting on every Friday for three weeks to discuss any issues we might have and set tasks for every team member to prepare for the next sprint.

On the final week, we have decided to use common cloud technology and the group has split into two sub-teams to work on their allocated tasks, i.e. Terraform and Kubernetes. We have daily startup meeting to see the progress of the tasks. While it went well with the configuration of Kubernetes, some unforseen issues happened with the configuration of Terraform. The team has digged deep into the literature and the configuration issues have been resolved. For the automation deployment, the original plan was to use Ansible, however the discovery of the same functionality of Terraform make our project progress faster.

<!-- CI Pipeline -->
## CI Pipeline

#### Below are the tools we use for our project.
* Kanban Board: Trello
* Version Control: Github
* Cloud service: Amazon Web Services (AWS)
* CD server: Jenkins
* Deployment: Kubernetes and Jenkins
* Infrastructure management: Terraform

![](https://github.com/WaledSalem/sigma-project/blob/Documentation/Documents/CI_pipline.png)

### Jenkins
Jenkins' ability to integrate with Plugins make it a powerful continuous delivery tool. It works with Github and allows the builds to complete in the background automatically.

### Kubernetes
Kubernetes is an open-source system for automating deployment, scaling and containerised applications management. It is chosen because of its powerful nature, it allows to scale without increasing human resource and it is flexible to run. It won't disappeared forever even if it was deleted accidentally.

### Terraform
Terraform is an open-source tool and its easy to reuse and maintain module structure encouraged us to employ it for creating VMs and install all necessary dependencies. 

<!-- Risk assessment -->
## Risk assessment

![](https://github.com/WaledSalem/sigma-project/blob/Documentation/risk_assessment.jpg)

<!-- Running cost estimation -->
## Running cost estimation

![](https://github.com/WaledSalem/sigma-project/blob/Documentation/Cost%20estimate.jpg)

<!-- CONTRIBUTORS -->
## Contributors

1. Karolina Sura
2. Serin Jeon
3. Waled Salem
4. Sabina Ku
5. Irene Chung
