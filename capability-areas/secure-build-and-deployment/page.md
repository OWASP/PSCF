---
title: Secure Build & Deployment
nextjs:
  metadata:
    title: Secure Build & Deployment
    description: A description of the Secure Build & Deployment capability area.
---

{% video src="https://www.youtube.com/embed/ksCcMQ3xEds?si=5ggsu-Lm9ie-ZuDa" /%}

## Area Overview

Secure Build & Deployment is a vital component in the product development pipeline, ensuring that the security measures ingrained during the design and implementation phases are accurately translated into the final product. This practice involves rigorous procedures and checks to maintain the integrity and security of the product from the build environment to its deployment in a live setting. It's about creating a fortified bridge between the development of secure code and its operation in the real world, ensuring that this transition is seamless, secure, and devoid of vulnerabilities that can be exploited.

These capabilities are pivotal for automating and reinforcing security measures throughout the build and deployment processes. By integrating robust security practices into these stages, organizations can safeguard their products against configuration errors, unauthorized access, and other security threats that can compromise the product post-deployment.

### Benefits

* **Continuous Security Assurance:** Secure Build & Deployment practices ensure that security is an ongoing priority, not just at certain stages, providing continuous protection throughout the product's lifecycle.
* **Streamlined Deployment Processes:** Integrating security into the build and deployment processes helps in automating security checks and controls, making these processes more efficient and less prone to human error.
* **Early Detection of Vulnerabilities:** Regular and automated security assessments during the build and deployment stages allow for the early detection and remediation of vulnerabilities, reducing potential exploitation risks.
* **Confidence in Product Integrity:** Ensures that the product deployed in the production environment mirrors the security and integrity of the product conceived during the design phase, fostering confidence among stakeholders and users.

## Dependency Management [PSCF&#8209;SBD&#8209;DM]

_The capability to evaluate and select secure software dependencies used by your product_

{% video src="https://www.youtube.com/embed/BSQMZJBTaGc?si=gWmrDWCgcJj_r4R4" /%}

### Capability Overview

Dependency management is crucial in modern software development due to the extensive use of third-party libraries and frameworks. Properly managing these dependencies is vital for maintaining the security and stability of software products, as vulnerabilities in these external components can be easily exploited.

### Compliance Requirement

{% compliance capability_id="PSCF-SBD-DM" / %}

### Accountability

{% accountability capability_id="PSCF-SBD-DM" / %}

### Responsibility

{% responsibility capability_id="PSCF-SBD-DM" / %}

## Build Process [PSCF&#8209;SBD&#8209;BP]

_The capability to securely assemble product artefacts from their codebases and dependencies_

{% video src="https://www.youtube.com/embed/FuVi71PzYjw?si=jbBdhb-NmDG15Z4-" /%}

### Capability Overview

The build process in software development is a critical stage where source code is compiled into executable programs. A secure and efficient build process is essential for ensuring that the software is free from vulnerabilities and defects, and is ready for deployment.

### Compliance Requirement

{% compliance capability_id="PSCF-SBD-BP" / %}

### Accountability

{% accountability capability_id="PSCF-SBD-BP" / %}

### Responsibility

{% responsibility capability_id="PSCF-SBD-BP" / %}

## Artifact Integrity [PSCF&#8209;SBD&#8209;AI]

_The capability to use product artefacts from trusted sources and evaluate any that change_

{% video src="https://www.youtube.com/embed/cavvIhxua7g?si=xNstMvVTrQ-Y998E" /%}

### Capability Overview

Artifact integrity is critical in ensuring that the software products developed are authentic and have not been tampered with. This is essential for maintaining trust in the software delivery process and for the security of the end product.

This capability involves verifying the integrity of software artifacts from creation to deployment. It includes implementing measures to ensure that the artifacts are not altered or corrupted during the software development lifecycle. Ensuring artifact integrity is crucial for preventing the introduction of malicious code or vulnerabilities into the software.

### Compliance Requirement

{% compliance capability_id="PSCF-SBD-AI" / %}

### Accountability

{% accountability capability_id="PSCF-SBD-AI" / %}

### Responsibility

{% responsibility capability_id="PSCF-SBD-AI" / %}

## Data Integrity [PSCF&#8209;SBD&#8209;DI]

_The capability to use data in your product that is obtained from and stored in trusted sources and evaluate any changes_

{% video src="https://www.youtube.com/embed/WEvcK80i2NY?si=ZLjO8VJrf85Eox-p" /%}

### Capability Overview

Data integrity is paramount in ensuring the accuracy, reliability, and consistency of data throughout its lifecycle. In the context of software development, it is crucial for maintaining the trustworthiness of the data used and produced by applications.

This capability focuses on ensuring that data is not altered in an unauthorized or unexpected manner. It encompasses strategies to protect data from corruption, unauthorized access, and errors. Effective data integrity practices are essential for complying with data protection regulations and for maintaining the overall quality of software products.

### Compliance Requirement

{% compliance capability_id="PSCF-SBD-DI" / %}

### Accountability

{% accountability capability_id="PSCF-SBD-DI" / %}

### Responsibility

{% responsibility capability_id="PSCF-SBD-DI" / %}

## Secrets Management [PSCF&#8209;SBD&#8209;SM]

_The capability to restrict access to product secrets to only when required by those people and systems that need them_

{% video src="https://www.youtube.com/embed/CNnJIOSCmyE?si=IgUnRe7nsbbmBdue" /%}

### Capability Overview

Secrets management is a critical aspect of software security, involving the safe handling of sensitive information like passwords, keys, and tokens. Proper management of these secrets is essential to protect against data breaches and unauthorized access.

This capability involves creating, storing, accessing, and disposing of secrets in a secure manner. It requires a comprehensive approach to ensure that secrets are not exposed to unauthorized individuals or systems and are used only for their intended purposes. Effective secrets management is a fundamental part of securing software systems and protecting sensitive information.

### Compliance Requirement

{% compliance capability_id="PSCF-SBD-SM" / %}

### Accountability

{% accountability capability_id="PSCF-SBD-SM" / %}

### Responsibility

{% responsibility capability_id="PSCF-SBD-SM" / %}

## Deployment Process [PSCF&#8209;SBD&#8209;DP]

_The capability to securely deploy a product and its components from a known set of artefacts_

{% video src="https://www.youtube.com/embed/vUZ5K27Mo7E?si=XgYOujKuvjDFyiXz" /%}

### Capability Overview

The deployment process is a critical stage in the software development lifecycle, where software is released to production environments. A secure and efficient deployment process is essential to ensure the reliability and availability of software products.

The deployment process involves the steps taken to move software from development to production environments. It requires careful planning and execution to ensure that deployments are performed without errors, disruptions, or security breaches. Effective deployment processes enable rapid and safe delivery of software updates and new features to users.

### Compliance Requirement

{% compliance capability_id="PSCF-SBD-DP" / %}

### Accountability

{% accountability capability_id="PSCF-SBD-DP" / %}

### Responsibility

{% responsibility capability_id="PSCF-SBD-DP" / %}
