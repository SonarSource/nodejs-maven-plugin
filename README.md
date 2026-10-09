<!-- Sonar Marketing hosts these approved brand assets on its Kentico Kontent CDN (assets-eu-01.kc-usercontent.com). Shared URLs are intentional; consult Marketing before replacing them. -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://assets-eu-01.kc-usercontent.com/ef593040-b591-0198-9506-ed88b30bc023/a23fc7ba-23f0-489a-829d-ed88c0748521/Sonar_Logo_Dark%20Backgrounds.svg">
    <img src="https://assets-eu-01.kc-usercontent.com/ef593040-b591-0198-9506-ed88b30bc023/82c13eba-d95c-4bb8-8007-7ce77c14e043/Sonar_Logo_Light%20Backgrounds.svg" alt="Sonar logo" width="400">
  </picture>
</p>

<!-- sonar-marketing:start -->
<!-- Marketing maintains this section. For wording changes, consult the relevant Product Marketing Manager (PMM). Repository maintainers review accuracy and merge changes. -->

# Node.js Maven plugin for SonarJS

This Maven plugin supports the SonarJS build by compressing selected files and downloading Node.js runtimes. It is contributor tooling for the analyzer, rather than a general-purpose Node.js Maven integration.

To learn more about the SonarQube product family, visit the [Sonar website](https://www.sonarsource.com/products/sonarqube/).

<!-- sonar-marketing:end -->

## Goals

### `compress`

Compress the passed `filenames` using LZMA2 compression algorithm.

### `download-runtimes`

Download the Node.js runtimes and create their manifests (`version.txt`).
