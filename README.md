# Sonatype Nexus Repository Manager Helm Chart

[![Release](https://img.shields.io/github/v/release/Scalified/helm-nexus?style=flat-square)](https://github.com/Scalified/helm-nexus/releases/latest)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/scalified-nexus)](https://artifacthub.io/packages/helm/scalified-nexus/nexus)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Scalified/helm-nexus/blob/master/LICENSE)

## Requirements

* [Helm 3+](https://helm.sh)

## Installation

```bash
helm repo add scalified-nexus https://scalified.github.io/helm-nexus/
helm upgrade --install nexus scalified-nexus/nexus --create-namespace --namespace nexus
```

# Troubleshooting

## AccessDeniedException on nexus-data Mount

If you encounter an AccessDeniedException when accessing the `/nexus-data` directory, ensure it has the correct ownership:

```bash
chown -R 200:200 /nexus-data
```

---

**Made with ❤️ by [Scalified](http://www.scalified.com)**
