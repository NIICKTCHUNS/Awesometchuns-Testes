# Locales   
Pelo visto ao instalar um sistema em português o local selecionado é apenas do idioma no qual você selecionou, no meu caso, português, que no caso é `pt\_BR.UTF-8`.   
Certa vez eu estava lendo os logs da Steam e percebi um aviso que estava aparecendo sempre que eu abria um jogo com o Proton.   
> pressure-vessel-adverb[7966]: W: Container startup will be faster if missing locales are created at OS level   

O local que esse aviso se referia era: `en\_US.UTF-8`. Ativando esse local pelo visto aceleraria o processo de abrir um jogo na Steam via Proton, e quem sabe os nativos também.   
Para habilitar é bem simples, só editar um arquivo e rodar um comando.   
Primeiro descomente a linha do local en\_US que citei acima no arquivo `/etc/locale.gen` com seu editor de texto favorito, depois disso rode o comando `sudo locale-gen`. Só isso.   
*OBS: Não confundir com o arquivo `/etc/locale.conf`, esse vc não mexe.*   
   
