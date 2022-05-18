## Earth Observation Art

*Active March, 2021 to Present*

When working with remote observation imagery in my professional capacity, I would often unintentionally generate images that are strange, beautiful, funny, or otherwise visually interesting. Some of these are intermediate products, some are the results of bugs in my code or errors in the underlying datasets, some are result of an odd selection of bands or color palette. Typically these images have little to no scientific or application value, so I would quickly press on and leave these images behind.

One day, however, I wondered what would happen if I intentionally set out to make such images for their own sake. So that's what I set out to do in my free time: making some new piece of Earth Observation Art (almost) every week. It turns out that this endeavor resulted in a number of side benefits. It gave me opportunities to try out new datasets. It forced me to learn new analysis techniques in order to translate an idea into reality, It showed me just how wild and diverse our world is. But ultimately the reason why I keep doing it is that it keeps working with EO data fun.

I post these images on social media, namely [Twitter](https://twitter.com/jack_b_reid) and [Instagram](https://www.instagram.com/jack.b.reid/) each week, so if you see hashtags and @ in the descriptions for these pieces, that's what they refer to.

The primary platform I use for manipulating and generating these images is [Google Earth Engine](https://earthengine.google.com/). You can access the scripts for [each weekly project here](https://code.earthengine.google.com/?accept_repo=users/jackreid/art) (apologies for the lack of comments and overall terrible organization, but this ain't exactly a professional endeavor). Note that some of the assets that I used my not have permissions set properly, so if you can't get anything to run, just reach out via email or twitter. Some of the pieces also involve some python scripts run on my laptop. I haven't organized these into any repository yet. If that's important to you, reach out and I can move that up my list of priorities.

### Week 49 (2022-05-19): Ukraine Nightlights
<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_05_19/Feb_Median_Labeled.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_05_19/Mar_Median_Labeled.png">

Took a week off due to family visiting. This week is showing median decreases (shown in pink-red) in nightlights (yellow) in Ukraine during the first two months of the invasion, using the @NASAEarthData VIIRS VNP46A2 dataset.

### Week 48 (2022-05-05): Farm Comparison

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_05_05/poland_ndvi.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_05_05/us_ndvi.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_05_05/china_ndvi.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_05_05/australia_ndvi.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_05_05/brazil_ndvi.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_05_05/cote-d-ivoire_ndvi.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_05_05/india_ndvi.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_05_05/westIndia_ndvi.png">

Here are 8 @USGSLandsat  8 NDVI images of agricultural land from countries around the world (can you guess which is which?), all at the same scale. Really highlights the variation in land practices & potential dangers of training a ML model on just one region.


### Week 47 (2022-04-28): Texas Open Street Map Distances

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_04_28/i_wtr.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_04_28/i_twr.png">


Playing around with data from @openstreetmap this week. These images are based on distances to railroads, bodies of water, and public toilets in Texas. Are those pretty arbitrary? Definitely.

### Week 46 (2022-04-21): ALOS & Landcover

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_04_21/c_g_dc_mongolia.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_04_21/c_g_dc_US.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_04_21/c_g_ddi_MiddleEast.png">

Nothing technically fancy this week, just combining some datasets that weren't probably intended to be combined. These use Conservation Science Partners ([https://www.csp-inc.org/](https://www.csp-inc.org/)) ALOS Topographic Diversity & Global Human Modification datasets, plus the @CopernicusEU Global Land Service.


### Week 45 (2022-04-14): Luecke Signature Timelapse

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_04_14/vis_combo.gif">

Perhaps more historical oddity than art this week, but here is a timelapse of the "largest signature in the world," just north of Smithville, Texas. It's about 1km x 4km and has been around since the late 90s.

More info: [https://www.atlasobscura.com/places/giant-luecke-signature](https://www.atlasobscura.com/places/giant-luecke-signature)

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_04_14/ind_combo.gif">

I couldn't resist making a psychedelic one using NDVI, the green band, and NDBI though!

### Week 44 (2022-04-07):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_04_07/reversed.gif">

Nothing fancy this week. Just messing around with @Zhou_ISU et al.'s 1992-2020 DSMP-VIIRS nightlights harmonization (on a log scale) along with a changing color palette.

Definitely recommend checking out the dataset: [https://www.nature.com/articles/s41597-020-0510-y](https://www.nature.com/articles/s41597-020-0510-y)

### Week 43 (2022-03-31):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_03_31/mosaic.png">

Back after missing a week due to Atlanta Academy. Here is the @ASI_spazio's #hyperspectral PRISMA again, this time broken down using PCA (a first for me) and then combining those principal components (including the not-so-principal ones) in various ways.

### Week 42 (2022-03-17):
<video width=700 controls>
  <source type="video/mp4" src="/docs/assets/eo_art/2022_03_17/increment_full_combo.mp4">
</video>

Messing around with #hyperspectral imagery for the first time. This is an image of Midongy Du Sud National Park in Madagascar from @ASI_spazio's PRISMA satellite, iterating through various false color combos of its ~240 VNIR & SWIR bands.

### Week 41 (2022-03-10):
<video width=700 controls>
  <source type="video/mp4" src="docs/assets/eo_art/2022_03_10/editing-2500-6000.mp4">
</video>

A day late, sorry! I may have fallen in love with @NOAASatellites #GOES imagery. At some point I will diversify my data sources again, but in the meantime here are some false color infrared composites from #GOES17 and #GOES18!

### Week 40 (2022-03-03):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_03_03/purples_8.gif">

Yesterday @NOAASatellites #GOEST successfully launched. Soon it will magically become GOES-18. Today's piece is inspired the GOES-R Fire/Hot Spot dataset in #GEE. These circles are wildfires from late June 2020, scaled and colored based on temperature

### Week 39 (2022-02-24):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_02_24/output_compressed.gif">

In anticipation of the imminent launch of #GOEST, I am using @NOAASatellites' #GOES17 for the first time! This is a timelapse of my birthday in an NDVI-centric false color. Really shows the importance of accounting for lighting conditions in #EO!

### Week 38 (2022-02-17):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_02_17/bvn_100.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_02_17/unv_default.png">

A pair of images that combine the mean anomalies of nightlights, NDVI, NDBI, and blue band in different ways (ref period is 2015-16, obs period is 2017-2019). Data from @USGSLandsat 8 & VIIRS. Area is just south of Wuhan.

### Week 37 (2022-02-10):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_02_10/Macacu_mosaic.png">

A look at the Área De Proteção Ambiental Da Bacia Do Rio Macacu of the state of Rio de Janeiro in a few different ways, including SRTM elevation, #Sentinel 1 SAR, and @USGSLandsat 8 NDVI.


### Week 36 (2022-02-03):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_02_03/purple-green_med.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_02_03/red-blue_english.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_02_03/red-blue_hongkong.png">

Three visually distinct pieces made using very similar processes. These were all made using @ESA_EO #Sentinel 1 SAR to identify ships, then processing the results in various ways.


### Week 35 (2022-01-27):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_27/132_2.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_27/113_6.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_27/132_3.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_27/213_5.png">

These are some visualizations of land cover change in different parts of Brazil over the period 1985 - 2020, using the wonderful @mapbiomas dataset (which is directly available on #GoogleEarthEngine). Definitely recommend checking it out if you work in that part of the world.

### Week 34 (2022-01-13):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_13/caucus.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_13/chongqing1.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_13/india.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_13/northern_india.png">

I tried out a few things this week but ultimately settled on something rather simple: log-scale of VIIRS nightlights (to bring out the detail) + a color palette that I like. These are from a few different places around the world, some more obvious than others.

### Week 33 (2022-01-06):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_06/austin_bcc.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_06/clouds_123.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_06/austin_cbv.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_06/austin_wbw.png">

Messing around with indices (vegetation, water, built up) and clouds in the area of my hometown, Austin, using @USGSLandsat 8.

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_06/dragon_wvc.png">

Lake Travis looks like a long-tongued dragon serpent, don't it? I spent a lot of time in the southeast corner of it as a child, but never really had a concept of its shape.


### Week 32 (2021-12-30):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_12_30/hyperion_15k.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_12_30/landsat.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_12_30/sent2.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_12_30/sent3.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_12_30/sent5_uv.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_12_30/sentinel1.png">

Happy New Years Week! When scientists use EO images, we often build seamless mosaics that blend images & hide boundaries. These pieces do the opposite, highlighting what different satellite tracks look like. Can you guess what satellite made each image?

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_12_30/sent3_partial3.png">

Also, a few weeks back, I shared by desktop image. Well that's now my *former* desktop image as it has been replaced by this Sentinel-3 OLCI mosaic. I just love the texture!


### Week 31 (2021-12-23):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_12_23/export6.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_12_23/edge_lowres.png">

Christmas is only a few days off, so here is a Greenland neon Christmas tree made using @polargeospatial's ArcticDEM Mosiac plus some edge detection.

Not very tree-like, but I also liked this intermediate image.

### Week N/A (2021-12-16):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_12_16/grand_canyon.png">

Too busy at #AGU21 for my weekly #EOArt post, so I am just going to leave the first satellite image that I processed (and my current desktop!) here. It's the Grand Canyon, but I honestly don't remember what instrument or what bands I used. #EarthEngine

### Week 30 (2021-12-09):

<video width=700 controls>
  <source type="video/mp4" src="/docs/assets/eo_art/2021_12_09/oklahoma_old_edited.mp4">
</video>

Nothing fancy, just liked using @USGSLandsat 1-3 last week, so ran it back. Since they lacked a blue band, I used a blue palette! The blocky parts are real, that's farmland north of OK City. The other artifacts, well that's just the old Landsat data acting up.


### Week 29 (2021-12-02):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_12_02/fade_looped.gif">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_12_02/cumulative_compressed.gif">

Got a pair of timelapse pieces for y'all. Both are representations of the Atlantic hurricane tracks from 1880 to 2018 based on NOAA HURDAT2. Some of them spiraled way off to the north out of frame! #earthengine

### Week N/A (2021-11-30):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_11_30/fullPark_ndvi_1984-Present_v3.gif">

A fun side project that I was asked to make today. This is @WaltDisneyWorld from 1972 (one year after it opened) to the present. Dark is water and built environment, bright is vegetation. Resolution improves in 1984. First time using @USGSLandsat 1-3!

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_11_30/fullPark_vis_1984-Present_v3.gif">

Here's the visual imagery (only going back to 1984)

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_11_30/disney.png">

And here's a labeled image so you know what you are looking at. Plenty of other locations of interest of course (including the lakes!) but this was getting busy enough as is.


### Week 28 (2021-11-25):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_11_25/finger_turkey.png">

Y'all remember painting hand turkeys as a child? Well I've done my best to recreate one in an appropriately jank fashion using the Finger Lakes of NY + Tuz Gölü of Turkey! Colors made by NDWI using @USGSLandsat. Happy Thanksgiving!


### Week 27 (2021-11-18):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_11_18/fwr2_30k.png">

I promise that I will do things other than distance maps at some point. This is the Sacramento area, compositing distance from water (MOD44W), distance from 2000-2020 wildfires (Globfire), & roads (TIGER, brightness based on road type, & a focal mean kernel).

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_11_18/roads.png">

I also like how the road band turned out by itself.


### Week 26 (2021-11-11):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_11_11/oae_10k.png">

When you got a hammer, all problems are nails. Doing a distance composite again. This time for the continental US, using distances from peaks, inland water, and bright nightlights.


### Week 25 (2021-11-04):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_11_04/mrw_11k.png">

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_11_04/rwm_11k.png">

Got something more directly inspired by my actual work today. Here we have a portion of the state of Rio de Janeiro, with distances to mangroves (Mapbiomas), bodies of water (GSWE), and major highways (SNV) constituting the RGB bands.


### Week 24 (2021-10-28):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_10_28/DutchPumpkin.png">

It's Halloween week so I put together a remote observation jack o'lantern! I made this by mosaicking different parts of the Netherlands with Sentinel 1 SAR imagery. The right eye is Vinkeveense Plassen and the mouth is Rotterdam, for instance. I leave the identification of the remainder as an exercise for the reader.


### Week 23 (2021-10-21):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_10_21/purples2_despeckle.gif">

This one is based on a timelapse of the White Nile River, just north of Rabak, in 3 month chunks from isolated fall of 2015 through winter of 2020, using the @USGSLandsat 8 water flag. Shoutout to @jstnbraaten, whose tutorial inspired this.

### Week 22 (2021-10-14):

<video width=700 controls>
  <source type="video/mp4" src="/docs/assets/eo_art/2021_10_14/fire_currents.mp4">
</video>

Another video! This has a foreground of large fires in the western US at a 6 month timescale as detected by the Aqua MYD14A2.006. Background is HYCOM ocean temps for North Atlantic over the course of a week.

Definitely dissatisfied with the relative slowness of the background relative to the foreground. A lesson learned.


### Week 21 (2021-10-07):

<video width=700 controls>
  <source type="video/mp4" src="/docs/assets/eo_art/2021_10_07/fourier.mp4">
</video>

For this one, I took @NASA_Landsat imagery of farmland around Clinton, IL in 2 month chunks from 2016-2018; computed NDVI to highlight the vegetation growth cycle; and then took the Fourier transform of each image.

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_10_07/ndvi.gif">

And here are the original NDVI images!


### Week 20 (2021-09-23):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_09_23/.png">


### Week 19 (2021-09-16):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_09_16/.png">


### Week 18 (2021-09-09):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_09_09/.png">


### Week 17 (2021-07-15):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_07_15/.png">


### Week 16 (2021-07-09):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_07_09/.png">


### Week 15 (2021-07-01):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_07_01/.png">


### Week 14 (2021-06-24):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_06_24/.png">


### Week 13 (2021-06-17):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_06_17/.png">

### Week 12 (2021-06-10):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_06_10/.png">


### Week 11 (2021-05-27):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_05_27/.png">


### Week 10 (2021-05-20):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_05_20/.png">


### Week 9 (2021-05-13):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_05_13/.png">


### Week 8 (2021-05-06):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_05_06/.png">


### Week 7 (2021-04-29):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_04_29/.png">


### Week 6 (2021-04-22):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_04_22/.png">


### Week 5 (2021-04-15):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_04_15/.png">


### Week 4 (2021-04-09):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_04_09/.png">


### Week 3 (2021-04-01):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_04_01/.png">


### Week 2 (2021-03-25):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_03_25/.png">


### Week 1 (2021-03-18):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2021_03_18/.png">
