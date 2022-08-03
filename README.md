<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Mapping Racism and Resistance: A digital exhibit to accompany the 52nd Annual Morris Fromkin Memorial Lecture"
       author="UWM Libraries"
       banner="https://upload.wikimedia.org/wikipedia/commons/5/54/Apl-demographics-segregation-milwaukee-redlining-holc-map-crop.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q6662268"> <!-- Lloyd Barbee -->
<param ve-entity eid="Q7918759"> <!-- Vel Phillips -->
<param ve-entity eid="Q1453838"> <!-- redlining -->
<param ve-entity eid="Q186356"> <!-- New Deal -->

## Video

You can also include Kaltura Mediaspace videos by using the param ve-iframe code and the embeding code from Kaltura. This is a WTMJ reports video from our WTMJ channel.
<param ve-iframe id="kaltura mediaspace" src="https://cdnapisec.kaltura.com/p/2370711/sp/237071100/embedIframeJs/uiconf_id/42909941/partner_id/2370711?iframeembed=true&playerId=kaltura_player&entry_id=1_3euc8iny&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=1_cambmsxn" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="WTMJ_reports_SR482_cs">    

## add an image using ve-image url

url: The URL to the image file. This is not required or used if a manifest option is provided. When using a IIIF image separate from a manifest, /info.json must be appended to the image URL. When using an image URL the highest quality version of the image should be used when multiple versions are available, such as when using a Wikimedia Commons image.

<param ve-image 
       url="https://collections.lib.uwm.edu/digital/iiif/kal/1211/full/pct:50/0/default.jpg">

## add an image using ve-image manifest

manifest: The URL to an existing IIIF presentation manifest for the image, if one exists.

<param ve-image 
       manifest="https://collections.lib.uwm.edu//digital/iiif-info/kal/1227/manifest.json" seq="2" layers="true">
       
## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

## Racially restrictive real estate covenants

Property deeds and real estate covenants govern restrictions on the use of property. During the early to mid-twentieth century, these documents were often used to prevent people who were not white from buying property in certain areas.[^1]
<param ve-image 
       manifest="https://liblamp.uwm.edu/IIIF/manifest/manifest1499.json">
       
The covenant pictured here is from the Lloyd Barbee Papers in the UWM Archives. This covenant, dated June 1940, restricts occupancy to white people, but makes an exception for "domestic servants domiciled with an owner or tenant." Such a clause not only restricts ownership, but assigns an "acceptable" role for non-whites who enter the neighborhood. 
<param ve-image 
       manifest="https://liblamp.uwm.edu/IIIF/manifest/manifest1499.json">

## Redlining

This 1938 map of Milwaukee was created by Home Owners' Loan Corporation - a federal agency created as part of the New Deal to help stabilize the home mortgage market. But it also introduced the concept of redlining. Neighborhoods were designated by different grades meant to signify investment risk. These grades effectively outlined the racial contours of the city and systematially embedded economic disadvantages by making it difficult or impossible to secure home loans in areas deemed low ("third" or "fourth") grade. 
<param ve-image 
       manifest="https://cdm17272.contentdm.oclc.org/iiif/info/agdm/3028/manifest.json">       

## Black residential segregration - 2000 census

Map plotting black residential segregation according to data from the 2000 United States census.
<param ve-image 
       manifest="https://upload.wikimedia.org/wikipedia/commons/4/4a/2000census-_Black_Residential_Segregation.JPG">

# References

[^1]: [What are Coventants? University of Minnesota: Mapping Prejudice](https://mappingprejudice.umn.edu/what-are-covenants/)

Links [March on Milwaukee](https://uwm.edu/marchonmilwaukee/)
