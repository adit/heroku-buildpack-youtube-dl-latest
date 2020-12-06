# heroku-buildpack-youtube-dl-latest

![test](https://github.com/adit/heroku-buildpack-youtube-dl-latest/workflows/test/badge.svg)

A Heroku buildpack for youtube-dl that always downloads the latest [static build](https://github.com/ytdl-org/youtube-dl/releases/latest).

## Usage

Add the following to your `app.json`:

```json
{
  "buildpacks": [
    {
      "url": "https://github.com/adit/heroku-buildpack-youtube-dl-latest"
    }
  ]
}
```

Or run the following from the heroku command line:

```bash
heroku buildpacks:add https://github.com/adit/heroku-buildpack-youtube-dl-latest

```
