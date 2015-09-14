# myIPTVchannels
Just a private collection of IPTV links collected over the web!
Opened to all the IPTV community.

##URLS myIPTVChannels (Kodi/VLC, etc)
PT Channels: pt.m3u = http://git.io/vZohP

Sports Channels: sports.m3u = http://git.io/vZPSM

UK Channels : uk.m3u = http://git.io/vZMmP

RU Channels: ru.m3u = http://git.io/vZoha

IN Channels: hindi.m3u = http://git.io/vZoJg

Music Channels: music.m3u = http://git.io/vZohs

NASA Channels: nasa.m3u = http://git.io/vZPFO

Adult Channels: adult.m3u = http://git.io/vZiiP


##Rules
1) KISS = Keep it as simple (as possible)!

1.1) Nome do canal com um espaço " " antes, a seguir à virgula (optimização para dispositivos pequenos, como tablets).

1.2) Se existir mais que um canal/ligação, diferenciar através de HD (para 1080p), SD (720p ou menos), ou então um número sequencial entre parentisis. Ex: RTP (2)

1.3) Nomes dos canais sem referências, créditos e cores.

1.4) Respeitar a estrutura previamente adoptada.

1.5) Verificar se a categoria já existe, e adicionar respeitando a mesma se já existir. Podem ser usadas cores para as diferênciar.

1.6) Tentar organizar por ordem alfabética dos nomes dos canais, dentro de cada categoria.


2) Template:
EXTINF:0 tvg-name="rtp1.pt" audio-track="pt" tvg-logo="http://mylogos.domain/Sporttv1.png" group-title="TDT", RTP 1
http://server.name/stream/to/video2

2.1) group-title= Sugiro categorias clean para a organização dos canais.Evitar a criação de novas categorias

2.2) tvg name pode consultar-se o xml do epg.kodiportugal.com

2.3) tvg-id is value of channel id in EPG xml file. If the tag is absent then addon will use tvg-name for map channel to EPG;

2.4) tvg-name is value of display-name in EPG there all space chars replaced to _ (underscore char) if this value is not found in xml then addon will use the channel name to find correct EPG.

2.5) tvg-shift is value in hours to shift EPG time. This tag can be used in #EXTM3U for apply shift to all channels or in #EXTINF for apply shift only to current channel.

2.6) group-name is channels group name. If the tag is absent then addon will use group name from the previous channel.
radio is flag that indicate what group or cahnnel is radio. If the tag is absent then addon will use value from current group (if exists).

2.7) tvg-logo - Display name or logo of this channel
audio-track - Audio track definition of this channel, if it's supported by stream. Write language codes in ISO 639-2 standard, you may use several codes separated by comma (e.g.: "eng, rus, deu"). The first item in the list will be defined as default.

##Channels Sources

###Portugal
http://kodiportugal.com/iptv.html
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
