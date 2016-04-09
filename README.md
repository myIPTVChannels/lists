# Comunidade myIPTVChannels
A comunidade myIPTVChannels nasceu no seio do grupo Listas IPTV do facebook https://www.facebook.com/groups/listasiptv/. O conceito do projecto é simples, em vez de cada um criar a sua lista IPTV, trabalhamos em equipa, actualizando as listas para todos podermos ter acesso a canais o mais actualizados e optimizados possível.

O projecto é aberto à participação de todos.

Atenção: <b>Todas as ligações de streams disponibilizados nas listas foram retiradas da internet. A comunidade apenas as organiza, disponibiliza e partilha. Não detemos qualquer servidor e/ou trasmitimos ou re-emitimos qualquer tipo de sinal</b>.

##Addon surikata TV (Kodi)
Com base neste projecto, o <b>Discave</b> criou um addon com todas as listas aqui presentes já configuradas. Agora basta adicionar o repositório <b>http://kodi.discavehb.com</b>, instalar o mesmo (discave.repo.zip) e depois adicionar o addon: Discave Repositório > Video addon > <b>"surikata TV"</b>.

##Tutoriais
1 - Legendas nos filmes - http://kodiportugal.pt/adicionar-legendas-nos-filmes-e-series/

2 - Configurar SSIPTV em LG webOS 5.x (Legendas PT) - https://www.youtube.com/watch?v=faw-U6Su-0c

3 - Usar várias listas em simultâneo no Kodi - http://kodiportugal.pt/usar-varias-listas-iptv-com-o-playlistloader/

## URLs das listas myIPTVChannels (Kodi, VLC, etc.)
Portugal Channels: pt.m3u = http://git.io/vZohP

Sports Channels: sports.m3u = http://git.io/vZPSM

MotorSports Channels:	motorsports.m3u = https://git.io/vai49

Portugal Channels para Wiseplay: pt-wiseplay.wise = http://git.io/v8TRX

Movies: movies.m3u = http://git.io/vnUb0

TV Shows: tvshows.m3u = http://git.io/vWISS

Music Channels: music.m3u = http://git.io/vZohs

Kids: kids.m3u = http://git.io/vWI93

News Channels: news.m3u = http://git.io/vlxJD

Radios: radios.m3u = http://git.io/vuWqF

Internacional: international.m3u = https://git.io/vznaV

Indian IN Channels: hindi.m3u = http://git.io/vZoJg

NASA Space Channels: nasa.m3u = http://git.io/vZPFO

SMART TV (LG, Samsung, Philips): smart-tv.m3u = http://git.io/vZQlR

Webcams World / Beaches : webcamsmundoepraias.m3u = http://git.io/vZHox

Adult Channels: adult.m3u = http://git.io/vZiiP

## Listas Removidas
~~Portugal Channels XML: pt.xml = http://git.io/vut0O~~ Deprecated

~~United Kingdom UK Channels : uk.m3u = http://git.io/vZMmP~~ > international.m3u

~~Russia RU Channels: ru.m3u = http://git.io/vZoha~~ > international.m3u

##Regras
1) KISS = Keep it simple, stupid (as possible)!

1.1) Nome do canal com um espaço " " antes, a seguir à virgula (optimização para dispositivos pequenos, como tablets).

1.2) Se existir mais que um canal/ligação, diferenciar através da qualidade do canal a seguir ao nome do mesmo, com FHD (para 1080p) HD (para 720p), FSD (entre 480i e 576i) e SD (Menos de 480i), ou então um número sequencial entre parentisis. Ex: RTP FHD / RTP (2). Resoluções abaixo de 720p porém acima de 576i deverão ser consideradas "FSD" (para avaliar a resolução de uma stream, poderão usar o VLC).

1.3) Nomes dos canais sem referências, créditos e cores.

1.4) Respeitar a estrutura previamente adoptada.

1.5) Verificar se a categoria já existe, e adicionar respeitando a mesma se já existir. Podem ser usadas cores para as diferênciar.

1.6) Tentar organizar por ordem alfabética dos nomes dos canais, dentro de cada categoria.


2) Template:
EXTINF:0 tvg-name="rtp1.pt" audio-track="pt" tvg-logo="http://mylogos.domain/Sporttv1.png" group-title="TDT", RTP 1
http://server.name/stream/to/video2

2.1) group-title= Sugiro categorias clean para a organização dos canais.Evitar a criação de novas categorias

2.2) tvg name pode consultar-se o xml do epg.kodiportugal.com ou http://kodiportugal.pt/o-nosso-epg-cresceu/

2.3) tvg-id is value of channel id in EPG xml file. If the tag is absent then addon will use tvg-name for map channel to EPG;

2.4) tvg-name is value of display-name in EPG there all space chars replaced to _ (underscore char) if this value is not found in xml then addon will use the channel name to find correct EPG.

2.5) tvg-shift is value in hours to shift EPG time. This tag can be used in #EXTM3U for apply shift to all channels or in #EXTINF for apply shift only to current channel.

2.6) group-name is channels group name. If the tag is absent then addon will use group name from the previous channel.
radio is flag that indicate what group or cahnnel is radio. If the tag is absent then addon will use value from current group (if exists).

2.7) tvg-logo - Display name or logo of this channel
audio-track - Audio track definition of this channel, if it's supported by stream. Write language codes in ISO 639-2 standard, you may use several codes separated by comma (e.g.: "eng, rus, deu"). The first item in the list will be defined as default.

##Help/Ajuda

No nosso grupo do Facebook: https://www.facebook.com/groups/listasiptv/

No blog do Adriano Afonso: http://www.adrianoafonso.net/blog/2015/kodi-no-raspberrypi-mediacenter/


##Channels Sources

###Portugal
http://kodiportugal.pt
Based on Kitina, by Magellan

###Russia Channels
http://fixzen.3dn.ru/load/video/iptv_playlist/7-1-0-36

http://dump-sat.blogspot.pt/

http://retranslyator.blogspot.com/p/iptv-playlist.html

###Husham
http://www.husham.com/iptv-links/

https://github.com/hmemar/husham.com/tree/master/Lists

###Indian Channels (Husham)
https://github.com/hmemar/husham.com/blob/master/Lists/hindi.m3u

##Utilities
http://git.io/

http://kodi.tv/download/

http://www.videolan.org/vlc/

https://notepad-plus-plus.org/download/

http://bit.do/
