# census-drops

[![Hippocratic License HL3-CL-ECO-EXTR-FFD-LAW-MIL-SV](https://img.shields.io/static/v1?label=Hippocratic%20License&message=HL3-CL-ECO-EXTR-FFD-LAW-MIL-SV&labelColor=5e2751&color=bc8c3d)](https://firstdonoharm.dev/version/3/0/cl-eco-extr-ffd-law-mil-sv.html)

On May 22, 2023, [Robert L. Santos](https://www.census.gov/newsroom/bios/robert-santos.html), 
the Director of the U.S. Census Bureau,
wrote a blog post entitled, 
[Valuable New Datasets on Race and Ethnicity From the U.S. Census Bureau](https://www.census.gov/newsroom/blogs/director/2023/05/race-ethnicity-datasets.html?utm_medium=email&utm_source=govdelivery).
In the post, he announced that the Census Bureau would be publishing 
a number of new data sets covering
race, ethnicity, and housing over the remainder of 2023. These are going
to be fantastically rich data sets that will be incredibly valuable
to researchers in a variety of domains.

One of the [design goals](https://github.com/vengroff/censusdis/blob/main/design-goals.md) of the 
[censusdis](https://github.com/vengroff/censusdis)
project was to go beyond simply providing a Python
interface to the widely used [American Community Survey (ACS)], 
but also enable users to download and work with data from any of the
hundreds of other data sets the U.S. Census bureau publishes. This includes
data sets that weren't even published when censusdis was written.
In order to test the hypothesis that we have acheived this goal, we are 
going to use this project to demonstrate, ideally within days of their
publication, that we can download and work with these new data sets.

The first data set dropped on May 25, 2023. It was the 
[2020 Census Demographic and Housing Characteristics File (DHC)](https://www.census.gov/data/tables/2023/dec/2020-census-dhc.html).
On May 30, we created the first demo notebook in this project,
[demo notebook](https://github.com/vengroff/census-drops/blob/main/DHC%20Demo.ipynb),
which illustrates how to
download data from this data set with censusdis.

As the various additional data sets mentioned in Santos' blog post are
published, we intend to follow up with additional demo notebooks 
as part of this project. If necessary, we will modify and enhance censusdis
to work with them, but our hope is that it will be able to handle all of
them out of the box, with no additional extensions or modifications.

You can run the demo notebook, courtesy of [mybinder.org](https://mybinder.org/),
by following the following link:

- [2020 Census Demographic and Housing Characteristics File (DHC)](https://mybinder.org/v2/gh/vengroff/census-drops/HEAD?labpath=DHC%20Demo.ipynb)


