# MangoHud   
Instalando e permitindo o acesso do mangohud ao arquivo de configurações gerado pelo Goverlay (ou qualquer outro programa)   
**Instalação**   
```
flatpak install org.freedesktop.Platform.VulkanLayer.MangoHud

```
Selecione a versão mais recente na hora de instalar.   
**Permitir acesso as configurações geradas pelo Goverlay em ~/.config/MangoHud/MangoHud.conf**   
```
flatpak override --user --filesystem=xdg-config/MangoHud:ro

```
   
