<h2 align="center">An agency specializing in custom plugin development for Grafana founded by long-time Grafana contributor Mikhail Volkov.</h2>

<div align="center"><img style="display: block; margin-left: auto; margin-right: auto; width: 35%;" src="https://volkovlabs.io/img/main.svg"></div>

<p align="center"><a href="https://volkovlabs.io" target="_blank"><img src="https://img.shields.io/badge/-Web-blueviolet?style=for-the-badge&logo=webpack"></a> <a href="https://volkovlabs.com" target="_blank"><img src="https://img.shields.io/badge/-Blog-orange?style=for-the-badge&logo=medium"></a> <a href="https://www.youtube.com/channel/UCQadniwbukI6ZmTN2oTTb-g" target="_blank"><img src="https://img.shields.io/badge/-Youtube-red?style=for-the-badge&logo=youtube"></a> <a href="https://demo.volkovlabs.io" target="_blank"><img src="https://img.shields.io/badge/-Demo%20Server-gray?style=for-the-badge&logo=codeforces"></a>  <a href="https://www.linkedin.com/company/volkovlabs" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=linkedin"></a> <a href="https://twitter.com/volkovlabs" target="_blank"><img src="https://img.shields.io/badge/-Twitter-9cf?style=for-the-badge&logo=twitter"></a></p>

## Plugins for Grafana

