
## Run


### Remotely
This assumes you have this folder in GitHub. We will need to change `index.html` file on the line cited above as this:
```js
await cheerpjRunJar("/app/cheerpj-osp_csm/osp_csm.jar");
```
where we have added the name of the repository `cheerpj-osp_csm` to the path.

1. Enable **GitHub Pages** for this repository, with *Settings | Pages*; Build and Deployment Source: **Deploy from a branch**;  Branch: `main / root`
2. Wait few seconds until the build finishes. You will see a web address at GitHub Pages. Something like this: `https://username/github.io/cheerpj-osp_csm/`
3. Wait few seconds for cheerpJ to build the application


