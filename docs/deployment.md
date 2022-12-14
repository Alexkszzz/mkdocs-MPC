# Deployment

Currently the website is deployed as a [test version](https://boisterous-axolotl-f0066f.netlify.app/) on Netlify. 

If you want to deploy in your local machine, use the following commands
```bash
    next build
```
then run it with
```bash
    next start
```

## Note
If you want to redeploy the website on Netlify, please note that Netlify treats all warnings as errors, and the website has some warnings at the moment. Therefore, you need to change CI value to false in Deployment Settings. See [documentation](https://docs.netlify.com/configure-builds/troubleshooting-tips/#build-fails-on-warning-message).

