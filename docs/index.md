# AI Software Template

This application, oda, is created from an AI Software Template. These software templates create a new source code repository as well as a new GitOps deployment repository.

The chosen sample source applicable is included in the source code repository.

## Sample Source Application

A DEtection TRansformer (DETR) model streamlit application. Upload an image to identify and locate objects in the image.

## Repositories

The source code for your application can be found in [https://github.com/jrichter-rhtap/oda124 ](https://github.com/jrichter-rhtap/oda124 ).
 
The GitOps repository, which contains the Kubernetes manifests for the application can be found in 
[https://github.com/jrichter-rhtap/oda124-gitops ](https://github.com/jrichter-rhtap/oda124-gitops ). 

## Application namespaces 

The default application is found in the namespace: **`rhdh-app`**. Applications can be deployed into their own unique namespace or multiple software templates can generate numerous applications into the same namespace.