# Trade and Conflict over the Spilhaus World Ocean Map 

mention;  https://github.com/rtlemos/spilhaus/blob/main/spilhaus_sst.png ; https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/spilhaus-more-like-thrillhaus  
## Summary

It has long been a truism that the global trading system has rested on the development of a supporting naval power. Since the 19th century, Alfred Mahan’s emphasis on maritime power has influenced multiple aspiring super-powers to create navies that can circumnavigate the globe. The United States has resolved this contest in the post-1945 world order with a global network of overseas military bases and vessels. It has tacitly enforced the UN Convention on the Laws of the Sea (UNCLOS) through freedom of navigation operations and secured the transit of freighters.  


Since the relation between maritime trade and the US naval security guarantee has remained largely untested, it is uncertain how much of the former relies on the latter. As other tenets of the international trading system unravel, we wonder how maritime trade may be affected by a changing security guarantee.  The following maps serve as a starting point for problematizing the relationship between maritime trade and naval power.


 ## Maritime Trade Routes, Chokepoints, and Ports

 All maps imply some distortion of the object they represent. This is inevitable when projecting a three-dimensional body to a two-dimensional plane. How a cartographer “projects” a continent or an ocean on a surface is a choice that should obey the function of the map. It follows that a map of maritime trade should use a projection that prioritizes the representation of the seas.

 The Spilhaus projection –known as “the world according to fish”— unfolds the world’s oceans into one continuous view.  The projection accurately portrays bodies of water, but admits large distortions in the Earth’s land mass. The map below presents the world’s oceans as one single interconnected body of water surrounding Antarctica.These maps are based on the *Spilhaus* map projection made available by Ricardo T. Lemos via the [rtlemos/spilhaus GitHub repository](https://github.com/rtlemos/spilhaus) on GitHub :contentReference[oaicite:0]{index=0}.Specifically, the functions `make_spilhaus_xy_gridpoints`, `from_spilhaus_xy_to_lonlat`, `pretify_spilhaus_df`, and others are used to transform geographic coordinates into the Spilhaus projection :contentReference[oaicite:1]{index=1}.

This first map also uses global shipping lane shapefiles from **Global Shipping Lanes / Routes GIS Dataset** hosted on GitHub: [newzealandpaul/Shipping-Lanes](https://github.com/newzealandpaul/Shipping-Lanes) :contentReference[oaicite:0]{index=0}. The dataset provides global shipping lanes georeferenced from the CIA's _Map of The World’s Oceans_ (October 2012), reprojected into the Spilhaus projection. Chokepoints and ports were loaded from the IMF PortWatch dataset, with bubble sizes proportional to vessel traffic. It offers a global picture of how maritime trade flows through shipping routes that join different ports and cross chokepoints that concentrate traffic.

 <p align="center">
  <img src="maps/spilhaus_map_1.png" width="600"/>
</p>

Note above the density of trade routes on the North Atlantic and over the Pacific. These join Western Europe to the North American East Coast, and South East Asia (SEA) to the North American Western Coast. There are also to clusters of chokepoints, on SEA and around Europe. The three largest chokepoints, the Taiwan Strait, the Starit of Malacca, and the Strait of Korea. 

## Comparative Reach With and Without Dual-Purpose Ports 

 <p align="center">
  <img src="maps/spilhaus_map_2.2.png" width="700"/>
</p>



 <p align="center">
  <img src="maps/spilhaus_map_2.3.png" width="700"/>
</p>


## Trade Routes Overlaid on Smoothed Maritime Influence Map

 <p align="center">
  <img src="maps/spilhaus_map_3.png" width="700"/>
</p>
