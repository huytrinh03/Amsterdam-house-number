# Amsterdam-house-number
 Visualizing Amsterdam's house numbers using Python

 I get inspirations for this work from my exchange study in Amsterdam, as well as the work by Nicolas Kruchten's article on Montreal house numbers: https://nicolas.kruchten.com/content/2015/04/mtl_housenumbers/

 In this project, I queried data from the OpenStreetMap project with the help from its Overpass turbo Query Wizard. After obtaining the data, I clean them with pandas and plotted them using plotly. The resulting plot presents the Dutch capital's house numbers from 1 to 6000 with rainbow colors.

![image](https://github.com/huytrinh03/Amsterdam-house-number/assets/97802661/1099f9b3-6de1-436d-a3bb-3f5c0470f60e)

The general patterns that I personally see from this visualization:
- For the concentric demi-circle canal streets, the west end serves as zero points, and the housenumbers increase as one goes along the same canal
- In Jordaan, houses that are closest to Prinsengracht are zero-points.
- In Amsterdam Oud-West, zero-points are houses that are closest to the the curly Singelgracht, and housenumbers increase as one goes further away from it.
- On the Amstel river, housenumbers for houseboats increases as we go upstream, i.e. going further out from the city center
