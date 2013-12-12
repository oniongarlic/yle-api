yle-api
=======

Unofficial documentation for YLE APIs and live radio streams

Radio station information
- http://yle.fi/global/radio-apps-xml/sns2.xml

XML files providing basic information of all stations, names and links to
station home page, twitter and facebook pages.

Program data
=

JSON formated. File name encodes date to query, YYYY-M-D.json, no zero padding.

- http://yle.fi/ohjelmat/radio/extrem/2013-5-11.json
- http://yle.fi/ohjelmat/radio/vega/aboland/2013-4-30.json
- http://yle.fi/ohjelmat/radio/ylenklassinen/2013-8-2.json

Song information, played, current and next
=

Values for %d
- -2 prevprev
- -1 prev
- 0 current
- 1 next
- 2 etc

URLs
- X3M, http://yle.fi/radiomanint/LiveXML/r44/item(0).xml
- YLEX, http://yle.fi/radiomanint/LiveXML/r02/item(0).xml
- Klassinen, http://yle.fi/radiomanint/LiveXML/r01/item(%d).xml

Returns 404 if information does exist, for example there is no current song playing (%d==0)

Not always correct, depends on program.

Simple On-air information
=
JSON formated, compact information about previous, current and next program/song

- http://yle.fi/radio/resources/ajax/radio/onair-simple/10/6668480
- http://yle.fi/radio/resources/ajax/radio/onair-simple/11/6673347
- http://yle.fi/radio/resources/ajax/radio/onair-simple/12/6673356
- http://yle.fi/radio/resources/ajax/radio/onair-simple/20/6673344
- http://yle.fi/radio/resources/ajax/radio/onair-simple/21/6673346
- http://yle.fi/radio/resources/ajax/radio/onair-simple/30/6673361
- http://yle.fi/radio/resources/ajax/radio/onair-simple/40/6673362
- http://yle.fi/radio/resources/ajax/radio/onair-simple/41/6673341
- http://yle.fi/radio/resources/ajax/radio/onair-simple/42/6673342
- http://yle.fi/radio/resources/ajax/radio/onair-simple/50/6673350
- http://yle.fi/radio/resources/ajax/radio/onair-simple/51/6673348
- http://yle.fi/radio/resources/ajax/radio/onair-simple/60/6673351
- http://yle.fi/radio/resources/ajax/radio/onair-simple/61/6673349
- http://yle.fi/radio/resources/ajax/radio/onair-simple/62/6673353
- http://yle.fi/radio/resources/ajax/radio/onair-simple/70/6668506
- http://yle.fi/radio/resources/ajax/radio/onair-simple/71/6673352
- http://yle.fi/radio/resources/ajax/radio/onair-simple/80/6673360
- http://yle.fi/radio/resources/ajax/radio/onair-simple/81/6673358
- http://yle.fi/radio/resources/ajax/radio/onair-simple/90/6673355
- http://yle.fi/radio/resources/ajax/radio/onair-simple/91/6673354
- http://yle.fi/radio/resources/ajax/radio/onair-simple/93/6688542

Radio streams, http
=

Radio streams, rtsp
=
- rtsp://stream3.yle.mobi/yle/live/etelakarjala.sdp
- rtsp://stream3.yle.mobi/yle/live/etelakarjala128.sdp
- rtsp://stream3.yle.mobi/yle/live/etelakarjala256.sdp

- rtsp://stream3.yle.mobi/yle/live/etelasavo.sdp
- rtsp://stream3.yle.mobi/yle/live/etelasavo128.sdp
- rtsp://stream3.yle.mobi/yle/live/etelasavo256.sdp

- rtsp://stream3.yle.mobi/yle/live/itauusimaa.sdp
- rtsp://stream3.yle.mobi/yle/live/itauusimaa128.sdp
- rtsp://stream3.yle.mobi/yle/live/itauusimaa256.sdp

- rtsp://stream3.yle.mobi/yle/live/kainuu.sdp
- rtsp://stream3.yle.mobi/yle/live/kainuu128.sdp
- rtsp://stream3.yle.mobi/yle/live/kainuu256.sdp

- rtsp://stream3.yle.mobi/yle/live/keskipohjanmaa.sdp
- rtsp://stream3.yle.mobi/yle/live/keskipohjanmaa128.sdp
- rtsp://stream3.yle.mobi/yle/live/keskipohjanmaa256.sdp

- rtsp://stream3.yle.mobi/yle/live/keskisuomi.sdp
- rtsp://stream3.yle.mobi/yle/live/keskisuomi128.sdp
- rtsp://stream3.yle.mobi/yle/live/keskisuomi256.sdp

- rtsp://stream3.yle.mobi/yle/live/kymenlaakso.sdp
- rtsp://stream3.yle.mobi/yle/live/kymenlaakso128.sdp
- rtsp://stream3.yle.mobi/yle/live/kymenlaakso256.sdp
 
- rtsp://stream3.yle.mobi/yle/live/lahdenradio.sdp
- rtsp://stream3.yle.mobi/yle/live/lahdenradio128.sdp
- rtsp://stream3.yle.mobi/yle/live/lahdenradio256.sdp

