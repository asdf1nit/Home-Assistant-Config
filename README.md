
# My Hass.io Home Assistant Configuration

### Welcome to my configuration! 

This is a work in progress as all home automation platforms usualy are. I haven't been using home assistant for long as of now( Dec 2018 ) so it's really basic as far as the functionality goes. I did take the time to split all of my configuration now that way it's not so cluttered in the end. I'm running on a ~~rpi 3 b+~~ for now but I have a nice little quad core nuc I plan on deploying it to along with a few other docker containers for my unifi network and pi hole.

---

** Updates and lots of chnages since my first commit **

1. I've since moved to my celeron j1900 qotom box that used to be a pfSense router.
2. I'm running hassos in debian stretch.
3. Unifi is on a CloudKey Gen 2.
4. I've added some sonoff switches with tasmota and use the TasmoAdmin plugin.
5. Started usign MQTT, grafana, and InfluxDB for nice graphs
6. Using unifi cameras

 Over all things have come along nice and this is a great platform to work with. I still have many things
Things I want to do
- [] Reconfigure my folder structure to make things a little cleaner
- [] Document more of my config and the devices I use
- [] Document my HomePanel display that I have on the living room wall, it's a pi4 with a [FullPageOS](https://github.com/guysoft/FullPageOS "FullPageOS Git Repo") custom build, [12.3" touchscreen](https://uperfect.store/products/touch-monitor-uperfect-12-3-computer-display-1600-1200-portable-monitor-capacitive-external-screen-4-3-speakers-vesa-fit-with-hdmi-dvi-vga-micro-usb-dc-for-pc-phone-mac-win-ps4-xbox-tv-industry) and all powered over a single poe port from a unifi switch
- [] Setup traefik as a reverse proxy and stop using the duckdns addon
- [] Get away from the vera zwave controller I have and replace those switches with more sonoff/tasmo flashed devices