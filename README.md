# <div align=center> Angular App + Tekton </div>

### <div align=center> [![Apache License](https://img.shields.io/badge/license-Apache%202.0-orange.svg?style=flat-square)](http://www.apache.org/licenses/LICENSE-2.0) [![build](https://img.shields.io/badge/build-passing-color.svg?style=flat-square)](https://cloud.ibm.com/devops/pipelines/tekton/29187ff0-1e93-44fe-9846-a4a707df0978?env_id=ibm:yp:us-south) <div/>

Repositorio con una aplicación angular configurada para su despliegue por medio de Tekton en un cluster de Kubernetes en IBM Cloud

Tekton permite independizar la aplicación de un servidor de integración como anteriormente se usaba, por ejemplo, Jenkins. Esto gracias a su modelo **Pipeline as Code** permitiendo personalizar todos los aspectos del despliegue, asimismo permite el seguimiento de las versiones de nuestra configuración con Git o Mercurial.

## Configuración

Para configurar Tekton en nuestra aplicación solo es necesario 3 archivos yaml, ubicados en la carpeta .tekton, y los scripts que se van a ejecutar en nuestro pipeline.

![tekton folder](https://raw.githubusercontent.com/MGsus/Tekton_Front/master/.github/.tekton.png) ![scripts folder](https://raw.githubusercontent.com/MGsus/Tekton_Front/master/.github/scripts.png)

## Autores

[Jesús Orlando Montoya Mejía](https://github.com/MGsus) <br/>
Equipo IBM Cloud Tech Sales Colombia

**Copyright 2020 IBM**
