# Project Title

DSC160 Data Science and the Arts - Final Project - Generative Arts - Spring 2020

Project Team Members: 
- Amir Uqdah, auqdah@ucsd.edu
- Sabrina Ho, ssh026@ucsd.edu
- Xinrui Zhan, x5zhan@ucsd.edu
- Yiheng Ye, yiy291@ucsd.edu
- Byungheon Jeong, b1jeong@ucsd.edu


## Abstract

We want to represent the recoveries & deaths from the Covid-19 virus in the audio form. Then we want to use style transfer to make music from that sound. Many times, art has been utilized to portray traumatic and devastating moments in the human condition. Further, statistics often lose its descriptive power when viewed too often and the numbers are too detached from normal life. Therefore, we believe that creating art depicting the tragedy of this current pandemic is a critical aspect of making sure that these events are understood and remembered. 


Some challenges that might arise are we aren’t completely confident about the appropriateness of the music generated by the LSTM neural network, and since we do not have datasets that are large enough to build a proper LSTM network by ourselves, we may need to find trained LSTM to help us make the style transfer.


We will mainly use the dataset of COVID 19 in the USA: (https://www.kaggle.com/sudalairajkumar/covid19-in-usa; https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_US.csv).


	
 The data contains the number of cases and deaths in each county each day. We are still looking for related work and papers to figure out the methods we are gonna use for style mapping on music. Our first thought of dealing with those time series data is to use miditime to convert data to pieces of sound and then use LSTM and RNN to change the sound into music with conditional style (those related papers are listed below). The results that we hope to see are music that contains the style extracted from the COVID 19 dataset. For example, the music generated from death count should be involving mourning while the recovery number involves inspiring tunes.  


Links for papers and datasets:

- http://web.mit.edu/music21/
- https://pypi.org/project/miditime/
- http://mogren.one/publications/2016/c-rnn-gan/mogren2016crnngan.pdf
- https://arxiv.org/pdf/1708.03535.pdf
- https://www.kaggle.com/sudalairajkumar/covid19-in-usa
- https://github.com/CSSEGISandData/COVID-19?fbclid=IwAR01PCDa9EYqA-6jD-8LEEtfSjUTMxZcS6Dsv-cuPtFz8TiNTi8PDL1nf-U
- https://github.com/daQuincy/DeepMusicvStyle



## Data and Model

(10 points) 

In the final submission, this section will describe both the data you use for this project and any pre-existing models/neural nets. For each you should provide the name, a textual description, and a link. If there is a paper (for neural net) link that as well.
- Such and such Neural Net. The short description of this neural net. 
  - [link to code]().
  - [Title of Paper with Link](). 
- Training data. Short description of training data including bibliographic info. [link to data]().

## Code

(20 points)

This section will link to the various code for your project (stored within this repository). Your code should be executable on datahub, should we choose to replicate your result. This includes code for: 

- code for data acquisition/scraping
- code for preprocessing
- training code (if appropriate)
- generative methods

Link each of these items to your .ipynb or .py files within this seection, and provide a brief explanation of what the code does. Reading this section we should have a sense of how to run your code.

## Results

(30 points) 

This section should summarize your results and will embed links to documentation to significant outputs. This should document both process and show artistic results. This can include figures, sound files, videos, bitmaps, as appropriate to your generative art idea. Each result should include a brief textual description, and all should be listed below: 

- image files (`.jpg`, `.png` or whatever else is appropriate)
- audio files (`.wav`, `.mp3`)
- written text as `.pdf`

## Discussion

(30 points, three to five paragraphs)

The first paragraph should be a short summary describing your results.

The subsequent paragraphs could address questions including:
- Why is this culturally innovative?
- How does your generative computational approach differ from traditional art/music/cultural production? 
- How do your results relate to broader social, cultural, economic political, etc., issues? 
- What are the ethical concerns for this form of generative art? 
- In what future directions could you expand this work?

## Team Roles

Provide an account of individual members and their efforts/contributions to the specific tasks you accomplished.

## Technical Notes and Dependencies

Any implementation details or notes we need to repeat your work. 
- Additional libraries you are using for this project
- Does this code require other pip packages, software, etc?
- Does this code need to run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

All references to papers, techniques, previous work, repositories you used should be collected at the bottom:
- Papers
- Repositories
- Blog posts
