# glmixer-snap

GLMixer Snap Image (because the app isn't compatible with Ubuntu 20.04)


## Install

**Safe but not everything is working properly:**

    snap install glmixer-unofficial

**Unsafe but works well:**

    snap install glmixer-unofficial --devmode


## Build

As you might not want to install someone else's package with `--devmode`, you can build the snap yourself.
That way you are at least sure it was built according to the [`snapcraft.yaml`](snap/snapcraft.yaml).

1. `snap install multipass --classic`

2. `snapcraft`

3. `snap install glmixer-unofficial_1.7-r1922_amd64.snap --dangerous --devmode`
