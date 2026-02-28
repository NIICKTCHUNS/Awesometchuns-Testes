---
# yaml-language-server: $schema=schemas/página.schema.json
Object type:
    - Página
Backlinks:
    - joguinhos-100-originais.md
Creation date: "2026-02-27T22:32:12Z"
Created by:
    - Daniel Ramos
Emoji: "\U0001F534"
id: bafyreidcam2eq475hfsjxewc2xfui4nuukkubjbc7aydvjme6gf7khwkyi
---
# Joguinho online 100% original   
Para jogar aquele joguinho 100% legit no seu Linux você precisa fazer fazer alguns passos a mais do que no Windows, que seria só baixar e executar com a Steam aberta.   
Para corrigir esses jogos do "multiplayer-fix.me" você precisa fazer o seguinte:   
1. Adicionar o jogo na Steam, no caso o executável do jogo.   
2. Adicione esse comando enorme nas Opções de Inicialização do jogo, na página de propriedades.
`WINEDLLOVERRIDES="OnlineFix64=n;SteamOverlay64=n;winmm=n,b;dnet=n;steam\_api64=n;winhttp=n,b" %command%`   
3. Vá na aba de Compatibilidade e ative o Proton.   
   
Feito isso, é só abrir o jogo diretamente pela Steam e vai funcionar normalmente! Podendo até usar o Overlay da Steam para convidar os amigos.   
Fonte:   
[Reddit (Esse subreddit é MUITO útil)](https://www.reddit.com/r/LinuxCrackSupport/comments/1cw7v8j/onlinefix_a_complete_guide_to_running_games_with/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)   
   
