<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Lucretia Mott"
       author="James Truitt"
       banner="https://digitalcollections.tricolib.brynmawr.edu/iiif/2/sc:262376~JP2~/full/pct:100/0/default.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->
<param ve-entity eid="Q267107"> <!-- Lucretia Mott -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference. Lucretia Mott.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

Lucretia Mott was a rad women's rights activist.[^1]
<param ve-compare curtain 
       url="https://stor.artstor.org/stor/10970784-2155-498d-8b05-d8586b1f67d0" 
       label="Lucretia Mott 1">
<param ve-compare 
       url="https://stor.artstor.org/stor/1420f054-9ba2-427b-b007-6aa22a7e785d" 
       label="Cafe Nero High Street (pre 1918)" 
       description="Canterbury High Street. Unposted and with no identifying features." 
       license="No Known Copyright">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map zoom="5" 
       center="39.833333, -98.583333"
       marker-type="circle"
       radius="4" 
       stroke-width="0"
       fill="blue" 
       fill-opacity="1">
<param ve-map-layer geojson title="Blood Lead Levels" url="child_blood_lead_levels_by_ct.geojson">

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
