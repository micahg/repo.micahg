# micahg's Kodi Repo

Hosts my addons that aren't really good enough for the main kodi repo. For
example, addons I don't want the reponsibility of maintaining in a timely
fashion.

## Download Link

Zip should be available directly [here](https://raw.githubusercontent.com/micahg/repo.micahg/master/repo.micahg.zip)

## Generating

Something like:

```
../create_repository.py --compressed https://github.com/micahg/plugin.video.snnow.git https://github.com/micahg/plugin.video.tsngo.git https://github.com/micahg/plugin.video.onesoccer.git ~/workspace/plugin.video.hdhrlive https://github.com/micahg/plugin.video.cbc
```
