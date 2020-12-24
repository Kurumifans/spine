# Spine

A web Spine viewer for models exported from Spine Version 2.1.27

## Features

### Drag and Drop
You can drop files directly into the view (canvas). The files required are: a .json or skel file, an atlas file (with the same name of the json/skel files) and sprite images specified inside .atlas file.

### Load from url
You can load models directly from url by specifying the query parameter `url`

Example: https://dalfc.github.io/spine/?url=https://raw.githubusercontent.com/n0k0m3/DateALiveData/master/res/basic/modle/weapon/angel_1104061/angel_1104061.skel

Note that the url containing the skeleton file should return the CORS headers, or the browser will block your request
