# Secure Application/Container Deployment phase.

**1. Verifying Application Signature**

Verify the application signature to ensure that it has not been tampered with or altered during deployment.



**2. Verifying Container Signature (in case of container deployment)**

In case of container deployment, verify both the container signature and the application signature to ensure that they have not been tampered with or altered during deployment.


**3. Deployment of Application/Container**

Deploy the application or container, ensuring that it has been properly verified and signed.


**Consumes:**

* **Application Build/Container**: The application build or container is consumed to deploy the application or container.
* **Digital Signatures**: A digital signature is used to verify the integrity and authenticity of the application build or container.

**Produces:**

* **Deployment of Application/Container**: The application or container is successfully deployed to a production environment.
* **Monitoring Results**: Monitoring results are provided to ensure that the application or container is running as expected.
