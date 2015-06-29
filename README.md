# PiSnapND
Snap! with Nailduino on Raspberrypi

# Used OSS
### S2A Firmata
    * https://github.com/MrYsLab/s2a_fm
    * Modified
        ```
        . Can Connect IP Address.
        ```
        
    
### Setup.
    * First, must check this basic raspberrypi configuration.
        ```
        . run raspi-config
        . Resize SD Card
        . Set Start xwindow at raspberrypi boot-up.
        . International configuration
        ```
    * Second, deffendence
        . https://github.com/rasplay/PiSnap.git
    
    * Clone Source
        ```
        $ cd ~/multisnap
        $ git clone https://github.com/rasplay/PiSnapND.git
        $ cd PiSnapND
        $ sh setup.sh
        ```

### Run
    * Restart RPi
    * Double Click NailDuinoSnap Icon (Console Window always open)
    * Double Click PiSnap Desktop Icon
    
    