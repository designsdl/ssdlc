# Secure Application Build

**1. Producing Build and Build Artifacts**

Produce a secure build of the application, including all necessary build artifacts such as:

* **Build Artifact**: A signed Software Bill of Materials (SBOM) that contains information about the components used in the build.
* **Custom Reports**: Additional reports that provide detailed information about the build process, such as dependencies and security vulnerabilities.


**2. Signing the Builds and Artifacts**

Sign the builds and artifacts using a digital signature, ensuring that they are authentic and trustworthy.

* **Digital Signature**: A unique identifier that ensures the integrity and authenticity of the build and its artifacts.
* **Signature Algorithm**: Uses a secure algorithm such as SHA-256 to create the digital signature.



**3. Uploading to Central Repository**

Upload the signed builds and artifacts to a central repository, such as:

* **Repository**: A centralized location that stores and manages all builds and their associated artifacts.
* **Authentication**: Ensures that only authorized users can access and manage the repository.


**Consumes:**

* **Code**: The application code used to build the application.
* **Build Tool**: A tool such as Maven or Gradle that manages the build process.

**Produces:**

* **Signed Build**: A secure build of the application, including all necessary build artifacts.
* **Signed Build Artifacts**: Signed artifacts associated with the build, such as the SBOM and custom reports.
