# ppracticafinalkube
Necesitamos desplegar una aplicación fullstack en Kubernetes utilizando Minikube 
como cluster. Necesitamos crear los servicios y deployments necesarios para poder 
desplegar nuestra aplicación inicialmente con una única versión en el front y una 
única versión en el back. Y también necesitamos configurar nuestro ingress para 
que cuando el usuario utilice la direccion /frontend vaya al front y si pone 
/backend vaya al backend.
 
Al menos debe haber una réplica
 
Imagen de docker a elegir. No tiene porque ser de backend y frontend, lo ideal es que sea pequeña, que no pese mucho, y que nos permita practicar.  TIENE QUE TENER VERSIONES, al menos 2.
 
Siguiente apartado es:
Conseguir versionar el backend y el frontend. De forma que, tengamos los deployments y servicios necesarios para cada versión y el ingress particione segun version de esta manera:
 
/frontend/v1 => Debe ir a la versión 1 del frontend
/frontend/v2 => Debe ir a la versión 2 del frontend
/backend/v1 => Debe ir a la versión 1 del frontend
/backend/v2 => Debe ir a la versión 2 del backend
 
 
Al menos debe haber una réplica
 
