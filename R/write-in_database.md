# Write-in Database

The `Listen Local Write-in Database` collects, contrasts, and if
necessary, corrects information about musical artists, and music work
(recordings). We only collect information about commercially released
music, because in this case, the artist and their representatives made
the music with information public and publicly retrievable. The Write-In
Database therefore does not require consent from the artist or the
artist’s representative.

The Write-in Database is a very important starting point to monitor the
performance of the local (national or regional) repertoire and identify
programs that make the music less visible, or may result in late or
missed payments. It can be use separately, or together with the [Listen
Local Opt-In Database](/data/opt-in). The `Opt-In Database` contains all
information that requires explicit artist (or lawful representative)
consent for collection and use.

The database contains properties and variables. - Properties do not
change, or change infrequently (such as the name of an artist, which may
change over the course of life but can be seen stable.) We time-stamp
them with the entry date, and change them only if necessary. -
Variables, such as the number of Spotify or Instagram followers, change,
and we collect them regularly with timestamps.

## Cross-identification properties

We use cross-identification data to check properties and variables,
i.e. dynamically changing information about a musical artist or a music
work/recording in various web resources.

### Name authorities

One of the most frequent metadata problem on music streaming services is
name ambiguity. There are many artists named ‘Rain’. How can an
algorithm recommend the correct `Rain` to a user? How can we make sure
that the correct `Rain` is getting paid?

There are many national and international name authorities that give a
globally unique identifier for artists. Unfortunately, their use is not
mandatory yet in most web services. Name authorities are great starting
points to start name disambiguation.

Listen Local cross-checks identity data in the following services:

