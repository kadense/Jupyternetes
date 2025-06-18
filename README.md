# Jupyternetes
![Jupyternetes Logo](./img/jupyternetes-inverted.png)

## What is Jupyternetes
upyternetes is an alternative to Jupyterhub's Kubespawner built on the operator model and designed to simplify configuration.

This was proposed as an amendment to the existing Kubespawner. However, due to concerns regarding upgrade paths, it was decided that this would be a separate project managed by Kadense Limited at least until the initial version is completed. The aim is to eventually integrate it into the wider Project Jupyter once it meets expectations.

Jupyternetes effectively breaks down the current hub in Kubernetes into multiple services, utilizing the Kubernetes operator design pattern and implementing a more refined security policy for these services.

[Full documentation of Jupyternetes can be found on the Kadense website](https://kadense.io/docs/Products/Jupyternetes/Introduction)