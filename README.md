# HTLV-1-machine-learning

## How to Run on Docker Image
- Install docker from the official website.
- Open the terminal and execute the following :
 
- pull the docker image from mdishtiakrashid/htlv_analysis_image

 ```
 docker pull mdishtiakrashid/htlv_analysis_image
```

- run the image :

```
docker run -p 8888:8888 mdishtiakrashid/htlv_analysis_image
```

- After running the container, note the URL with the token provided in the terminal output. Open this URL in a web browser to access the Jupyter notebook. From the panel bar on the left access the file.
