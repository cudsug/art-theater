# Analyzing Art Theater data

## Organization Name
The Art Theater

## Overview
The Art Theater is a one-screen Art House theater that programs its films for a combination of fulfilling its mission and keeping the business operating through ticket and concessions sales.  

## Problem Statement
Choosing films is a difficult process, as theaters must select movies well in advance – and strategy is necessary to choose the right films for the right amount of time.  

A wonderful part of the theater business is a constant stream of new content, plus rich data in the attendance and revenue details of each showing.  


1.	How can this data be mined for lessons about future bookings?  How are characteristics of films linked to their performance?

2.	What sort of metrics can the theater use to know how it is performing – either against itself or against its peers?  

•	The good: There are open APIs with IMDB-like data (https://rapidapi.com/imdb/api/movie-database-imdb-alternative) 
•	The bad: to get box office results by week, we're looking at paid services.  I traded e-mails with these guys -> https://www.opusdata.com/   At this point, they provided me with a sample database of what we could get for about $1,000.  It's what we'd want, but it's $1,000.  

1) You can get overall total grosses using Box Office Mojo's API: https://www.boxofficemojo.com/about/data.htm
2) All the cool kids are into screen scraping.  (Not me, but I hear it's popular...)  So I'm thinking they could do some amount of screen scraping from the weekly totals https://www.boxofficemojo.com/movies/?page=weekly&id=rbg.htm or even daily totals: https://www.boxofficemojo.com/movies/?page=daily&view=chart&id=rbg.htm 


## Evaluation criteria

For each the diagnostic or predictive focus areas, the evaluation will be determined by the use of available data from the Art Theater, linked to movie data from external sources, to provide evidence for your recommendation or findings.

## Data Details


