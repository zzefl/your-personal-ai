# your-personal-ai
Hi! If you came here, it means you wanted your personal assistant on the PC. 
This guide will install and configure your personal AI on your computer! 
First you need to install the necessary components: 
1. Docker https://www.docker.com/products/docker-desktop/
2. Ollama https://ollama.com/

Dachshund, if you've installed this, then you're doing great!
Add Docker Desktop to the PATH and almost everything is ready, it remains to choose the model of your assistant!
when you install ollama, you will have a console, write
```bash 
ollama run mistral```
or
 ```bash
ollama run llama3```
 there, now wait until it is installed and consider it ready!
But if you want a web interface (like ChatGPT), then write in the console ```bash docker run -d -p 3000:3p000 -e OLLAMA_BASE_URL=http://host.docker.internal:11434 --name open-webui ghcr.io/open-webui/open-webui:main`
And count That's it! Now you have a personal assistant on your computer.
