# glmixer-snap
GLMixer Snap Image (because it isn't compatible with Ubuntu 20.04)

## Install

**Safe but not everything is working properly:**

  snap install glmixer-unofficial

**Unsafe but works well:**

  snap install glmixer-unofficial --devmode

## Build

As you might not want to install someone else's package with `--devmode`, you might want to build the snap yourself.

1. `snap install multipass --classic`

2. `snapcraft`

3. `snap install glmixer-unofficial_1.7-r1922_amd64.snap --dangerous --devmode`
