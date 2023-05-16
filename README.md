# Auto-Msg-Send-on-Whatsapp
Automatic message send on whatsapp using pywhatkit


# Installation and Supported Versions
     
      PyWhatKit is available on PyPi:

               python3 -m pip install pywhatkit
               pip3 install pywhatkit
               
               

This method can be used to remotely control your PC using your phone (Windows only)
               
      
      Make sure your PC and your phone are on same network, on your PC, Open Network and Internet Settings > Properties > Network Profile, make sure it's set to Private.
      
      
      
      
# Features
         
         
                    * Sending Message to a WhatsApp Group or Contact
                    * Sending Image to a WhatsApp Group or Contact
                    * Converting an Image to ASCII Art
                    * Converting a String to Handwriting
                    * Playing YouTube Videos
                    * Sending Mails with HTML Code
                    * Install and Use
                    
                    
                    
# Usage


import pywhatkit

# Send a WhatsApp Message to a Contact at 1:30 PM
pywhatkit.sendwhatmsg("+910123456789", "Hi", 13, 30)

# Same as above but Closes the Tab in 2 Seconds after Sending the Message
pywhatkit.sendwhatmsg("+910123456789", "Hi", 13, 30, 15, True, 2)

# Send an Image to a Group with the Caption as Hello
pywhatkit.sendwhats_image("AB123CDEFGHijklmn", "Images/Hello.png", "Hello")

# Send an Image to a Contact with the no Caption
pywhatkit.sendwhats_image("+910123456789", "Images/Hello.png")

# Send a WhatsApp Message to a Group at 12:00 AM
pywhatkit.sendwhatmsg_to_group("AB123CDEFGHijklmn", "Hey All!", 0, 0)

# Send a WhatsApp Message to a Group instantly
pywhatkit.sendwhatmsg_to_group_instantly("AB123CDEFGHijklmn", "Hey All!")

# Play a Video on YouTube
pywhatkit.playonyt("PyWhatKit")

# Converting image to ASCII Art
  ascii_art = pywhatkit.image_to_ascii_art("image path")
  print(ascii_art)
