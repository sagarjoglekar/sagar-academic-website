+++
title = "Press cover for Facelift"
date = 2020-01-31T12:14:56+01:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["News","Urban Informatics"]
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

I am very happy to announce the publication of "FaceLift: a transparent deep learning framework to beautify urban scenes" in the Royal soceity open science journal
 
Facelift is a Deeplearning driven algorithm, that goes beyond assessing beauty in urban scenes (streetviews) -- as done by other studies in the field -- and recreates the elements that can make any given urban scene more beautiful. It then explains away the elements behind the beauty using metrics which are commonly understood by the target users of this system such as Urban Planners and Architects.
 
The study builds a model of urban beauty(X) using 20,000 street view images, and around 1 million votes from the crowds about the beauty of any given streetview. It then uses Generative Adversarial models, to mutate an input image into something that maximizes its beauty score for the model X.
The differences between the input and the output urban scenes are then explained using computer vision algorithms in terms of 5 urban design metric viz. Walkability, Greenery, Complexity, Openness and Landmarks.
 
We believe this system is the first step towards augmenting the urban planning industry using AI, and that too at the scale of an entire city.

This article has got some press attention too. Please find some coverages below :

Fast Company: [https://www.fastcompany.com/90455358/ai-can-now-design-cities-should-we-let-it](https://www.fastcompany.com/90455358/ai-can-now-design-cities-should-we-let-it)


Cosmos Magazine: [https://cosmosmagazine.com/technology/want-to-beautify-your-street-ask-a-computer](https://cosmosmagazine.com/technology/want-to-beautify-your-street-ask-a-computer)


You can find the paper and some resources around this project below:

Link to article: [https://royalsocietypublishing.org/doi/10.1098/rsos.190987](https://royalsocietypublishing.org/doi/10.1098/rsos.190987)
Link to interactive map: [https://goodcitylife.org/facelift/index.php](https://goodcitylife.org/facelift/index.php)