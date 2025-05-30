## ✅ Preguntas sobre Nube, AWS y Arquitectura Distribuida

### 1. ¿Hypervision es de qué proveedor?
- a. Microsoft ✅  
- b. Amazon  
- c. Oracle  
- d. Google  

✅ **Explicación:** Hyper-V es el hipervisor desarrollado por **Microsoft** para ejecutar máquinas virtuales.

---

### 2. ¿Qué es Terraform?
- a. Un sistema operativo basado en contenedores.  
- b. Una base de datos relacional en la nube.  
- c. Una herramienta de infraestructura como código para aprovisionar recursos ✅  
- d. Un lenguaje de programación específico para la nube.  

✅ **Explicación:** Terraform es una herramienta de **Infraestructura como Código (IaC)** creada por **HashiCorp** para aprovisionar y gestionar infraestructura en múltiples proveedores de nube.

---

### 3. ¿Qué es una VPC?
- a. Una red privada dentro de una nube pública que proporciona control sobre entornos virtuales ✅  
- b. Un protocolo de seguridad para comunicaciones cifradas.  
- c. Un sistema operativo ligero.  
- d. Una máquina virtual especializada en bases de datos.  

✅ **Explicación:** VPC significa **Virtual Private Cloud** y permite crear entornos de red virtuales aislados dentro de la nube pública.

---

### 4. Verdadero o falso: En un entorno multi-tenant los recursos de la nube se comparten, pero cada usuario tiene acceso exclusivo a sus datos y servicios.
- Verdadero ✅  
- Falso  

✅ **Explicación:** En entornos multi-tenant, los recursos físicos son compartidos, pero cada usuario tiene acceso exclusivo y aislado a sus propios datos y servicios.

---

### 5. ¿Qué es la orquestación de contenedores y cuál es su beneficio principal?
- a. Un método para mejorar la seguridad de los contenedores.  
- b. No sabe/No responde  
- c. Un proceso manual de configuración de contenedores  
- d. La automatización de la implementación, gestión, escalado y redes de contenedores, mejorando la eficiencia operativa y la coherencia del despliegue ✅  
- e. Una técnica para reducir el tamaño de los contenedores.  

✅ **Explicación:** La orquestación de contenedores automatiza la gestión de contenedores en producción, utilizando herramientas como Kubernetes o Docker Swarm.

---

### 6. Verdadero o falso: Las funciones de AWS Lambda pueden ejecutarse en respuesta a eventos, como cambios en datos en un bucket de S3 o actualizaciones en una tabla de DynamoDB.
- Verdadero ✅  
- Falso  

✅ **Explicación:** AWS Lambda permite ejecutar código en respuesta a eventos de otros servicios de AWS como S3, DynamoDB, API Gateway, etc., sin necesidad de administrar servidores.

---

### 7. ¿Cuál de las siguientes estrategias es la más adecuada para implementar un sistema de alta disponibilidad y tolerancia a fallos en una arquitectura de nube distribuida?
- a. No sabe/No responde  
- b. Utilizar una sola región con una arquitectura monolítica para simplificar la gestión y reducir costos.  
- c. Implementar réplicas de datos en múltiples regiones geográficas y usar balanceadores de carga para distribuir el tráfico entre servidores ✅  
- d. Configurar servidores redundantes en una única zona de disponibilidad para reducir la latencia.  
- e. Utilizar bases de datos locales en cada servidor para mejorar el rendimiento de las consultas.  

✅ **Explicación:** Para lograr alta disponibilidad y tolerancia a fallos, es clave tener réplicas geográficamente distribuidas y balanceadores de carga para asegurar continuidad operativa.

---

### 8. ¿Qué es alta disponibilidad y tolerancia a fallos?
- a. Alta disponibilidad es la capacidad de un sistema de estar funcionando casi todo el tiempo.  
- b. Tolerancia a fallos es la capacidad de seguir operando aun si una parte del sistema falla.  
- c. Ambas ✅  
- d. Ninguna  

✅ **Explicación:** Alta disponibilidad minimiza el tiempo fuera de servicio, y tolerancia a fallos garantiza que el sistema siga funcionando incluso ante errores internos.
