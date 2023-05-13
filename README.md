# debian-desktop-novnc
A lightweight desktop environment for Debian docker image that can be accessed from any browser. The image is based on the following components: 
- Debian Linux distribution
- Xfce Desktop environment 
- TigerVNC VNC server (default port 5901)
- noVNC VNC client web application (default port 6901)
# Usage
'''docker run -d --name=linux-desktop -p 6901:6901 -p 5901:5901 galjabari/debian-dektop-novnc'''
