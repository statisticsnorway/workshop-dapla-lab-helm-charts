# minimalist-web-notepad

![Version: 0.0.2](https://img.shields.io/badge/Version-0.0.2-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square)

WORKSHOP - The ultimate notepad for DaplaLab.

## Source Code

* <https://github.com/statisticsnorway/workshop-dapla-lab-helm-charts>

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| https://statisticsnorway.github.io/dapla-lab-helm-charts-services | library-chart | 1.0.1 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| service.image.pullPolicy | string | `"IfNotPresent"` |  |
| service.image.version | string | `"jdreinhardt/minimalist-web-notepad:latest"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)