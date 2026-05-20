# Keycloak Config CLI Builder

Simple GitHub Actions workflow for building custom versions of [keycloak-config-cli](https://github.com/adorsys/keycloak-config-cli) directly from selected Git tags.

The workflow:
- clones the upstream repository
- checks out a selected tag
- builds the project using Maven
- uploads generated JAR files as GitHub Actions artifacts

# Usage

## Run build manually

1. Fork repository
2. Open the **Actions** tab in repository
3. Select: Build Keycloak Config CLI
4. Wait
5. Download Artifact
6. Enjoy ;)
