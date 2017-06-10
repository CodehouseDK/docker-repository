# docker-repository

Fork of Azure/ACR "custom domain" scripts for running SSL and custom domain in front of a Azure Container Registry.

The nginx config is modified to allow larger layers to be pushed (Windows images tend to be large)

This proxy is running on [https://registry.codehouse.com](https://registry.codehouse.com)

## Known issues

- You need to create ACR manually and use the hostname as backend url in this ARM template.
- When deploying it will seem to just hang and never finish, but it does so just let it be.
