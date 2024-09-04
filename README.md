
## Run

### Locally (your PC)
Assumes you have an `index.html` with this line 13:
```js
await cheerpjRunJar("/app/osp_csm.jar");
```

1. Start `http-server` on the current local folder. Example `http-server -p 8080`  
2. Click on one of the IP addresses provided by the script. Example: http://127.0.0.1:8080
3. When your internet browser opens the page, wait for few seconds until the Java application is converted to WebAssembly