<table>
<thead>
<tr>
<th style="text-align:left;">
property
</th>
<th style="text-align:left;">
description
</th>
<th style="text-align:left;">
example
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P214" style="     " >VIAF
ID</a>
</td>
<td style="text-align:left;">
VIAF identifier for the Virtual International Authority File.
</td>
<td style="text-align:left;">
<a href="https://isni.oclc.org/xslt/DB=1.2//CMD?ACT=SRCH&IKT=8006&TRM=ISN%3A0000%200001%203319%203871" style="     " >Aistė
Smilgevičiūtė</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P227" style="     " >GND
ID</a>
</td>
<td style="text-align:left;">
GND identifier for names on the Deutsche Nationalbibliothek.
</td>
<td style="text-align:left;">
<a href="https://portal.dnb.de/opac.htm?method=simpleSearch&cqlMode=true&query=nid%3D131416480" style="     " >Valya
Balkanska</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P1828" style="     " >IPI
name number</a>
</td>
<td style="text-align:left;">
IPI identifier for names of composers, artist, and other relevant
parties.
</td>
<td style="text-align:left;">
<a href=" " style="     " > </a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P7859" style="     " >WorldCat
Identities ID</a>
</td>
<td style="text-align:left;">
Identified for the WorldCat bibliographic page.
</td>
<td style="text-align:left;">
<a href="https://worldcat.org/identities/lccn-nr2006020430/" style="     " >Antis
\[lccn-nr2006020430\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P646" style="     " >Freebase
ID</a>
</td>
<td style="text-align:left;">
Feebase ID for a page. We collect pages of musical artists.
</td>
<td style="text-align:left;">
<a href="https://www.google.com/search?kgmid=/m/03nxmn" style="     " >Antis
\[/m/03nxmn\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P244" style="     " >Library
of Congress authority ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the Library of Congress.
</td>
<td style="text-align:left;">
<a href="https://id.loc.gov/authorities/names/nr2006020430.html" style="     " >Antis
\[nr2006020430\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P268" style="     " >Bibliothèque
nationale de France ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the Bibliothèque Nationale de France.
</td>
<td style="text-align:left;">
<a href="https://catalogue.bnf.fr/ark:/12148/cb13895093v" style="     " >Jascha
Heifetz \[13895093v\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P8179" style="     " >Canadiana
Name Authority ID</a>
</td>
<td style="text-align:left;">
Identifier for the Canadiana Name Authority File.
</td>
<td style="text-align:left;">
<a href=" " style="     " > </a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P7400" style="     " >LibraryThing
author ID</a>
</td>
<td style="text-align:left;">
Identifier for an author on the LibraryThing web service.
</td>
<td style="text-align:left;">
<a href="https://www.librarything.com/author/heifetzjascha" style="     " >Jascha
Heifetz \[heifetzjascha\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P1005" style="     " >Portuguese
National Library author ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the Biblioteca Nacional de Portugal.
</td>
<td style="text-align:left;">
<a href=" " style="     " > </a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P1005" style="     " >Portuguese
National Library author ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the Biblioteca Nacional de Portugal.
</td>
<td style="text-align:left;">
<a href="" style="     " ></a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P4619" style="     " >National
Library of Brazil ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Brazil.
</td>
<td style="text-align:left;">
<a href=" " style="     " > </a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P4619" style="     " >National
Library of Brazil ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Brazil.
</td>
<td style="text-align:left;">
<a href="" style="     " ></a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P409" style="     " >Libraries
Australia ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Australia.
</td>
<td style="text-align:left;">
<a href="https://librariesaustralia.nla.gov.au/search/display?dbid=auth&id=35398062" style="     " >Jascha
Heifetz \[35398062\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:National Library of Sweden" style="     " >SELIBR
ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Sweden.
</td>
<td style="text-align:left;">
<a href="https://libris.kb.se/75kns39r43rcgfj" style="     " >Jascha
Heifetz \[306503\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P8189" style="     " >National
Library of Israel J9U ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Israel.
</td>
<td style="text-align:left;">
<a href="http://uli.nli.org.il/F/?func=find-b&local_base=NLX10&find_code=UID&request=987007262544605171" style="     " >Jascha
Heifetz \[987007262544605171\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P1368" style="     " >National
Library of Latvia ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Latvia.
</td>
<td style="text-align:left;">
<a href="https://kopkatalogs.lv/F/?func=direct&local_base=lnc10&doc_number=000061341" style="     " >Baiba
Skride \[000061341\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P7293" style="     " >PLWABN
ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Poland.
</td>
<td style="text-align:left;">
<a href="http://mak.bn.org.pl/cgi-bin/KHW/makwww.exe?BM=1&NU=1&IM=4&WI=9810600259505606" style="     " >Jascha
Heifetz \[9810600259505606\]</a>
</td>
</tr>
</tbody>
</table>

Many national libraries provide excellent national name authorities.

<table>
<thead>
<tr>
<th style="text-align:left;">
property
</th>
<th style="text-align:left;">
description
</th>
<th style="text-align:left;">
example
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P7400" style="     " >LibraryThing
author ID</a>
</td>
<td style="text-align:left;">
Identifier for an author on the LibraryThing web service.
</td>
<td style="text-align:left;">
<a href="https://www.librarything.com/author/heifetzjascha" style="     " >Jascha
Heifetz \[heifetzjascha\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P1005" style="     " >Portuguese
National Library author ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the Biblioteca Nacional de Portugal.
</td>
<td style="text-align:left;">
<a href=" " style="     " > </a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P1005" style="     " >Portuguese
National Library author ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the Biblioteca Nacional de Portugal.
</td>
<td style="text-align:left;">
<a href="" style="     " ></a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P4619" style="     " >National
Library of Brazil ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Brazil.
</td>
<td style="text-align:left;">
<a href=" " style="     " > </a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P4619" style="     " >National
Library of Brazil ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Brazil.
</td>
<td style="text-align:left;">
<a href="" style="     " ></a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P409" style="     " >Libraries
Australia ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Australia.
</td>
<td style="text-align:left;">
<a href="https://librariesaustralia.nla.gov.au/search/display?dbid=auth&id=35398062" style="     " >Jascha
Heifetz \[35398062\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:National Library of Sweden" style="     " >SELIBR
ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Sweden.
</td>
<td style="text-align:left;">
<a href="https://libris.kb.se/75kns39r43rcgfj" style="     " >Jascha
Heifetz \[306503\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P8189" style="     " >National
Library of Israel J9U ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Israel.
</td>
<td style="text-align:left;">
<a href="http://uli.nli.org.il/F/?func=find-b&local_base=NLX10&find_code=UID&request=987007262544605171" style="     " >Jascha
Heifetz \[987007262544605171\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P1368" style="     " >National
Library of Latvia ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Latvia.
</td>
<td style="text-align:left;">
<a href="https://kopkatalogs.lv/F/?func=direct&local_base=lnc10&doc_number=000061341" style="     " >Baiba
Skride \[000061341\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P7293" style="     " >PLWABN
ID</a>
</td>
<td style="text-align:left;">
Identifier issued by the National Library of Poland.
</td>
<td style="text-align:left;">
<a href="http://mak.bn.org.pl/cgi-bin/KHW/makwww.exe?BM=1&NU=1&IM=4&WI=9810600259505606" style="     " >Jascha
Heifetz \[9810600259505606\]</a>
</td>
</tr>
</tbody>
</table>

## Music streaming services

Our most important goal is to make sure that `Listen Local` artists can
be found and properly recommended by algorithms on various music
platforms. Currently we are connecting to the following services. At the
early stage of the project, we only trace and measure information on
Spotify.

<table>
<thead>
<tr>
<th style="text-align:left;">
property
</th>
<th style="text-align:left;">
description
</th>
<th style="text-align:left;">
example
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P2722" style="     " >Deezer
artist ID</a>
</td>
<td style="text-align:left;">
Identifier for a musical artist on Deezer.
</td>
<td style="text-align:left;">
<a href="https://www.deezer.com/en/artist/1548881" style="     " >Youniverse
\[1548881\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P4576" style="     " >Tidal
artist ID</a>
</td>
<td style="text-align:left;">
Identifier for a musical artist on Tidal.
</td>
<td style="text-align:left;">
<a href="https://tidal.com/browse/artist/8623" style="     " >Jascha
Heifetz \[8623\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P2397" style="     " >YouTube
channel ID</a>
</td>
<td style="text-align:left;">
Identifier for a musical artist channel on YouTube \[not the artist!\]
</td>
<td style="text-align:left;">
<a href="https://music.youtube.com/channel/UCyaNMr5nKhne0akW4_Wtk4A" style="     " >Baiba
Skride \[UCyaNMr5nKhne0akW4\_Wtk4A\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P1553" style="     " >Yandex
Music artist ID</a>
</td>
<td style="text-align:left;">
NA
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P1902" style="     " >Spotify
artist ID</a>
</td>
<td style="text-align:left;">
Identifier for a musical artist on Spotify.
</td>
<td style="text-align:left;">
<a href="https://open.spotify.com/artist/3QImtM6BEiNSC4ZP4DWaEf?" style="     " >Bears
and Hunters \[3QImtM6BEiNSC4ZP4DWaEf?\]</a>
</td>
</tr>
</tbody>
</table>

## Lyrics services

Lyrics is very important in many genres. People often want to sing along
a song, or want to look up a song by a few lines in the lyrics that they
like. The lyrics is a work on its own, and it is important to see if it
well-connected to music work and recording itself.

<table>
<thead>
<tr>
<th style="text-align:left;">
property
</th>
<th style="text-align:left;">
description
</th>
<th style="text-align:left;">
example
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P6351" style="     " >Genius
artist numeric ID</a>
</td>
<td style="text-align:left;">
Identifier for a musical artist on Genius.
</td>
<td style="text-align:left;">
<a href="https://genius.com/artists/Vaidas-baumila" style="     " >Vaidas
Baumila \[Vaidas-baumila\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P7194" style="     " >AZLyrics.com
artist ID</a>
</td>
<td style="text-align:left;">
Identifier for a musical artist on AZLyrics.
</td>
<td style="text-align:left;">
<a href="https://www.azlyrics.com/n/natalielarose.html" style="     " >Natalie
La Rose \[n/natalielarose\]</a>
</td>
</tr>
</tbody>
</table>

### Social media

Artists mainly connect to audiences via social media. Concert and
festival promoters, record labels often make decisions on working with
an artist on social media metrics. Social media data is very useful to
find new audience for the artist. We record information about the
following social media.

<table>
<thead>
<tr>
<th style="text-align:left;">
property
</th>
<th style="text-align:left;">
description
</th>
<th style="text-align:left;">
example
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P2013" style="     " >Facebook
ID</a>
</td>
<td style="text-align:left;">
Facebook identifier.
</td>
<td style="text-align:left;">
<a href="https://www.facebook.com/DONISMUSIC/?fref=ts" style="     " >Donis
\[DONISMUSIC\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P2002" style="     " >Twitter
username</a>
</td>
<td style="text-align:left;">
Twitter username excluding the @ symbol.
</td>
<td style="text-align:left;">
<a href="https://twitter.com/tenwallsmusic?lang=en" style="     " >Ten
Walls \[TenWallsMusic\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P2003" style="     " >Instagram
username</a>
</td>
<td style="text-align:left;">
Instagram username.
</td>
<td style="text-align:left;">
<a href="https://www.instagram.com/fume.musik/" style="     " >Maximilian
Oprishka \[fume.musik\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P2984" style="     " >Snapchat
username</a>
</td>
<td style="text-align:left;">
Snapchat username.
</td>
<td style="text-align:left;">
<a href="https://www.snapchat.com/add/taylorswift" style="     " >Taylor
Swift \[taylorswift\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P7085" style="     " >TikTok
username</a>
</td>
<td style="text-align:left;">
TikTok username excluding the @ symbol.
</td>
<td style="text-align:left;">
<a href="https://www.tiktok.com/@borobachkadosta?lang=en" style="     " >Boro
Purvi \[borobachkadosta\]</a>
</td>
</tr>
</tbody>
</table>

### Music information services

There are more than 100,000,000 songs competing for the attention of
music fans, radio curators, concert and festival promoters, playlist
editors, music editors for film and advertising.

Music services often rely on information about an artits or his/her work
from music information services. It is important to check if correct
(factual and well-structured) information is available about the artist
and works.

We are providing data health checks on various music information
services.

<table>
<thead>
<tr>
<th style="text-align:left;">
property
</th>
<th style="text-align:left;">
description
</th>
<th style="text-align:left;">
example
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P434" style="     " >MusicBrainz
artist ID</a>
</td>
<td style="text-align:left;">
Artist identifier on the MusicBrainz music information resource.
</td>
<td style="text-align:left;">
<a href="https://musicbrainz.org/artist/fbb72ddb-af9e-4c7b-9715-37e1631ccc5f" style="     " >Katarzia
\[fbb72ddb-af9e-4c7b-9715-37e1631ccc5f\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P5917" style="     " >Shazam
artist ID</a>
</td>
<td style="text-align:left;">
Artist name and identifier on the Shazam music discovery application.
</td>
<td style="text-align:left;">
<a href="https://www.shazam.com/artist/%D0%BC%D0%B8%D1%85%D0%B0%D0%B5%D0%BB%D0%B0-%D0%BC%D0%B0%D1%80%D0%B8%D0%BD%D0%BE%D0%B2%D0%B0/1019656066" style="     " >Михаела
Маринова \[михаела-маринова/1019656066\]</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P6911" style="     " >Dutch
Charts artist ID</a>
</td>
<td style="text-align:left;">
NA
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P6559" style="     " >Official
Charts artist ID</a>
</td>
<td style="text-align:left;">
NA
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P7672" style="     " >Musiikkituottajat
artist ID</a>
</td>
<td style="text-align:left;">
NA
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:left;">
<a href="https://www.wikidata.org/wiki/Property:P10372" style="     " >Offizielle
Deutsche Charts composer ID</a>
</td>
<td style="text-align:left;">
NA
</td>
<td style="text-align:left;">
</td>
</tr>
</tbody>
</table>

### Biographical & Career Properties

Biographical and career properties are very important to recommend and
artist, or the works/recordings of an artist to an appropriate local,
national or foreign (export audience.)

We collect location data about artists, and in some cases, their
works/recordings. We want to know where the artist was born, where is
the artist active, and if a particular work/recording has any
relationship with a location. This makes our music recommendation
location-aware.

### Lyrics properties

The lyrics properties are necessary for recommending the music or to
enforce local content guidelines. They may be needed to find the right
context for the work/recording.

-   `instrumental`: We mark instrumental music. In usch cases, the
    lyrics properies will be logically missing (i.e. not by omission or
    lack of access.)
-   `explicit`: The lyrics contains expressions that are not suitable
    for certain audiences, particularly where minors are present.
-   `language`: The language of vocal music is very important to find a
    proper audience for a song. We record the language property of the
    title and the lyrics. For multi-language lyrics, we will develop a
    special taxonomy.  
-   `hate speech`: The lyrics contains hate speech. Listen Local is
    committed to fight racism, xenophobia and hatred, and records
    works/recordings with hateful lyrics on a special table that is
    never recommended by our applications. Furthermore, we make steps to
    request the removal of such works from public platforms.

### Musicological properties

The musicological properties are necessary for recommending the music.
They may be needed to find the right context for the work/recording.

-   `key`: The main key of the recording (for Western music.)
-   `tempo`: The tempo of the music.

### Audio properties

The audio properties are necessary for recommending the music. They may
refer to sound qualities: often a recording must meet minimum
requirements or parameters to be included in a radio or streaming
playlist. Or, the audio qualities will be necessary to find the right
context for the work/recording.

-   `duration`: The length of a recording. (Works may have several
    recordings with different duration.)

### Rights management and economic properties

Rights management properties are necessary to collect use revenues for
the artist’s works (publishing side) or recordings (neighboring rights:
producer and performer royalties.)

From a policy perspective, such information is critical to implement
local content policies, such as enforcing local/national radio or
streaming quotas.

-   `isrc`: The unique international identifier of a commercially
    released recording. The ISRC code connects the producers and
    performers to a recorded performance of a work.
-   `isrc_country`: The country where the ISRC was registered.
-   `isrc_year`: The year when the ISRC was registered.
-   `iswc`: The unique international identifier of a music work
    (composition.) A work may have several (or no known) recorded
    performances. The ISWC code connects a music work to music artists
    who composed the work.
-   `label`: The music label that is known to manage the producer (and
    potentially performing) rights of a recording. Label representation
    is a variable, it may change time to time.
-   `publisher`: The music publisher that is known to manage the
    author’s rights (copyrights) of a music work. Publishing
    representation is a variable, it may change time to time.
