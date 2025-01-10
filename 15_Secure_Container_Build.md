# Secure Container Build

**1. Scanning Containers for Vulnerabilities**

Scan the containers after they're built for vulnerabilities using a tool such as:

* **Vulnerability Scanner**: A tool that scans the container image for known vulnerabilities and provides recommendations for remediation.
* **Container Security Tool**: A tool that scans the container image for security vulnerabilities and provides recommendations for remediation.


**2. Creating Custom Images (Distroless) as Base with Monitoring Tools**

Create a custom image (ideally distroless) as base that includes monitoring tools.


**3. Only Allowing Signed Base Images to be Used to Build On Top Of**

Only allow signed base images to be used to build on top of, ensuring that the container is secure and tamper-proof.


**4. Signing the Container**

Sign the container using a digital signature, ensuring that it is authentic and trustworthy.

**Consumes:**

* **Application Build**: The application build is used to create the container image.
* **Custom Image**: The custom image (ideally distroless) as base with monitoring tools.

**Produces:**

* **Application Container**: A secure and tamper-proof container that includes monitoring tools and digital signatures.
