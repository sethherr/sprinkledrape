I wanted a shower curtain with a map of the world with [a projection](https://xkcd.com/977/) other than Mercator.

I couldn't find one (in my lazy search) that was an interesting projection and covered the whole curtain. Since it's possible to print anything because the internet, I decided to make my own.

I decided on a tessellated [Peirce quincuncial projection](https://en.wikipedia.org/wiki/Peirce_quincuncial_projection), e.g.

<a href="https://en.wikipedia.org/wiki/Peirce_quincuncial_projection#/media/File:Peirce_quincuncial_projection_SW_20W_tiles.JPG"><img src="examples/wikipedia.jpg" alt="Tessellated Peirce quincuncial projection from Wikipedia" width="200px"></a>

Since custom, might as well go all in, programming ftw! [Link to page with all the examples](https://sethherr.github.io/sprinkledrape)

## Tessellated map

Use [d3-geo-projection](https://github.com/d3/d3-geo-projection)

Some resources:

- [Mike Bostock's Peirce Quincuncial example](https://bl.ocks.org/mbostock/4310087)
- [Jason Davies tessellated beauty](https://www.jasondavies.com/maps/peirce/)


First - [I copied](https://sethherr.github.io/sprinkledrape/jasondavies) what Jason Davies did (including stealing [his topojson](https://www.jasondavies.com/maps/world-50m.json)).

## What do the maps show?

It would be cool if the maps each showed something different and interesting. Some things I think might be interesting:

- Country names
- Water
- Population
- Wealth
