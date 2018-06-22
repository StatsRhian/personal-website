+++
title = "Efficient Analysis of Data Streams"
date = 2017-06-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Rhian Davies"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication = "PhD Thesis"
#publication_short = "In *PROBAB ENG INFORM SC*"

# Abstract and optional shortened version.
abstract = "Data streams provide a challenging environment for statistical analysis. Data points can arrive at a high velocity and may need to be deleted once they have been observed. Due to these restrictions, standard techniques may not be applicable to the data streaming scenario. This leads to the need for data summaries to represent the data stream. This thesis explores how data summaries can be used to perform clustering and classification on data streams across a broad range of applications. Spectral clustering is one such technique which prior to this work has not been applicable to the data streaming setting due to the high computation involved. CluStream is an existing method which uses micro-clusters to summarise data streams. We present two algorithms which utilise these micro-cluster summaries to enable spectral clustering to be performed on data streams. The methods were tested on simulated data streams, as well as textured images and hand-written digits. Distributed acoustic sensing is used to monitor oil flow at various depths throughout an oil well. Vibrations are recorded at very high resolutions, up to 10000 observations a second at each depth. Unfortunately, corruption can occur in the signal and engineers need to know where corruption occurs. We develop a method which treats the multiple time series as a high-dimensional clustering problem and uses the cluster labels to identify changes within the signal. The final piece of work concerns identifying areas of activity within a video stream, in particular CCTV footage. It is more efficient if this classification stage is performed on a compressed version of the video stream. In order to reconstruct areas of activity in the original video a recovery algorithm is needed. We present a comparison of the performance of two recovery algorithms and identify an ideal range for the compression ratio."
# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "http://eprints.lancs.ac.uk/88556/1/2017daviesphd.pdf"
#url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++
