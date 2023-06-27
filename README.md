# DAI5 EDA Case Study: Youtube Analytics

### Authors:

  * Makhi Richburg
  * Joel Himes
  * Robert Ebend
  * Ben MacDonald


## Project Goal 


* Finding common traits of high view count

* Finding the top 5 (or 10) categories to advertise to


## Benefit of Exploratory Data Analysis

* Knowing this will help us make more strategically targeted decisions

* Company can choose which criteria they want for direction of ad revenue

* Company can gain more reach in specific sectors.


## Describe the data

* The data consists of metrics related to individual videos uploaded to Youtube.

* * run df.describe on either json or csv to generate summary stats for dataset. Snip pic of dataset summary stats to highlight high level overview.


## 	What features (columns) did you have to work with? 

There are 16 columns:

* video_id
* trending_date
* title
* channel_title
* category_id
* publish_time
* tags
* views
* likes
* dislikes
* comment_count
* thumbnail_link
* comments_disabled
* rating_disabled
* video_error_or_removed
* description


## What features were you interested in?

* views, likes, dislikes(engagement meter), categories, tags

* why are we interested in these?


## Were the features numerical/categorical/text?

* mixture of all three 

* give snippet or example of each type

## Was a lot of data missing? (If so, what did you do to handle it?)

* minimal data missing 

* show snippet of the \n rows


## How did features relate to each other, and the values that you were interested in?

* first/second plot

* poss corr matrix, heatmap, and hist


## Use plots to clearly communicate the data's story to stakeholders.

* more plots 
* anything that specifically helps tell our story and our obj’s


## STEPS

Goal:

1. Finding the top 5 categories to advertise to by looking at views

2. For each category:
Find top 20-50 videos (or 100 if there is that many)
Find the correlations for each
(Find Common traits for each)

3. Determine if there is a different trend criteria for each category by analyzing the correlation matrixes 


4. Establish the top 5 channels for each category that should be advertised to.

Graph types:

Find the top 5 categories to advertise to.
* Bar graph
    * x-axis is categories
    * y-axis is view count

Top 20 (or 100) videos for each category
* Barh graph
* video_id on the y-axis
* views on x-axis

Correlation matrix for top videos on each category(should have 5 total)

Created a slide that shows all correlation matrixes and visually determine commonalities

Find the top 5 channels from each categories to advertise to.
* Bar graph
  *  x-axis is channels
  *  y-axis is *column that had the highest correlation with view count*


Finding common traits of high view count.
* Correlation matrix
    * is there a correlation between views and:
      *  amount of tags
      *  description length 
        



