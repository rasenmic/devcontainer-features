# devcontainer-features
A collection of features for vscode devcontainers, not (yet) available in https://github.com/devcontainers/features.

The features are based on the official feature template https://github.com/devcontainers/feature-template.

## Quarkus feature
Installs a version of quarkus-cli in devcontainer and also the "Quarkus Tools for Visual Studio Code" (redhat.vscode-quarkus).
```json
{
  "image": "mcr.microsoft.com/devcontainers/base:ubuntu",

  "features": {
    "java": "22.2.r17-grl",
    "maven": "3.8",
    "ghcr.io/rasenmic/devcontainer-features/quarkus:0": {
      "version" : "latest" 
    }
  } 
}
```
