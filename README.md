[![Twitter](https://img.shields.io/twitter/url.svg?label=Follow%20%40_mithundas&style=social&url=https%3A%2F%2Ftwitter.com%2F_mithundas)](https://x.com/_mithundas)

# Balenafied Ollama Open Webui

Deploy open webui with a click of a button using balena on different single board computers such as Raspberry Pi 5

### Hardware

<table>

<tr><td>
<img height="24px" src="https://raw.githubusercontent.com/ketilmo/balena-ads-b/master/docs/images/arch/raspberrypi5.svg" alt="raspberrypi4-64" style="max-width: 100%; margin: 0px 4px;"></td><td>Raspberry Pi 5</td>
</tr>
</table>

### Software

- Sign up for a free [BalenaCloud account](https://www.balena.io/)
- [balenaEtcher](https://www.balena.io/etcher/)

### Deploy using balenaCloud

Click on the _deploy-with-balena_ button as given below, which will help you to deploy your application to balenaCloud and then to your Raspbery Pi in **one-click!**

[![](https://balena.io/deploy.png)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/just4give/balenafied-ollama-open-webui)

Else you can build your own release by cloning this repo on your primary machine (x86) and use the following commands :

```
$ git clone https://github.com/just4give/balenafied-ollama-open-webui.git
$ cd balenafied-ollama-open-webui
$ balena login
$ balena push balenafied-ollama-open-webui
```

[Sample PDF](https://arxiv.org/pdf/1702.05843)
