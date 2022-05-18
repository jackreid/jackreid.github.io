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

<video src="docs/assets/eo_art/2022_03_17/increment_full_combo.mp4" data-canonical-src="docs/assets/eo_art/2022_03_17/increment_full_combo.mp4 controls="controls" muted="muted" class="d-block rounded-bottom-2 width-fit">

Messing around with #hyperspectral imagery for the first time. This is an image of Midongy Du Sud National Park in Madagascar from @ASI_spazio's PRISMA satellite, iterating through various false color combos of its ~240 VNIR & SWIR bands.

### Week 41 (2022-03-10):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_03_10/.png">

### Week 40 (2022-03-03):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_03_03/.png">

### Week 39 (2022-02-24):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_02_24/.png">

### Week 38 (2022-02-17):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_02_17/.png">

### Week 37 (2022-02-10):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_2_10/.png">

### Week 36 (2022-02-03):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_02_03/.png">

### Week 35 (2022-01-27):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_27/.png">

### Week 34 (2022-01-13):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_13/.png">

### Week 33 (2022-01-06):

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_01_06/.png">

### Week 32 (2021-12-30):


### Week 31 (2021-12-23):

### Week 30 (2021-12-09):

### Week 29 (2021-12-02):

### Week 28 (2021-11-25):

### Week 27 (2021-11-18):

### Week 26 (2021-11-11):

### Week 25 (2021-11-04):

### Week 24 (2021-10-28):

### Week 23 (2021-10-21):

### Week 22 (2021-10-14):

### Week 21 (2021-10-07):

### Week 20 (2021-09-23):

### Week 19 (2021-09-16):

### Week 18 (2021-09-09):

### Week 17 (2021-07-15):

### Week 16 (2021-07-09):

### Week 15 (2021-07-01):

### Week 14 (2021-06-24):

### Week 13 (2021-06-17):

### Week 12 (2021-06-10):

### Week 11 (2021-05-27):

### Week 10 (2021-05-20):

### Week 9 (2021-05-13):

### Week 8 (2021-05-06):

### Week 7 (2021-04-29):

### Week 6 (2021-04-22):

### Week 5 (2021-04-15):

### Week 4 (2021-04-09):

### Week 3 (2021-04-01):

### Week 2 (2021-03-25):

### Week 1 (2021-03-18):
