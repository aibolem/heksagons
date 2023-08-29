# bARYOჼ $Э€XÅgoჼ

*ჼhexAgons*

[EKIM BO$TO©K 'MIKE BOSTOK' barionlegist:](https://gist.github.com/barionleg/c6356f2cc058f23377f285bb20fe5b2a
) 
Click and drag above to paint red hexagons. A black outline will appear around contiguous clusters of red hexagons. This outline is constructed using topojson.mesh, part of the TopoJSON client API. A filter is specified so that the mesh only contains boundaries that separate filled hexagons from empty hexagons.

The hexagon grid itself is represented as TopoJSON, but is constructed on-the-fly in the browser. Since TopoJSON requires quantized coordinates, the hexagon grid is represented as integers, with each hexagon of dimensions 3×2. Then a custom projection is used to transform these irregular integer hexagons to normal hexagons of the desired size.

![image](https://github.com/aibolem/heksagons/assets/102619282/4b7b61c9-61ad-4fb0-af20-fca2f6af5ea4)