| Plugin | Repository | Labels |
| ---- | ----- | ---- |
| [Apache ECharts Panel](https://github.com/volkovlabs/volkovlabs-echarts-panel) | Private | ![Release](https://img.shields.io/github/v/release/volkovlabs/volkovlabs-echarts-panel.svg) ![Stars](https://img.shields.io/github/stars/volkovlabs/volkovlabs-echarts-panel.svg?style=social&amp;label=Star&amp;maxAge=3600) [![codecov](https://codecov.io/gh/VolkovLabs/volkovlabs-echarts-panel/branch/main/graph/badge.svg)](https://codecov.io/gh/VolkovLabs/volkovlabs-echarts-panel)
| [Balena Application](https://github.com/volkovlabs/volkovlabs-balena-app) | Private |  ![Release](https://img.shields.io/github/v/release/volkovlabs/volkovlabs-balena-app.svg) ![Stars](https://img.shields.io/github/stars/volkovlabs/volkovlabs-balena-app.svg?style=social&amp;label=Star&amp;maxAge=3600) [![codecov](https://codecov.io/gh/VolkovLabs/volkovlabs-balena-app/branch/main/graph/badge.svg)](https://codecov.io/gh/VolkovLabs/volkovlabs-balena-app)
| [Base64 Image/Video/Audio/PDF Panel](https://github.com/volkovlabs/volkovlabs-image-panel) | Grafana Marketplace | ![Release](https://img.shields.io/github/v/release/volkovlabs/volkovlabs-image-panel.svg) ![Stars](https://img.shields.io/github/stars/volkovlabs/volkovlabs-image-panel.svg?style=social&amp;label=Star&amp;maxAge=3600) [![codecov](https://codecov.io/gh/volkovlabs/volkovlabs-image-panel/branch/main/graph/badge.svg)](https://codecov.io/gh/volkovlabs/volkovlabs-image-panel) [![Plugin Downloads](https://img.shields.io/badge/dynamic/json?color=green&label=downloads&query=%24.downloads&url=https%3A%2F%2Fgrafana.com%2Fapi%2Fplugins%2Fvolkovlabs-image-panel)](https://grafana.com/grafana/plugins/volkovlabs-image-panel)| 
| [Data Manipulation Panel](https://github.com/volkovlabs/volkovlabs-form-panel) | Private | ![Release](https://img.shields.io/github/v/release/volkovlabs/volkovlabs-form-panel.svg) ![Stars](https://img.shields.io/github/stars/volkovlabs/volkovlabs-form-panel.svg?style=social&amp;label=Star&amp;maxAge=3600) [![codecov](https://codecov.io/gh/VolkovLabs/volkovlabs-form-panel/branch/main/graph/badge.svg)](https://codecov.io/gh/VolkovLabs/volkovlabs-form-panel)
|[Environment Data Source](https://github.com/volkovlabs/volkovlabs-env-datasource) | Private | ![Release](https://img.shields.io/github/v/release/volkovlabs/volkovlabs-env-datasource.svg) ![Stars](https://img.shields.io/github/stars/volkovlabs/volkovlabs-env-datasource.svg?style=social&amp;label=Star&amp;maxAge=3600) [![codecov](https://codecov.io/gh/VolkovLabs/volkovlabs-env-datasource/branch/main/graph/badge.svg)](https://codecov.io/gh/VolkovLabs/volkovlabs-env-datasource)
|[RSS/Atom Data Source](https://github.com/volkovlabs/volkovlabs-rss-datasource) | Grafana Marketplace | ![Release](https://img.shields.io/github/v/release/volkovlabs/volkovlabs-rss-datasource.svg) ![Stars](https://img.shields.io/github/stars/volkovlabs/volkovlabs-rss-datasource.svg?style=social&amp;label=Star&amp;maxAge=3600) [![codecov](https://codecov.io/gh/VolkovLabs/volkovlabs-rss-datasource/branch/main/graph/badge.svg)](https://codecov.io/gh/VolkovLabs/volkovlabs-rss-datasource) [![Plugin Downloads](https://img.shields.io/badge/dynamic/json?color=green&label=downloads&query=%24.downloads&url=https%3A%2F%2Fgrafana.com%2Fapi%2Fplugins%2Fvolkovlabs-rss-datasource)](https://grafana.com/grafana/plugins/volkovlabs-rss-datasource)|

### Install from our Private Repository

We are constantly updating and improving our Grafana plugins. A private repository has become a part of our workflow to verify and test plugins on our demo server and projects.

```bash
$ grafana-cli --repo https://volkovlabs.io/plugins plugins list-remote
```

## balenaHub Projects
  
| Project | Labels |
| ---- | ------ |
| [Balena NFS Server and Client](https://github.com/VolkovLabs/balena-nfs) | ![Release](https://img.shields.io/github/v/release/volkovlabs/balena-nfs.svg) ![Stars](https://img.shields.io/github/stars/volkovlabs/balena-nfs.svg?style=social&amp;label=Star&amp;maxAge=3600) [![Balena](https://github.com/volkovlabs/balena-nfs/actions/workflows/balena.yml/badge.svg)](https://github.com/volkovlabs/balena-nfs/actions/workflows/balena.yml) [![Deploy with balena](https://balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/volkovlabs/balena-nfs)
| [Balena Application for Grafana](https://github.com/VolkovLabs/volkovlabs-balena-app) | ![Release](https://img.shields.io/github/v/release/volkovlabs/volkovlabs-balena-app.svg) ![Stars](https://img.shields.io/github/stars/volkovlabs/volkovlabs-balena-app.svg?style=social&amp;label=Star&amp;maxAge=3600) [![Balena](https://github.com/volkovlabs/volkovlabs-balena-app/actions/workflows/balena.yml/badge.svg)](https://github.com/volkovlabs/volkovlabs-balena-app/actions/workflows/balena.yml) [![Deploy with balena](https://balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/volkovlabs/volkovlabs-balena-app)

## Development Templates for Grafana
  
| Template | Labels |
| ---- | ------ |
| [Abc Panel](https://github.com/volkovlabs/volkovlabs-abc-panel) | ![Release](https://img.shields.io/github/v/release/volkovlabs/volkovlabs-abc-panel.svg) ![Stars](https://img.shields.io/github/stars/volkovlabs/volkovlabs-abc-panel.svg?style=social&amp;label=Star&amp;maxAge=3600) [![codecov](https://codecov.io/gh/volkovlabs/volkovlabs-abc-panel/branch/main/graph/badge.svg)](https://codecov.io/gh/volkovlabs/volkovlabs-abc-panel)
|[Abc Data Source](https://github.com/volkovlabs/volkovlabs-abc-datasource) | ![Release](https://img.shields.io/github/v/release/volkovlabs/volkovlabs-abc-datasource.svg) ![Stars](https://img.shields.io/github/stars/volkovlabs/volkovlabs-abc-datasource.svg?style=social&amp;label=Star&amp;maxAge=3600) [![codecov](https://codecov.io/gh/volkovlabs/volkovlabs-abc-datasource/branch/main/graph/badge.svg)](https://codecov.io/gh/volkovlabs/volkovlabs-abc-datasource)
|[Abc Application](https://github.com/volkovlabs/volkovlabs-abc-app) | ![Release](https://img.shields.io/github/v/release/volkovlabs/volkovlabs-abc-app.svg) ![Stars](https://img.shields.io/github/stars/volkovlabs/volkovlabs-abc-app.svg?style=social&amp;label=Star&amp;maxAge=3600) [![codecov](https://codecov.io/gh/volkovlabs/volkovlabs-abc-app/branch/main/graph/badge.svg)](https://codecov.io/gh/volkovlabs/volkovlabs-abc-app)
