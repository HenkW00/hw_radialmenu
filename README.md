# HW Scripts - Radial Menu

**Description**
- This is a radial menu system that can help improve RP.
Its using the OX Radial Menu, and currently im working on making it funtion on some of my own scripts.
You can configure alot, but i havent yet made all things nice, since im still working on it.
Script might look verry messy, and im sorry for that part!
- This script works with [HW Med System](https://github.com/HenkW00/hw_medsystem)


**Author**
- HW Development | HenkW

🛠 **Requirements**
- ESX Server
- OX Lib
- HW Med System (only if you want to use the radial menu function)

^^^^
Please be aware you have to uncomment the function needed (own med check or nearby player), u can change this in hw_medsystem>client>main.lua:line186. 
The radial menu script will know what to do, so no changes needed there ;)



🌐 **Requirements Download links**
- es_extended: [https://github.com/esx-framework/esx_core]
- ox_lib: [https://github.com/overextended/ox_lib]
- hw_medsystem: [https://github.com/HenkW00/hw_medsystem] --> Optional

✅ **Features**
- Vehicle functions added when in a vehicle.
- Clothing option added in radial menu.
- You can open the radial menu via '~' on youre keyboard.

**Preview**
- Radial Menu
![image|492x425](upload://at9dfkk9R87x5rtcEkXzIDDhY60.jpeg)

- Example function that currently works with latest release from hw_medsystem
![image|560x444](upload://yKhzLE9rlXfphNqnKR9c5QgH5qh.jpeg)
![image|687x500](upload://sXpX3qwzGrGvw1oXH3slSsGZBHX.jpeg)


🔧 **Download & Installation**

Follow these steps to set up the radial script on your ESX server:

1. **Download the Files**: Download the script files from the provided source.

2. **Copy to Server Resource Directory**: Place the `hw_radialmenu` folder in the server resource directory.

3. **Update `server.cfg`**: Add the following line to your `server.cfg` file:

    ```cfg
    start hw_radialmenu
    ```

4. **Start Your Server**: Restart or start your ESX server to load the `hw_radialmenu` resource.

Enjoy the script! <3