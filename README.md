# Site configuration

## About

This is a version controlled site configuration. It is used to manage the configuration of applications and services that are deployed to the site. Managed using git, the configuration is released to hosts using a CI/CD pipeline.

## Structure

The site configuration is structured on a application basis. Each application has its own directory in the root of the repository. If an application has multiple services or components or deployments, they are managed in subdirectories of the application directory.

## Site map

The following is a list of applications and services managed by this repository:

- Traefik
- Blocky DNS
  - NS1
  - NS2

