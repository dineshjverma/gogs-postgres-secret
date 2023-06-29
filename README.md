# gogs-postgres-secret

**Deployed Multi-Tier Application with Gogs and Postgres in Kubernetes**

This Git repository contains the deployment configuration and related files for a multi-tier application deployed in a Kubernetes cluster. The application utilizes Gogs, a self-hosted Git service, and Postgres, a powerful open-source relational database management system.

The deployment is organized into two separate Kubernetes namespaces: **"frontend"** and **"backend".** The **"frontend"** namespace hosts the **Gogs** service **A painless self-hosted Git service**, while the **"backend"** namespace contains the **Postgres** as **Database**.

To securely connect Gogs with the Postgres backend, the repository includes a Kubernetes Secret configuration that stores the necessary connection details. The Secret includes the following information:

- User: **root**
- Password: **alexa**
- Database: **unnati**

By leveraging these configurations, the application ensures a reliable and scalable architecture. Developers can collaborate and manage their code using Gogs, while Postgres handles the storage and retrieval of application data.

This Git repository serves as a central source for managing the deployment and any related updates or modifications to the multi-tier application. Developers can easily clone, fork, or contribute to the repository to enhance the application's functionality or make improvements to the deployment configuration.

Whether you are a developer seeking to understand the deployment architecture or an administrator responsible for managing the Kubernetes cluster, this repository provides the necessary resources and configurations to deploy and maintain the multi-tier application effectively.
