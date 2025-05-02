# Nexus Helm Chart

[![Release](https://img.shields.io/github/v/release/Scalified/helm-nexus?style=flat-square)](https://github.com/Scalified/helm-nexus/releases/latest)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/scalified-nexus)](https://artifacthub.io/packages/helm/scalified-nexus/nexus)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Scalified/helm-nexus/blob/master/LICENSE)

A Helm chart for Sonatype Nexus Repository Manager

## Requirements

* [Helm 3+](https://helm.sh)

## Installation

```bash
helm repo add scalified-nexus https://scalified.github.io/helm-nexus/
helm upgrade --install nexus scalified-nexus/nexus --create-namespace --namespace nexus
```

## Removal

```bash
helm delete nexus --namespace nexus
```

## License

```
MIT License

Copyright (c) 2025 Scalified

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Scalified Links

* [Scalified](http://www.scalified.com)
* [Scalified Official Facebook Page](https://www.facebook.com/scalified)
* <a href="mailto:info@scalified.com?subject=[Helm Nexus Chart]: Proposals And Suggestions">Scalified Support</a>
