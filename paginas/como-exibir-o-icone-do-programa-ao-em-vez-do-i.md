---
# yaml-language-server: $schema=schemas/página.schema.json
Object type:
    - Página
Tag:
    - Correções
Backlinks:
    - correcoes.md
Creation date: "2026-02-27T22:21:12Z"
Created by:
    - Daniel Ramos
Image:
    - files/wayland-logo-png-transparent-3042440460.png
id: bafyreifxe2cm3xnmwmptz4zd62znfilurwpmjtblktg4qjnu3ruhh5yid4
---
# Como exibir o ícone do programa ao em vez do ícone do Wayland em alguns casos   
Eu achei essa dica em algum lugar gringo que eu não dei os créditos na época, então vou ficar devendo, enfim.   
Isso é bem simples   
Clique no ícone do Wayland, depois vá em   
> Mais ações > Definir as configurações especiais do aplicativo > Adicionar propriedade > Nome do arquivo desktop   

Depois de adicionar isso, você deve botar o nome que seria o identificador do aplicativo, por exemplo, o identificador do GIMP (Flatpak) é `org.gimp.GIMP`, mas nem sempre vai ser assim, caso não funcione com o nome que o próprio painel de configurações especiais mostra, você pode usar o programa do próprio Plasma chamado "Explorador de ícones", procure o programa que você quer saber o "ID" do ícone e bote lá na caixinha do arquivo desktop, aplique e está pronto.   
