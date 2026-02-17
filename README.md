## Sobre el proyecto

Este proyecto provisiona una infraestructura en AWS, simulando un entorno productivo mediante Terraform. Incluye una VPC, public subnet, una instancia EC2 a modo de laboratorio con nginx y SSH configurado, web estatica
utilizando un bucket de S3 y CloudFront para distribuir la pagina de manera segura. La infraestructura viene soportada por un backend de terraform remoto, utilizando S3 y DynamoDB.

El despliegue de la infraestructura esta automatizado mediante GitHub Actions (CI/CD), usando autentificacion OIDC (sin utilizar credenciales de AWS).

## Requisitos

## Despliegue

## Tecnologias utilizadas

    <li><a href="#roadmap">Terraform >= 1.14</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
