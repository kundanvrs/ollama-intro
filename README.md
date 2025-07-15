# ollama-intro
> pip install ollama 



# Open WebUI
## 1.Installation via Python pip 

### Install Open WebUI
> pip install open-webui 
### Running Open WebUI
> open-webui serve 


### 2.Using Docker
> docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main 
