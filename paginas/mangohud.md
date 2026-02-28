---
# yaml-language-server: $schema=schemas/página.schema.json
Object type:
    - Página
Tag:
    - Correções
Backlinks:
    - programas.md
Creation date: "2026-02-27T22:54:30Z"
Created by:
    - Daniel Ramos
id: bafyreiazdwdchyjoizp6fvy6mnk6z3onek5uubpblnti5vxq5pm5ldsux4
---
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
   
