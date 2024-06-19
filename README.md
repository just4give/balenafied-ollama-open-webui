[![Twitter](https://img.shields.io/twitter/url.svg?label=Follow%20%40_mithundas&style=social&url=https%3A%2F%2Ftwitter.com%2F_mithundas)](https://x.com/_mithundas)

![](./logo.png)

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

<video alt="vide" src="https://github.com/just4give/balenafied-ollama-open-webui/assets/9275193/79706103-d860-49ce-9df1-48bc4c1b6c64"  width="480" height="320" >
</video>


<details>
  <summary>Flash the SD card with downloaded image</summary>
<video width="480" height="320" controls src="https://github.com/just4give/balenafied-ollama-open-webui/assets/9275193/db3f580e-766d-4a3f-8b49-c924e727c273">
</video>

</details>

<details>
  <summary>Download local LLM</summary>
  
<video src="https://github.com/just4give/balenafied-ollama-open-webui/assets/9275193/f7cd4127-f7f5-432b-837e-0d93287a96af" width="480" height="320" >
</video>

</details>

<details>
  <summary>Chat with local LLM</summary>
  <video src="https://github.com/just4give/balenafied-ollama-open-webui/assets/9275193/5ec30909-f89e-4312-9be6-3594679247ab"  width="480" height="320" controls>
  </video>

</details>
