# Useful-Bash-scripts

# Docker Games

- To play the game you wish 
  - pull the image you would like to try / play 
  - Pull using **`docker pull siddiquesa/dockergames:<tag/game-name>`**
  - Run the pulled image as **`docker run -it --rm --init -p <port>:3000 <pulled-image-name/tag>`**
  - then browse to _**http://localhost: \<port\>**_

### NOTE :- 
- For _**\<port>**_ you can give any available Ports in your Env.
- You have to replace _**<pulled-image-name/tag>**_ with correct image tag name. 
