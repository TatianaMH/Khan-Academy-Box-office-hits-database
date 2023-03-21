# Khan-Academy-Box-office-hits-database
I will be pulling different data from different movies in this project

[Link to finished project](https://www.khanacademy.org/computer-programming/spin-off-of-challenge-box-office-hits-database/5742889621831680)

**STEP ONE I need to select just the names out of all the prewritten code these are the steps I use to get the data I need**
SELECT * FROM movies;

**STEP TWO now it is asking me add another query to filter by a certain year given and in DESC order**
SELECT * FROM movies WHERE release_year > 2000 
ORDER BY release_year;
