# DXVK   
Como exibir o aviso de que os shaders estão sendo compilados.   
Vá até a pasta   
> ~/.steam/steam/steamapps/common/Proton VER/user_settings.sample.py   

ou ~/.steam/steam/compatibilitytools.d/Seu Proton   
Abra esse arquivo com um editor de texto, ache a linha escrito `# "DXVK\_HUD": "devinfo,fps"`, tire o hashtag (#) e o `devinfo,fps` dentro das aspas, substitua por `compiler`.   
Salve o arquivo como `user\_settings.py` no mesmo local.   
   
