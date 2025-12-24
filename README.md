# rpi-mediarr
## HW Aceleration improvements
sudo apt install -y libva-dev vainfo
sudo apt install -y \
  libva2 \
  libva-drm2 \
  mesa-va-drivers \
  libv4l-0 \
  v4l-utils
  
**RPi 4+**
dtoverlay=vc4-kms-v3d > /boot/firmware/usercfg.txt
