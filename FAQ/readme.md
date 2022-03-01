# FAQ
## Si l'esp n'ai pas reconnu
- changer de cable USB
- Changer d'adaptateur <br><img src="../FAQ/Images/IMG_8334.jpg" width="300">
- installer le driver associé à l'esp (voir model sur le microprocesseur) <br><img src="../FAQ/Images/IMG_8332.jpg" width="300"> <br><img src="../FAQ/Images/Install-CP210x-VCP-Driver 2022-01-29 16-10-44.png" width="300">
- vérifier dans /dev si le port existe bien <br><img src="../FAQ/Images/terminal.png" width="300"> 

## Impossibible de téléverser le code

<img src="../FAQ/Images/upload-error.png" width="400"> 

Il faut presser sur RESET + GPIO0 au moment du téléchargement. Attention il y a 3 boutons sur certain modèl ! Utiliser celui sous l’ESP et le GPIO0 du support.

ATTENTION : Il faut ensuite débrancher puis rebrancher l’ESP

Vidéo : https://youtu.be/v8s-UMqcTJs 

Si cela ne fonctionne toujours pas
- débrancher l'alim. de l'esp (pin 5v ou 3.3v)
- débrancher toutes les pin et recommencer.

## Corespondance Dx -> GPIOx
<img src="../FAQ/Images/ESP8266-NodeMCU-kit-12-E-pinout-gpio-pin.png" width="400"> 
