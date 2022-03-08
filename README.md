# [whichmoto.com](https://whichmoto.com)

This repo deploys a [fast.ai](https://github.com/fastai/fastai) model on Render.

The app described here is up at https://whichmoto.onrender.com. Test it out with motorcycle images!

## Develop

You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

## Deploy

The guide for to deploy this repo is at https://course.fast.ai/deployment_render.html.

Please use [Render's fast.ai forum thread](https://forums.fast.ai/t/deployment-platform-render/33953) for questions and support.
