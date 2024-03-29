# Movie Project Read Me


### Team Members
Eric Landstein, [Kevin Sun ][1]

[1]:https://github.com/16kesun

### Project Goals
To see if there are any patterns that make a movie financially successful 
1. Are there any movies that have higher than average DVD or Blu-ray sales 
2. Is there a specific month that is best for a movie to be released 
3. Are there genres that perform better then others 

### Data
We scraped the movie data from https://www.the-numbers.com/ to get the following features 

- Movie Name 
- Domestic Box Office
- Rank 
- DVD Sales
- Blu Ray Sales 

### EDA 

We started by first looking at the month a movie was released to see if there was any positive or negetive financial impact. 

**Movie revenue by month**

From the data it is hard to determine if there is a best month to release a movie as April had the Avengers which was a big outlier.  Though it is safe to say that August was the worst performing month.  

![](https://github.com/Landstein/TopMovies/blob/master/images/Movie_release_month.png)

**Profitability**

For this category we looked at which movies had the best return on their investment.  

![](https://github.com/Landstein/TopMovies/blob/master/images/top_profit.png)

The Movies in Red are

- Bohemian Rhapsody
- A Star is born 
- A Quiet Place
- The Nun 
- Peter Rabbit
- Fifty Shades Freed 
- Green Book

**Genre**

Compared Genres that showed up in the movies that had the best revenue per budget against the other top 100 movies 

![](https://github.com/Landstein/TopMovies/blob/master/images/genre.png)

**Home Sales**

Lastly we looked at DVD and Blu Ray sales to see if there was any indicator of what type of movie has the best after theater sales.  Overall it was pretty consistant. 

![](https://github.com/Landstein/TopMovies/blob/master/images/homesales.png)

![](https://github.com/Landstein/TopMovies/blob/master/images/revenueandhomesales.png)

### Conclusions 

- The best performing genres were Drama, Horror, Music and Romance 
- Best Months to release a movie: April, June, July December 
- Worst Month to release a movie: August 
- If a movie is in the top 100 grossing for the year.  It will likely have good DVD / Blu Ray sales 

