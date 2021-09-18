+++
title = "Sensing the real world through NHS prescriptions data"
date = 2021-09-18T12:14:56+01:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["News"]
categories = []

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = ""
caption = ""
preview = true

+++

Researchers and practitioners intererested in geography of health, social dynamics, economics, and everything in between are always interested methods that use data to sense health outcomes in the real world. If one can create proxies for health, and map them on to geographical units, one could ask important questions such as:

a) How does health of an area relate with its socio-economic conditions?

b) Are there any temporal trends or periodicities in certain health outcomes?

c) What is the relationship between health indicators from the real world and the signals obtained from online data source like social media (e.g. as seen in this paper: http://social-dynamics.net/docs/icwsm-21.pdf )?

d) Do certain policy or demograhic factors make an area more suseptible to particular health conditions?

But in order to be creative with such questions, one needs a principled way to create proxies for health outcomes from official datasources, at scale, and map them onto geographical units. Unfortunately, most health data sources are highly protected, if not propreitary, and the processing steps required to translate raw data into geographical outcomes are tedious and often require domain knowledge.

Over the past 2 years at Bell Labs, I have been working on something that would partly solve these issues. The [NHS Prescriptions parser](https://github.com/sagarjoglekar/NHSPrescriptionsParser) allows practitioners to mine the openly available NHS prescriptions data to make geo-spatial estimates about health outcomes across England. A more detailed manual about the steps for usage can be found [here](https://medium.com/@SagarJoglekar/mapping-health-outcomes-at-the-scale-of-an-entire-nation-bbe0eb949eea)

