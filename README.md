# Specifications and possible configuration to run a VAAPI accelared server without dGPU

First step is to configure the headless server to have a dummy Xserver running, so the VAAPI can run correctly;

# 10-headless.conf
/etc/X11/xorg.conf.d/10-headless.conf

For a headless configuration, the xf86-video-dummy driver is necessary; install it and create a configuration file above.