- rtsp://stream3.yle.mobi/yle/live/lapinradio.sdp
- rtsp://stream3.yle.mobi/yle/live/lapinradio128.sdp
- rtsp://stream3.yle.mobi/yle/live/lapinradio256.sdp

- rtsp://stream3.yle.mobi/yle/live/ouluradio.sdp
- rtsp://stream3.yle.mobi/yle/live/ouluradio128.sdp
- rtsp://stream3.yle.mobi/yle/live/ouluradio256.sdp

- rtsp://stream3.yle.mobi/yle/live/peili.sdp
- rtsp://stream3.yle.mobi/yle/live/peili128.sdp
- rtsp://stream3.yle.mobi/yle/live/peili256.sdp

- rtsp://stream3.yle.mobi/yle/live/perameri.sdp
- rtsp://stream3.yle.mobi/yle/live/perameri128.sdp
- rtsp://stream3.yle.mobi/yle/live/perameri256.sdp

- rtsp://stream3.yle.mobi/yle/live/pohjanmaa.sdp
- rtsp://stream3.yle.mobi/yle/live/pohjanmaa128.sdp
- rtsp://stream3.yle.mobi/yle/live/pohjanmaa256.sdp

- rtsp://stream3.yle.mobi/yle/live/pohjkarjala.sdp
- rtsp://stream3.yle.mobi/yle/live/pohjkarjala128.sdp
- rtsp://stream3.yle.mobi/yle/live/pohjkarjala256.sdp

- rtsp://stream3.yle.mobi/yle/live/radio1.sdp
- rtsp://stream3.yle.mobi/yle/live/radio1128.sdp
- rtsp://stream3.yle.mobi/yle/live/radio1256.sdp

- rtsp://stream3.yle.mobi/yle/live/radio_suomi_b.sdp
- rtsp://stream3.yle.mobi/yle/live/radio_suomi_b128.sdp
- rtsp://stream3.yle.mobi/yle/live/radio_suomi_b256.sdp

- rtsp://stream3.yle.mobi/yle/live/radiohame.sdp
- rtsp://stream3.yle.mobi/yle/live/radiohame128.sdp
- rtsp://stream3.yle.mobi/yle/live/radiohame256.sdp

- rtsp://stream3.yle.mobi/yle/live/radiosavo.sdp
- rtsp://stream3.yle.mobi/yle/live/radiosavo128.sdp
- rtsp://stream3.yle.mobi/yle/live/radiosavo256.sdp

- rtsp://stream3.yle.mobi/yle/live/samiradio.sdp
- rtsp://stream3.yle.mobi/yle/live/samiradio128.sdp
- rtsp://stream3.yle.mobi/yle/live/samiradio256.sdp

- rtsp://stream3.yle.mobi/yle/live/satakunta.sdp
- rtsp://stream3.yle.mobi/yle/live/satakunta128.sdp
- rtsp://stream3.yle.mobi/yle/live/satakunta256.sdp

- rtsp://stream3.yle.mobi/yle/live/tampere.sdp
- rtsp://stream3.yle.mobi/yle/live/tampere128.sdp
- rtsp://stream3.yle.mobi/yle/live/tampere256.sdp

- rtsp://stream3.yle.mobi/yle/live/turunradio.sdp
- rtsp://stream3.yle.mobi/yle/live/turunradio128.sdp
- rtsp://stream3.yle.mobi/yle/live/turunradio256.sdp

Vega
- rtsp://stream3.yle.mobi/yle/live/vega_aboland.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_aboland128.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_aboland256.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_mellannyland.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_mellannyland128.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_mellannyland256.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_osterbotten.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_osterbotten128.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_osterbotten256.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_ostnyland.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_ostnyland128.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_ostnyland256.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_vastnyland.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_vastnyland128.sdp
- rtsp://stream3.yle.mobi/yle/live/vega_vastnyland256.sdp

X3M
- rtsp://stream3.yle.mobi/yle/live/x3m.sdp
- rtsp://stream3.yle.mobi/yle/live/x3m128.sdp
- rtsp://stream3.yle.mobi/yle/live/x3m256.sdp

- rtsp://stream3.yle.mobi/yle/live/ylenaikainen.sdp
- rtsp://stream3.yle.mobi/yle/live/ylenaikainen128.sdp
- rtsp://stream3.yle.mobi/yle/live/ylenaikainen256.sdp

Klassinen 
- rtsp://stream3.yle.mobi/yle/live/ylenklassinen.sdp
- rtsp://stream3.yle.mobi/yle/live/ylenklassinen128.sdp
- rtsp://stream3.yle.mobi/yle/live/ylenklassinen256.sdp

- rtsp://stream3.yle.mobi/yle/live/ylenlantinen.sdp
- rtsp://stream3.yle.mobi/yle/live/ylenlantinen128.sdp
- rtsp://stream3.yle.mobi/yle/live/ylenlantinen256.sdp

YLEX
- rtsp://stream3.yle.mobi/yle/live/ylex.sdp
- rtsp://stream3.yle.mobi/yle/live/ylex128.sdp
- rtsp://stream3.yle.mobi/yle/live/ylex256.sdp
- rtsp://stream3.yle.mobi/yle/live/ylexstudio.sdp
