# [NMRiH/Any?] Decal image

Print image to ingame with three colors (white, gray, black) by using decal.

[+] NOTE: Due to the limited number of usable decals, black tile will not printed to reduce the number of decals.

## Requirements
* [**Socket extension**](http://forums.alliedmods.net/showthread.php?t=67640)
* [**img_server**](https://github.com/newpsw/img_server)

## Environment settings

 1. Run the Python 'image_server'.
 2. Set the server port and also set the secret code to be include in text.
 3. Run a game server with the 'decal_img' plugin included.
 4. Check if the game server and the Python socket server (img_sever) are connected.

    **[ ! ] CAUTION :**

    **The game server and Python server(img_server) must be set to the same IP (same IP, different ports).**

   [+] NOTE :
 
   The maximum number of connections to the Python server is 6, and duplicate IPs accessed from outside are set to disconnect.
   When the in-game server is connected to the Python server,
   you can communicate with the in-game player by connecting to the Python server from the outside using a tcp client and sending text in utf-8 format.
   (If you do not include the secret code to end of the text you send, the connection will be disconnected.)

## Command list

* **!dp**

 Reprints the last printed image.

  
* **!dp+url**

 Downloads and prints the image from the url.
 
 If download the image from the url fails, it will reprints the last printed image.

 **- Example command line :**
    
    !dphttps://steamuserimages-a.akamaihd.net/ugc/2389811413347088108/F803727C196C745E5E2A14EE8996CF904477ABBD/



## Video

 https://www.youtube.com/watch?v=NmyVxr2R-AA
## 

* **Original image :**

![image](https://github.com/user-attachments/assets/75c63c99-cb53-41d4-baa3-bfe270a2f5f2)


* **Print image to ingame :**

![image](https://github.com/user-attachments/assets/cbbdcb56-9aba-42ad-aab1-e92a2976cede)

