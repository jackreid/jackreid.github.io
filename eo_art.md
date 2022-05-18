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

Nothing technically fancy this week, just combining some datasets that weren't probably intended to be combined. These use Conservation Science Partners (https://www.csp-inc.org/) ALOS Topographic Diversity & Global Human Modification datasets, plus the @CopernicusEU Global Land Service.


### Week 45 (2022-04-14): Luecke Signature Timelapse

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_04_14/vis_combo.gif">

Perhaps more historical oddity than art this week, but here is a timelapse of the "largest signature in the world," just north of Smithville, Texas. It's about 1km x 4km and has been around since the late 90s.

More info: https://www.atlasobscura.com/places/giant-luecke-signature

<img style="float: center;" width=800 src="/docs/assets/eo_art/2022_04_14/ind_combo.gif">

I couldn't resist making a psychedelic one using NDVI, the green band, and NDBI though!
