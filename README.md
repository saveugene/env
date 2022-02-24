# My enviroment

## Packages:
* [pyenv](https://github.com/pyenv/pyenv)
* [nvm](https://github.com/nvm-sh/nvm)
* [git](https://github.com/git/git)
* [ffmpeg](https://github.com/FFmpeg/FFmpeg)
* docker
  * [Install](https://docs.docker.com/engine/install/ubuntu/)
  * [Post install](https://docs.docker.com/engine/install/ubuntu/)
* docker-compose
  * [Install](https://docs.docker.com/compose/install/)
* helm 
  * [Install](https://helm.sh/docs/intro/install/)
* kubectl 
  * [Install](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/)
* [python](https://github.com/python/cpython)
* [node](https://github.com/nodejs/node)


## Programs:
* [keeweb](https://github.com/keeweb/keeweb)
* [museeks](https://github.com/martpie/museeks)
* [flameshot](https://github.com/flameshot-org/flameshot)
* [pycharm](https://www.jetbrains.com/pycharm/)
* [telegram-desktop](https://github.com/telegramdesktop/tdesktop)
* [spotify](https://www.spotify.com/us/download/other/)
* [visual-studio-code](https://github.com/microsoft/vscode)
* [google-chrome](https://www.google.com/chrome/)
* [vlc](https://github.com/videolan/vlc)
* [qbittorrent](https://github.com/qbittorrent/qBittorrent)


## MacOS programs:
* [mos](https://github.com/Caldis/Mos)
* [linearmouse](https://github.com/linearmouse/linearmouse)



## Fixes:
- Keychron K2 fn keys fix (ubuntu)
```console
echo "options hid_apple fnmode=0" | sudo tee -a /etc/modprobe.d/hid_apple.conf
```