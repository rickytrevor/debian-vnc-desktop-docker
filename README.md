# debian-vnc-desktop

Not everything can be done from the command line. This brings remote desktop to a docker container, by adding a desktop environment and VNC.

### Current Status

This is my first foray into using Docker; so releases are considered development builds.

The `rickytrevor/debian-vnc:latest` tag will always point the latest image.


![No Session Error Dialog](https://raw.githubusercontent.com/bewster/debian-vnc-desktop-docker/master/no-session-error.png)

### Customisations

A number of settings can be changed using enviroment variables:

```
VNC_PASSWORD=changeit
VNC_GEOMETRY=1920x1080
```

## Links

* Docker repository: [bewster/debian-vnc-desktop](https://hub.docker.com/r/bewster/debian-vnc-desktop/)
* GitHub repository: [bewster/debian-vnc-desktop-docker](https://github.com/bewster/debian-vnc-desktop-docker)
