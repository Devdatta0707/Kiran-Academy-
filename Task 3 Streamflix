# StreamFlix MySQL Challenge — Answer Key

All 47 tasks/challenges executed against the `streamflix.movies` table (30 records). Each entry shows the business requirement, the SQL query, and the actual result set.


## LEVEL 1 — Movie Detective

### Task 1
**Requirement:** Find all movies having rating greater than 8.

```sql
SELECT * FROM movies WHERE rating > 8;
```
| movie_id | title | genre | language | rating | price | views | release_year | director | production_company |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 101 | Avengers: Endgame | Action | English | 8.4 | 199 | 950,000 | 2019 | Anthony Russo & Joe Russo | Marvel Studios |
| 102 | 3 Idiots | Comedy | Hindi | 8.4 | 149 | 1,200,000 | 2009 | Rajkumar Hirani | Vinod Chopra Films |
| 103 | Drishyam | Thriller | Hindi | 8.2 | 129 | 850,000 | 2015 | Nishikant Kamat | Panorama Studios |
| 104 | Interstellar | Sci-Fi | English | 8.7 | 249 | 1,100,000 | 2014 | Christopher Nolan | Warner Bros. Pictures |
| 105 | KGF: Chapter 1 | Action | Kannada | 8.4 | 179 | 1,400,000 | 2018 | Prashanth Neel | Hombale Films |
| 106 | KGF: Chapter 2 | Action | Kannada | 8.4 | 199 | 1,800,000 | 2022 | Prashanth Neel | Hombale Films |
| 109 | Baahubali 2: The Conclusion | Epic | Telugu | 8.2 | 199 | 2,500,000 | 2017 | S. S. Rajamouli | Arka Media Works |
| 114 | Dangal | Sports | Hindi | 8.3 | 159 | 1,300,000 | 2016 | Nitesh Tiwari | Aamir Khan Productions |
| 115 | PK | Comedy | Hindi | 8.1 | 149 | 1,250,000 | 2014 | Rajkumar Hirani | Vinod Chopra Films |
| 116 | Munna Bhai M.B.B.S. | Comedy | Hindi | 8.1 | 99 | 900,000 | 2003 | Rajkumar Hirani | Vinod Chopra Films |
| 117 | Chhichhore | Comedy | Hindi | 8.3 | 129 | 1,050,000 | 2019 | Nitesh Tiwari | Fox Star Studios |
| 118 | Taare Zameen Par | Drama | Hindi | 8.3 | 119 | 780,000 | 2007 | Aamir Khan | Aamir Khan Productions |
| 119 | Zindagi Na Milegi Dobara | Drama | Hindi | 8.2 | 139 | 980,000 | 2011 | Zoya Akhtar | Excel Entertainment |
| 127 | Vikram | Action | Tamil | 8.3 | 189 | 1,450,000 | 2022 | Lokesh Kanagaraj | Raaj Kamal Films International |
| 129 | Kantara | Drama | Kannada | 8.2 | 149 | 1,350,000 | 2022 | Rishab Shetty | Hombale Films |

*Rows returned: 15*

### Task 2
**Requirement:** Find movies whose price is less than 150.

```sql
SELECT * FROM movies WHERE price < 150;
```
| movie_id | title | genre | language | rating | price | views | release_year | director | production_company |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 102 | 3 Idiots | Comedy | Hindi | 8.4 | 149 | 1,200,000 | 2009 | Rajkumar Hirani | Vinod Chopra Films |
| 103 | Drishyam | Thriller | Hindi | 8.2 | 129 | 850,000 | 2015 | Nishikant Kamat | Panorama Studios |
| 115 | PK | Comedy | Hindi | 8.1 | 149 | 1,250,000 | 2014 | Rajkumar Hirani | Vinod Chopra Films |
| 116 | Munna Bhai M.B.B.S. | Comedy | Hindi | 8.1 | 99 | 900,000 | 2003 | Rajkumar Hirani | Vinod Chopra Films |
| 117 | Chhichhore | Comedy | Hindi | 8.3 | 129 | 1,050,000 | 2019 | Nitesh Tiwari | Fox Star Studios |
| 118 | Taare Zameen Par | Drama | Hindi | 8.3 | 119 | 780,000 | 2007 | Aamir Khan | Aamir Khan Productions |
| 119 | Zindagi Na Milegi Dobara | Drama | Hindi | 8.2 | 139 | 980,000 | 2011 | Zoya Akhtar | Excel Entertainment |
| 121 | Dhoom | Action | Hindi | 6.6 | 109 | 720,000 | 2004 | Sanjay Gadhvi | Yash Raj Films |
| 122 | Dhoom 2 | Action | Hindi | 6.5 | 129 | 860,000 | 2006 | Sanjay Gadhvi | Yash Raj Films |
| 123 | Dhoom 3 | Action | Hindi | 5.4 | 149 | 920,000 | 2013 | Vijay Krishna Acharya | Yash Raj Films |
| 124 | Bahubali Returns | Fantasy | Hindi | 7.1 | 139 | 410,000 | 2020 | Demo Director | StreamFlix Originals |
| 125 | Robot | Sci-Fi | Tamil | 7.1 | 129 | 680,000 | 2010 | S. Shankar | Sun Pictures |
| 129 | Kantara | Drama | Kannada | 8.2 | 149 | 1,350,000 | 2022 | Rishab Shetty | Hombale Films |
| 130 | Charlie 777 | Adventure | Kannada | 8 | 139 | 740,000 | 2022 | Kiranraj K | Paramvah Studios |

*Rows returned: 14*

### Task 3
**Requirement:** Find all Hindi movies.

```sql
SELECT * FROM movies WHERE language = 'Hindi';
```
| movie_id | title | genre | language | rating | price | views | release_year | director | production_company |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 102 | 3 Idiots | Comedy | Hindi | 8.4 | 149 | 1,200,000 | 2009 | Rajkumar Hirani | Vinod Chopra Films |
| 103 | Drishyam | Thriller | Hindi | 8.2 | 129 | 850,000 | 2015 | Nishikant Kamat | Panorama Studios |
| 112 | Jawan | Action | Hindi | 6.9 | 199 | 2,200,000 | 2023 | Atlee | Red Chillies Entertainment |
| 113 | Pathaan | Action | Hindi | 5.8 | 179 | 1,600,000 | 2023 | Siddharth Anand | Yash Raj Films |
| 114 | Dangal | Sports | Hindi | 8.3 | 159 | 1,300,000 | 2016 | Nitesh Tiwari | Aamir Khan Productions |
| 115 | PK | Comedy | Hindi | 8.1 | 149 | 1,250,000 | 2014 | Rajkumar Hirani | Vinod Chopra Films |
| 116 | Munna Bhai M.B.B.S. | Comedy | Hindi | 8.1 | 99 | 900,000 | 2003 | Rajkumar Hirani | Vinod Chopra Films |
| 117 | Chhichhore | Comedy | Hindi | 8.3 | 129 | 1,050,000 | 2019 | Nitesh Tiwari | Fox Star Studios |
| 118 | Taare Zameen Par | Drama | Hindi | 8.3 | 119 | 780,000 | 2007 | Aamir Khan | Aamir Khan Productions |
| 119 | Zindagi Na Milegi Dobara | Drama | Hindi | 8.2 | 139 | 980,000 | 2011 | Zoya Akhtar | Excel Entertainment |
| 120 | War | Action | Hindi | 6.5 | 189 | 1,500,000 | 2019 | Siddharth Anand | Yash Raj Films |
| 121 | Dhoom | Action | Hindi | 6.6 | 109 | 720,000 | 2004 | Sanjay Gadhvi | Yash Raj Films |
| 122 | Dhoom 2 | Action | Hindi | 6.5 | 129 | 860,000 | 2006 | Sanjay Gadhvi | Yash Raj Films |
| 123 | Dhoom 3 | Action | Hindi | 5.4 | 149 | 920,000 | 2013 | Vijay Krishna Acharya | Yash Raj Films |
| 124 | Bahubali Returns | Fantasy | Hindi | 7.1 | 139 | 410,000 | 2020 | Demo Director | StreamFlix Originals |

*Rows returned: 15*

### Task 4
**Requirement:** Find movies having more than 1,000,000 views.

```sql
SELECT * FROM movies WHERE views > 1000000;
```
| movie_id | title | genre | language | rating | price | views | release_year | director | production_company |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 102 | 3 Idiots | Comedy | Hindi | 8.4 | 149 | 1,200,000 | 2009 | Rajkumar Hirani | Vinod Chopra Films |
| 104 | Interstellar | Sci-Fi | English | 8.7 | 249 | 1,100,000 | 2014 | Christopher Nolan | Warner Bros. Pictures |
| 105 | KGF: Chapter 1 | Action | Kannada | 8.4 | 179 | 1,400,000 | 2018 | Prashanth Neel | Hombale Films |
| 106 | KGF: Chapter 2 | Action | Kannada | 8.4 | 199 | 1,800,000 | 2022 | Prashanth Neel | Hombale Films |
| 107 | RRR | Action | Telugu | 8 | 199 | 2,100,000 | 2022 | S. S. Rajamouli | DVV Entertainment |
| 108 | Baahubali: The Beginning | Epic | Telugu | 8 | 179 | 1,900,000 | 2015 | S. S. Rajamouli | Arka Media Works |
| 109 | Baahubali 2: The Conclusion | Epic | Telugu | 8.2 | 199 | 2,500,000 | 2017 | S. S. Rajamouli | Arka Media Works |
| 110 | Pushpa: The Rise | Action | Telugu | 7.6 | 179 | 1,700,000 | 2021 | Sukumar | Mythri Movie Makers |
| 111 | Pushpa 2: The Rule | Action | Telugu | 6.1 | 199 | 2,300,000 | 2024 | Sukumar | Mythri Movie Makers |
| 112 | Jawan | Action | Hindi | 6.9 | 199 | 2,200,000 | 2023 | Atlee | Red Chillies Entertainment |
| 113 | Pathaan | Action | Hindi | 5.8 | 179 | 1,600,000 | 2023 | Siddharth Anand | Yash Raj Films |
| 114 | Dangal | Sports | Hindi | 8.3 | 159 | 1,300,000 | 2016 | Nitesh Tiwari | Aamir Khan Productions |
| 115 | PK | Comedy | Hindi | 8.1 | 149 | 1,250,000 | 2014 | Rajkumar Hirani | Vinod Chopra Films |
| 117 | Chhichhore | Comedy | Hindi | 8.3 | 129 | 1,050,000 | 2019 | Nitesh Tiwari | Fox Star Studios |
| 120 | War | Action | Hindi | 6.5 | 189 | 1,500,000 | 2019 | Siddharth Anand | Yash Raj Films |
| 127 | Vikram | Action | Tamil | 8.3 | 189 | 1,450,000 | 2022 | Lokesh Kanagaraj | Raaj Kamal Films International |
| 128 | Master | Action | Tamil | 7.3 | 159 | 1,120,000 | 2021 | Lokesh Kanagaraj | XB Film Creators |
| 129 | Kantara | Drama | Kannada | 8.2 | 149 | 1,350,000 | 2022 | Rishab Shetty | Hombale Films |

*Rows returned: 18*

### Task 5
**Requirement:** Find movies released after 2015.

```sql
SELECT * FROM movies WHERE release_year > 2015;
```
| movie_id | title | genre | language | rating | price | views | release_year | director | production_company |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 101 | Avengers: Endgame | Action | English | 8.4 | 199 | 950,000 | 2019 | Anthony Russo & Joe Russo | Marvel Studios |
| 105 | KGF: Chapter 1 | Action | Kannada | 8.4 | 179 | 1,400,000 | 2018 | Prashanth Neel | Hombale Films |
| 106 | KGF: Chapter 2 | Action | Kannada | 8.4 | 199 | 1,800,000 | 2022 | Prashanth Neel | Hombale Films |
| 107 | RRR | Action | Telugu | 8 | 199 | 2,100,000 | 2022 | S. S. Rajamouli | DVV Entertainment |
| 109 | Baahubali 2: The Conclusion | Epic | Telugu | 8.2 | 199 | 2,500,000 | 2017 | S. S. Rajamouli | Arka Media Works |
| 110 | Pushpa: The Rise | Action | Telugu | 7.6 | 179 | 1,700,000 | 2021 | Sukumar | Mythri Movie Makers |
| 111 | Pushpa 2: The Rule | Action | Telugu | 6.1 | 199 | 2,300,000 | 2024 | Sukumar | Mythri Movie Makers |
| 112 | Jawan | Action | Hindi | 6.9 | 199 | 2,200,000 | 2023 | Atlee | Red Chillies Entertainment |
| 113 | Pathaan | Action | Hindi | 5.8 | 179 | 1,600,000 | 2023 | Siddharth Anand | Yash Raj Films |
| 114 | Dangal | Sports | Hindi | 8.3 | 159 | 1,300,000 | 2016 | Nitesh Tiwari | Aamir Khan Productions |
| 117 | Chhichhore | Comedy | Hindi | 8.3 | 129 | 1,050,000 | 2019 | Nitesh Tiwari | Fox Star Studios |
| 120 | War | Action | Hindi | 6.5 | 189 | 1,500,000 | 2019 | Siddharth Anand | Yash Raj Films |
| 124 | Bahubali Returns | Fantasy | Hindi | 7.1 | 139 | 410,000 | 2020 | Demo Director | StreamFlix Originals |
| 126 | Enthiran 2.0 | Sci-Fi | Tamil | 6.2 | 169 | 760,000 | 2018 | S. Shankar | Lyca Productions |
| 127 | Vikram | Action | Tamil | 8.3 | 189 | 1,450,000 | 2022 | Lokesh Kanagaraj | Raaj Kamal Films International |
| 128 | Master | Action | Tamil | 7.3 | 159 | 1,120,000 | 2021 | Lokesh Kanagaraj | XB Film Creators |
| 129 | Kantara | Drama | Kannada | 8.2 | 149 | 1,350,000 | 2022 | Rishab Shetty | Hombale Films |
| 130 | Charlie 777 | Adventure | Kannada | 8 | 139 | 740,000 | 2022 | Kiranraj K | Paramvah Studios |

*Rows returned: 18*

### Task 6
**Requirement:** Find movies whose rating is between 8 and 8.5.

```sql
SELECT * FROM movies WHERE rating BETWEEN 8 AND 8.5;
```
| movie_id | title | genre | language | rating | price | views | release_year | director | production_company |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 101 | Avengers: Endgame | Action | English | 8.4 | 199 | 950,000 | 2019 | Anthony Russo & Joe Russo | Marvel Studios |
| 102 | 3 Idiots | Comedy | Hindi | 8.4 | 149 | 1,200,000 | 2009 | Rajkumar Hirani | Vinod Chopra Films |
| 103 | Drishyam | Thriller | Hindi | 8.2 | 129 | 850,000 | 2015 | Nishikant Kamat | Panorama Studios |
| 105 | KGF: Chapter 1 | Action | Kannada | 8.4 | 179 | 1,400,000 | 2018 | Prashanth Neel | Hombale Films |
| 106 | KGF: Chapter 2 | Action | Kannada | 8.4 | 199 | 1,800,000 | 2022 | Prashanth Neel | Hombale Films |
| 107 | RRR | Action | Telugu | 8 | 199 | 2,100,000 | 2022 | S. S. Rajamouli | DVV Entertainment |
| 108 | Baahubali: The Beginning | Epic | Telugu | 8 | 179 | 1,900,000 | 2015 | S. S. Rajamouli | Arka Media Works |
| 109 | Baahubali 2: The Conclusion | Epic | Telugu | 8.2 | 199 | 2,500,000 | 2017 | S. S. Rajamouli | Arka Media Works |
| 114 | Dangal | Sports | Hindi | 8.3 | 159 | 1,300,000 | 2016 | Nitesh Tiwari | Aamir Khan Productions |
| 115 | PK | Comedy | Hindi | 8.1 | 149 | 1,250,000 | 2014 | Rajkumar Hirani | Vinod Chopra Films |
| 116 | Munna Bhai M.B.B.S. | Comedy | Hindi | 8.1 | 99 | 900,000 | 2003 | Rajkumar Hirani | Vinod Chopra Films |
| 117 | Chhichhore | Comedy | Hindi | 8.3 | 129 | 1,050,000 | 2019 | Nitesh Tiwari | Fox Star Studios |
| 118 | Taare Zameen Par | Drama | Hindi | 8.3 | 119 | 780,000 | 2007 | Aamir Khan | Aamir Khan Productions |
| 119 | Zindagi Na Milegi Dobara | Drama | Hindi | 8.2 | 139 | 980,000 | 2011 | Zoya Akhtar | Excel Entertainment |
| 127 | Vikram | Action | Tamil | 8.3 | 189 | 1,450,000 | 2022 | Lokesh Kanagaraj | Raaj Kamal Films International |
| 129 | Kantara | Drama | Kannada | 8.2 | 149 | 1,350,000 | 2022 | Rishab Shetty | Hombale Films |
| 130 | Charlie 777 | Adventure | Kannada | 8 | 139 | 740,000 | 2022 | Kiranraj K | Paramvah Studios |

*Rows returned: 17*

### Task 7
**Requirement:** Find movies belonging to Action, Comedy or Thriller using IN.

```sql
SELECT * FROM movies WHERE genre IN ('Action','Comedy','Thriller');
```
| movie_id | title | genre | language | rating | price | views | release_year | director | production_company |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 101 | Avengers: Endgame | Action | English | 8.4 | 199 | 950,000 | 2019 | Anthony Russo & Joe Russo | Marvel Studios |
| 102 | 3 Idiots | Comedy | Hindi | 8.4 | 149 | 1,200,000 | 2009 | Rajkumar Hirani | Vinod Chopra Films |
| 103 | Drishyam | Thriller | Hindi | 8.2 | 129 | 850,000 | 2015 | Nishikant Kamat | Panorama Studios |
| 105 | KGF: Chapter 1 | Action | Kannada | 8.4 | 179 | 1,400,000 | 2018 | Prashanth Neel | Hombale Films |
| 106 | KGF: Chapter 2 | Action | Kannada | 8.4 | 199 | 1,800,000 | 2022 | Prashanth Neel | Hombale Films |
| 107 | RRR | Action | Telugu | 8 | 199 | 2,100,000 | 2022 | S. S. Rajamouli | DVV Entertainment |
| 110 | Pushpa: The Rise | Action | Telugu | 7.6 | 179 | 1,700,000 | 2021 | Sukumar | Mythri Movie Makers |
| 111 | Pushpa 2: The Rule | Action | Telugu | 6.1 | 199 | 2,300,000 | 2024 | Sukumar | Mythri Movie Makers |
| 112 | Jawan | Action | Hindi | 6.9 | 199 | 2,200,000 | 2023 | Atlee | Red Chillies Entertainment |
| 113 | Pathaan | Action | Hindi | 5.8 | 179 | 1,600,000 | 2023 | Siddharth Anand | Yash Raj Films |
| 115 | PK | Comedy | Hindi | 8.1 | 149 | 1,250,000 | 2014 | Rajkumar Hirani | Vinod Chopra Films |
| 116 | Munna Bhai M.B.B.S. | Comedy | Hindi | 8.1 | 99 | 900,000 | 2003 | Rajkumar Hirani | Vinod Chopra Films |
| 117 | Chhichhore | Comedy | Hindi | 8.3 | 129 | 1,050,000 | 2019 | Nitesh Tiwari | Fox Star Studios |
| 120 | War | Action | Hindi | 6.5 | 189 | 1,500,000 | 2019 | Siddharth Anand | Yash Raj Films |
| 121 | Dhoom | Action | Hindi | 6.6 | 109 | 720,000 | 2004 | Sanjay Gadhvi | Yash Raj Films |
| 122 | Dhoom 2 | Action | Hindi | 6.5 | 129 | 860,000 | 2006 | Sanjay Gadhvi | Yash Raj Films |
| 123 | Dhoom 3 | Action | Hindi | 5.4 | 149 | 920,000 | 2013 | Vijay Krishna Acharya | Yash Raj Films |
| 127 | Vikram | Action | Tamil | 8.3 | 189 | 1,450,000 | 2022 | Lokesh Kanagaraj | Raaj Kamal Films International |
| 128 | Master | Action | Tamil | 7.3 | 159 | 1,120,000 | 2021 | Lokesh Kanagaraj | XB Film Creators |

*Rows returned: 19*

### Task 8
**Requirement:** Find all movies directed by S. S. Rajamouli.

```sql
SELECT * FROM movies WHERE director = 'S. S. Rajamouli';
```
| movie_id | title | genre | language | rating | price | views | release_year | director | production_company |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 107 | RRR | Action | Telugu | 8 | 199 | 2,100,000 | 2022 | S. S. Rajamouli | DVV Entertainment |
| 108 | Baahubali: The Beginning | Epic | Telugu | 8 | 179 | 1,900,000 | 2015 | S. S. Rajamouli | Arka Media Works |
| 109 | Baahubali 2: The Conclusion | Epic | Telugu | 8.2 | 199 | 2,500,000 | 2017 | S. S. Rajamouli | Arka Media Works |

*Rows returned: 3*

### Task 9
**Requirement:** Find all movies produced by Hombale Films.

```sql
SELECT * FROM movies WHERE production_company = 'Hombale Films';
```
| movie_id | title | genre | language | rating | price | views | release_year | director | production_company |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 105 | KGF: Chapter 1 | Action | Kannada | 8.4 | 179 | 1,400,000 | 2018 | Prashanth Neel | Hombale Films |
| 106 | KGF: Chapter 2 | Action | Kannada | 8.4 | 199 | 1,800,000 | 2022 | Prashanth Neel | Hombale Films |
| 129 | Kantara | Drama | Kannada | 8.2 | 149 | 1,350,000 | 2022 | Rishab Shetty | Hombale Films |

*Rows returned: 3*

### Task 10
**Requirement:** Find all movies produced by Arka Media Works.

```sql
SELECT * FROM movies WHERE production_company = 'Arka Media Works';
```
| movie_id | title | genre | language | rating | price | views | release_year | director | production_company |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 108 | Baahubali: The Beginning | Epic | Telugu | 8 | 179 | 1,900,000 | 2015 | S. S. Rajamouli | Arka Media Works |
| 109 | Baahubali 2: The Conclusion | Epic | Telugu | 8.2 | 199 | 2,500,000 | 2017 | S. S. Rajamouli | Arka Media Works |

*Rows returned: 2*


## LEVEL 2 — Streaming Recommendation Team

### Task 11
**Requirement:** Find the 5 most viewed movies.

```sql
SELECT title, views FROM movies ORDER BY views DESC LIMIT 5;
```
| title | views |
| --- | --- |
| Baahubali 2: The Conclusion | 2,500,000 |
| Pushpa 2: The Rule | 2,300,000 |
| Jawan | 2,200,000 |
| RRR | 2,100,000 |
| Baahubali: The Beginning | 1,900,000 |

*Rows returned: 5*

### Task 12
**Requirement:** Find the 5 lowest-priced movies.

```sql
SELECT title, price FROM movies ORDER BY price ASC LIMIT 5;
```
| title | price |
| --- | --- |
| Munna Bhai M.B.B.S. | 99 |
| Dhoom | 109 |
| Taare Zameen Par | 119 |
| Drishyam | 129 |
| Chhichhore | 129 |

*Rows returned: 5*

### Task 13
**Requirement:** Display movies from highest rating to lowest rating.

```sql
SELECT title, rating FROM movies ORDER BY rating DESC;
```
| title | rating |
| --- | --- |
| Interstellar | 8.7 |
| Avengers: Endgame | 8.4 |
| 3 Idiots | 8.4 |
| KGF: Chapter 1 | 8.4 |
| KGF: Chapter 2 | 8.4 |
| Dangal | 8.3 |
| Chhichhore | 8.3 |
| Taare Zameen Par | 8.3 |
| Vikram | 8.3 |
| Drishyam | 8.2 |
| Baahubali 2: The Conclusion | 8.2 |
| Zindagi Na Milegi Dobara | 8.2 |
| Kantara | 8.2 |
| PK | 8.1 |
| Munna Bhai M.B.B.S. | 8.1 |
| RRR | 8 |
| Baahubali: The Beginning | 8 |
| Charlie 777 | 8 |
| Pushpa: The Rise | 7.6 |
| Master | 7.3 |
| Bahubali Returns | 7.1 |
| Robot | 7.1 |
| Jawan | 6.9 |
| Dhoom | 6.6 |
| War | 6.5 |
| Dhoom 2 | 6.5 |
| Enthiran 2.0 | 6.2 |
| Pushpa 2: The Rule | 6.1 |
| Pathaan | 5.8 |
| Dhoom 3 | 5.4 |

*Rows returned: 30*

### Task 14
**Requirement:** Display only unique movie languages using DISTINCT.

```sql
SELECT DISTINCT language FROM movies;
```
| language |
| --- |
| English |
| Hindi |
| Kannada |
| Telugu |
| Tamil |

*Rows returned: 5*

### Task 15
**Requirement:** Display Movie and Rating using aliases Movie and IMDb_Rating.

```sql
SELECT title AS Movie, rating AS IMDb_Rating FROM movies;
```
| Movie | IMDb_Rating |
| --- | --- |
| Avengers: Endgame | 8.4 |
| 3 Idiots | 8.4 |
| Drishyam | 8.2 |
| Interstellar | 8.7 |
| KGF: Chapter 1 | 8.4 |
| KGF: Chapter 2 | 8.4 |
| RRR | 8 |
| Baahubali: The Beginning | 8 |
| Baahubali 2: The Conclusion | 8.2 |
| Pushpa: The Rise | 7.6 |
| Pushpa 2: The Rule | 6.1 |
| Jawan | 6.9 |
| Pathaan | 5.8 |
| Dangal | 8.3 |
| PK | 8.1 |
| Munna Bhai M.B.B.S. | 8.1 |
| Chhichhore | 8.3 |
| Taare Zameen Par | 8.3 |
| Zindagi Na Milegi Dobara | 8.2 |
| War | 6.5 |
| Dhoom | 6.6 |
| Dhoom 2 | 6.5 |
| Dhoom 3 | 5.4 |
| Bahubali Returns | 7.1 |
| Robot | 7.1 |
| Enthiran 2.0 | 6.2 |
| Vikram | 8.3 |
| Master | 7.3 |
| Kantara | 8.2 |
| Charlie 777 | 8 |

*Rows returned: 30*

### Task 16
**Requirement:** Display movie title, director and production company only.

```sql
SELECT title, director, production_company FROM movies;
```
| title | director | production_company |
| --- | --- | --- |
| Avengers: Endgame | Anthony Russo & Joe Russo | Marvel Studios |
| 3 Idiots | Rajkumar Hirani | Vinod Chopra Films |
| Drishyam | Nishikant Kamat | Panorama Studios |
| Interstellar | Christopher Nolan | Warner Bros. Pictures |
| KGF: Chapter 1 | Prashanth Neel | Hombale Films |
| KGF: Chapter 2 | Prashanth Neel | Hombale Films |
| RRR | S. S. Rajamouli | DVV Entertainment |
| Baahubali: The Beginning | S. S. Rajamouli | Arka Media Works |
| Baahubali 2: The Conclusion | S. S. Rajamouli | Arka Media Works |
| Pushpa: The Rise | Sukumar | Mythri Movie Makers |
| Pushpa 2: The Rule | Sukumar | Mythri Movie Makers |
| Jawan | Atlee | Red Chillies Entertainment |
| Pathaan | Siddharth Anand | Yash Raj Films |
| Dangal | Nitesh Tiwari | Aamir Khan Productions |
| PK | Rajkumar Hirani | Vinod Chopra Films |
| Munna Bhai M.B.B.S. | Rajkumar Hirani | Vinod Chopra Films |
| Chhichhore | Nitesh Tiwari | Fox Star Studios |
| Taare Zameen Par | Aamir Khan | Aamir Khan Productions |
| Zindagi Na Milegi Dobara | Zoya Akhtar | Excel Entertainment |
| War | Siddharth Anand | Yash Raj Films |
| Dhoom | Sanjay Gadhvi | Yash Raj Films |
| Dhoom 2 | Sanjay Gadhvi | Yash Raj Films |
| Dhoom 3 | Vijay Krishna Acharya | Yash Raj Films |
| Bahubali Returns | Demo Director | StreamFlix Originals |
| Robot | S. Shankar | Sun Pictures |
| Enthiran 2.0 | S. Shankar | Lyca Productions |
| Vikram | Lokesh Kanagaraj | Raaj Kamal Films International |
| Master | Lokesh Kanagaraj | XB Film Creators |
| Kantara | Rishab Shetty | Hombale Films |
| Charlie 777 | Kiranraj K | Paramvah Studios |

*Rows returned: 30*

### Task 17
**Requirement:** Sort movies by production company and then by rating descending.

```sql
SELECT title, production_company, rating FROM movies ORDER BY production_company ASC, rating DESC;
```
| title | production_company | rating |
| --- | --- | --- |
| Dangal | Aamir Khan Productions | 8.3 |
| Taare Zameen Par | Aamir Khan Productions | 8.3 |
| Baahubali 2: The Conclusion | Arka Media Works | 8.2 |
| Baahubali: The Beginning | Arka Media Works | 8 |
| RRR | DVV Entertainment | 8 |
| Zindagi Na Milegi Dobara | Excel Entertainment | 8.2 |
| Chhichhore | Fox Star Studios | 8.3 |
| KGF: Chapter 1 | Hombale Films | 8.4 |
| KGF: Chapter 2 | Hombale Films | 8.4 |
| Kantara | Hombale Films | 8.2 |
| Enthiran 2.0 | Lyca Productions | 6.2 |
| Avengers: Endgame | Marvel Studios | 8.4 |
| Pushpa: The Rise | Mythri Movie Makers | 7.6 |
| Pushpa 2: The Rule | Mythri Movie Makers | 6.1 |
| Drishyam | Panorama Studios | 8.2 |
| Charlie 777 | Paramvah Studios | 8 |
| Vikram | Raaj Kamal Films International | 8.3 |
| Jawan | Red Chillies Entertainment | 6.9 |
| Bahubali Returns | StreamFlix Originals | 7.1 |
| Robot | Sun Pictures | 7.1 |
| 3 Idiots | Vinod Chopra Films | 8.4 |
| PK | Vinod Chopra Films | 8.1 |
| Munna Bhai M.B.B.S. | Vinod Chopra Films | 8.1 |
| Interstellar | Warner Bros. Pictures | 8.7 |
| Master | XB Film Creators | 7.3 |
| Dhoom | Yash Raj Films | 6.6 |
| War | Yash Raj Films | 6.5 |
| Dhoom 2 | Yash Raj Films | 6.5 |
| Pathaan | Yash Raj Films | 5.8 |
| Dhoom 3 | Yash Raj Films | 5.4 |

*Rows returned: 30*

### Task 18
**Requirement:** Find the 5 highest-rated movies released after 2015.

```sql
SELECT title, rating, release_year FROM movies WHERE release_year > 2015 ORDER BY rating DESC LIMIT 5;
```
| title | rating | release_year |
| --- | --- | --- |
| Avengers: Endgame | 8.4 | 2019 |
| KGF: Chapter 1 | 8.4 | 2018 |
| KGF: Chapter 2 | 8.4 | 2022 |
| Dangal | 8.3 | 2016 |
| Chhichhore | 8.3 | 2019 |

*Rows returned: 5*

### Task 19
**Requirement:** Find the 3 most viewed Telugu movies.

```sql
SELECT title, views FROM movies WHERE language = 'Telugu' ORDER BY views DESC LIMIT 3;
```
| title | views |
| --- | --- |
| Baahubali 2: The Conclusion | 2,500,000 |
| Pushpa 2: The Rule | 2,300,000 |
| RRR | 2,100,000 |

*Rows returned: 3*

### Task 20
**Requirement:** Find the 5 most expensive movies.

```sql
SELECT title, price FROM movies ORDER BY price DESC LIMIT 5;
```
| title | price |
| --- | --- |
| Interstellar | 249 |
| Avengers: Endgame | 199 |
| KGF: Chapter 2 | 199 |
| RRR | 199 |
| Baahubali 2: The Conclusion | 199 |

*Rows returned: 5*


## LEVEL 3 — Find the Hidden Movies

### Task 21
**Requirement:** Find movies whose title starts with A.

```sql
SELECT title FROM movies WHERE title LIKE 'A%';
```
| title |
| --- |
| Avengers: Endgame |

*Rows returned: 1*

### Task 22
**Requirement:** Find movies whose title ends with a.

```sql
SELECT title FROM movies WHERE title LIKE '%a';
```
| title |
| --- |
| Zindagi Na Milegi Dobara |
| Kantara |

*Rows returned: 2*

### Task 23
**Requirement:** Find movies whose title contains the word 'Baahubali'.

```sql
SELECT title FROM movies WHERE title LIKE '%Baahubali%';
```
| title |
| --- |
| Baahubali: The Beginning |
| Baahubali 2: The Conclusion |

*Rows returned: 2*

### Task 24
**Requirement:** Find movies whose title contains 'Dhoom'.

```sql
SELECT title FROM movies WHERE title LIKE '%Dhoom%';
```
| title |
| --- |
| Dhoom |
| Dhoom 2 |
| Dhoom 3 |

*Rows returned: 3*

### Task 25
**Requirement:** Find movies whose title has exactly 5 characters.

```sql
SELECT title FROM movies WHERE LENGTH(title) = 5;
```
| title |
| --- |
| Jawan |
| Dhoom |
| Robot |

*Rows returned: 3*

### Task 26
**Requirement:** Find directors whose name contains 'Raj'.

```sql
SELECT DISTINCT director FROM movies WHERE director LIKE '%Raj%';
```
| director |
| --- |
| Rajkumar Hirani |
| S. S. Rajamouli |
| Lokesh Kanagaraj |
| Kiranraj K |

*Rows returned: 4*

### Task 27
**Requirement:** Find production companies whose name contains 'Films'.

```sql
SELECT DISTINCT production_company FROM movies WHERE production_company LIKE '%Films%';
```
| production_company |
| --- |
| Vinod Chopra Films |
| Hombale Films |
| Yash Raj Films |
| Raaj Kamal Films International |

*Rows returned: 4*

### Task 28
**Requirement:** Find movies whose language starts with 'T'.

```sql
SELECT title, language FROM movies WHERE language LIKE 'T%';
```
| title | language |
| --- | --- |
| RRR | Telugu |
| Baahubali: The Beginning | Telugu |
| Baahubali 2: The Conclusion | Telugu |
| Pushpa: The Rise | Telugu |
| Pushpa 2: The Rule | Telugu |
| Robot | Tamil |
| Enthiran 2.0 | Tamil |
| Vikram | Tamil |
| Master | Tamil |

*Rows returned: 9*


## LEVEL 4 — Business Team

### Task 29
**Requirement:** Find movies with price greater than 150 AND rating greater than 8.

```sql
SELECT title, price, rating FROM movies WHERE price > 150 AND rating > 8;
```
| title | price | rating |
| --- | --- | --- |
| Avengers: Endgame | 199 | 8.4 |
| Interstellar | 249 | 8.7 |
| KGF: Chapter 1 | 179 | 8.4 |
| KGF: Chapter 2 | 199 | 8.4 |
| Baahubali 2: The Conclusion | 199 | 8.2 |
| Dangal | 159 | 8.3 |
| Vikram | 189 | 8.3 |

*Rows returned: 7*

### Task 30
**Requirement:** Find movies with views greater than 1,000,000 OR rating greater than 8.5.

```sql
SELECT title, views, rating FROM movies WHERE views > 1000000 OR rating > 8.5;
```
| title | views | rating |
| --- | --- | --- |
| 3 Idiots | 1,200,000 | 8.4 |
| Interstellar | 1,100,000 | 8.7 |
| KGF: Chapter 1 | 1,400,000 | 8.4 |
| KGF: Chapter 2 | 1,800,000 | 8.4 |
| RRR | 2,100,000 | 8 |
| Baahubali: The Beginning | 1,900,000 | 8 |
| Baahubali 2: The Conclusion | 2,500,000 | 8.2 |
| Pushpa: The Rise | 1,700,000 | 7.6 |
| Pushpa 2: The Rule | 2,300,000 | 6.1 |
| Jawan | 2,200,000 | 6.9 |
| Pathaan | 1,600,000 | 5.8 |
| Dangal | 1,300,000 | 8.3 |
| PK | 1,250,000 | 8.1 |
| Chhichhore | 1,050,000 | 8.3 |
| War | 1,500,000 | 6.5 |
| Vikram | 1,450,000 | 8.3 |
| Master | 1,120,000 | 7.3 |
| Kantara | 1,350,000 | 8.2 |

*Rows returned: 18*

### Task 31
**Requirement:** Find movies that are NOT in the genre Horror.

```sql
SELECT title, genre FROM movies WHERE genre NOT IN ('Horror');
```
| title | genre |
| --- | --- |
| Avengers: Endgame | Action |
| 3 Idiots | Comedy |
| Drishyam | Thriller |
| Interstellar | Sci-Fi |
| KGF: Chapter 1 | Action |
| KGF: Chapter 2 | Action |
| RRR | Action |
| Baahubali: The Beginning | Epic |
| Baahubali 2: The Conclusion | Epic |
| Pushpa: The Rise | Action |
| Pushpa 2: The Rule | Action |
| Jawan | Action |
| Pathaan | Action |
| Dangal | Sports |
| PK | Comedy |
| Munna Bhai M.B.B.S. | Comedy |
| Chhichhore | Comedy |
| Taare Zameen Par | Drama |
| Zindagi Na Milegi Dobara | Drama |
| War | Action |
| Dhoom | Action |
| Dhoom 2 | Action |
| Dhoom 3 | Action |
| Bahubali Returns | Fantasy |
| Robot | Sci-Fi |
| Enthiran 2.0 | Sci-Fi |
| Vikram | Action |
| Master | Action |
| Kantara | Drama |
| Charlie 777 | Adventure |

*Rows returned: 30*

### Task 32
**Requirement:** Find movies released between 2015 and 2020.

```sql
SELECT title, release_year FROM movies WHERE release_year BETWEEN 2015 AND 2020;
```
| title | release_year |
| --- | --- |
| Avengers: Endgame | 2019 |
| Drishyam | 2015 |
| KGF: Chapter 1 | 2018 |
| Baahubali: The Beginning | 2015 |
| Baahubali 2: The Conclusion | 2017 |
| Dangal | 2016 |
| Chhichhore | 2019 |
| War | 2019 |
| Bahubali Returns | 2020 |
| Enthiran 2.0 | 2018 |

*Rows returned: 10*

### Task 33
**Requirement:** Find movies priced between 100 and 200.

```sql
SELECT title, price FROM movies WHERE price BETWEEN 100 AND 200;
```
| title | price |
| --- | --- |
| Avengers: Endgame | 199 |
| 3 Idiots | 149 |
| Drishyam | 129 |
| KGF: Chapter 1 | 179 |
| KGF: Chapter 2 | 199 |
| RRR | 199 |
| Baahubali: The Beginning | 179 |
| Baahubali 2: The Conclusion | 199 |
| Pushpa: The Rise | 179 |
| Pushpa 2: The Rule | 199 |
| Jawan | 199 |
| Pathaan | 179 |
| Dangal | 159 |
| PK | 149 |
| Chhichhore | 129 |
| Taare Zameen Par | 119 |
| Zindagi Na Milegi Dobara | 139 |
| War | 189 |
| Dhoom | 109 |
| Dhoom 2 | 129 |
| Dhoom 3 | 149 |
| Bahubali Returns | 139 |
| Robot | 129 |
| Enthiran 2.0 | 169 |
| Vikram | 189 |
| Master | 159 |
| Kantara | 149 |
| Charlie 777 | 139 |

*Rows returned: 28*

### Task 34
**Requirement:** Find movies from Hindi or Telugu language.

```sql
SELECT title, language FROM movies WHERE language IN ('Hindi','Telugu');
```
| title | language |
| --- | --- |
| 3 Idiots | Hindi |
| Drishyam | Hindi |
| RRR | Telugu |
| Baahubali: The Beginning | Telugu |
| Baahubali 2: The Conclusion | Telugu |
| Pushpa: The Rise | Telugu |
| Pushpa 2: The Rule | Telugu |
| Jawan | Hindi |
| Pathaan | Hindi |
| Dangal | Hindi |
| PK | Hindi |
| Munna Bhai M.B.B.S. | Hindi |
| Chhichhore | Hindi |
| Taare Zameen Par | Hindi |
| Zindagi Na Milegi Dobara | Hindi |
| War | Hindi |
| Dhoom | Hindi |
| Dhoom 2 | Hindi |
| Dhoom 3 | Hindi |
| Bahubali Returns | Hindi |

*Rows returned: 20*

### Task 35
**Requirement:** Find Action movies with more than 1,000,000 views.

```sql
SELECT title, genre, views FROM movies WHERE genre = 'Action' AND views > 1000000;
```
| title | genre | views |
| --- | --- | --- |
| KGF: Chapter 1 | Action | 1,400,000 |
| KGF: Chapter 2 | Action | 1,800,000 |
| RRR | Action | 2,100,000 |
| Pushpa: The Rise | Action | 1,700,000 |
| Pushpa 2: The Rule | Action | 2,300,000 |
| Jawan | Action | 2,200,000 |
| Pathaan | Action | 1,600,000 |
| War | Action | 1,500,000 |
| Vikram | Action | 1,450,000 |
| Master | Action | 1,120,000 |

*Rows returned: 10*

### Task 36
**Requirement:** Find movies directed by S. S. Rajamouli with rating greater than 8.

```sql
SELECT title, director, rating FROM movies WHERE director = 'S. S. Rajamouli' AND rating > 8;
```
| title | director | rating |
| --- | --- | --- |
| Baahubali 2: The Conclusion | S. S. Rajamouli | 8.2 |

*Rows returned: 1*

### Task 37
**Requirement:** Find movies produced by Hombale Films and released after 2019.

```sql
SELECT title, production_company, release_year FROM movies WHERE production_company = 'Hombale Films' AND release_year > 2019;
```
| title | production_company | release_year |
| --- | --- | --- |
| KGF: Chapter 2 | Hombale Films | 2022 |
| Kantara | Hombale Films | 2022 |

*Rows returned: 2*

### Task 38
**Requirement:** Find movies where director is not S. S. Rajamouli.

```sql
SELECT title, director FROM movies WHERE director != 'S. S. Rajamouli';
```
| title | director |
| --- | --- |
| Avengers: Endgame | Anthony Russo & Joe Russo |
| 3 Idiots | Rajkumar Hirani |
| Drishyam | Nishikant Kamat |
| Interstellar | Christopher Nolan |
| KGF: Chapter 1 | Prashanth Neel |
| KGF: Chapter 2 | Prashanth Neel |
| Pushpa: The Rise | Sukumar |
| Pushpa 2: The Rule | Sukumar |
| Jawan | Atlee |
| Pathaan | Siddharth Anand |
| Dangal | Nitesh Tiwari |
| PK | Rajkumar Hirani |
| Munna Bhai M.B.B.S. | Rajkumar Hirani |
| Chhichhore | Nitesh Tiwari |
| Taare Zameen Par | Aamir Khan |
| Zindagi Na Milegi Dobara | Zoya Akhtar |
| War | Siddharth Anand |
| Dhoom | Sanjay Gadhvi |
| Dhoom 2 | Sanjay Gadhvi |
| Dhoom 3 | Vijay Krishna Acharya |
| Bahubali Returns | Demo Director |
| Robot | S. Shankar |
| Enthiran 2.0 | S. Shankar |
| Vikram | Lokesh Kanagaraj |
| Master | Lokesh Kanagaraj |
| Kantara | Rishab Shetty |
| Charlie 777 | Kiranraj K |

*Rows returned: 27*


## LEVEL 5 — Boss Challenges

### Challenge 1 (Hidden Gem)
**Requirement:** Find movies that have a rating above 8 but fewer than 500,000 views.

```sql
SELECT title, rating, views FROM movies WHERE rating > 8 AND views < 500000;
```
_No rows returned._

### Challenge 2 (Cheap & Popular)
**Requirement:** Find movies where price is below 150 and views are above 1,000,000.

```sql
SELECT title, price, views FROM movies WHERE price < 150 AND views > 1000000;
```
| title | price | views |
| --- | --- | --- |
| 3 Idiots | 149 | 1,200,000 |
| PK | 149 | 1,250,000 |
| Chhichhore | 129 | 1,050,000 |
| Kantara | 149 | 1,350,000 |

*Rows returned: 4*

### Challenge 3 (Recommendation Engine)
**Requirement:** Find English movies released after 2015 having rating above 8.5.

```sql
SELECT title, language, release_year, rating FROM movies WHERE language = 'English' AND release_year > 2015 AND rating > 8.5;
```
_No rows returned._

### Challenge 4 (Trending Movies)
**Requirement:** Find the 3 most viewed movies released after 2020.

```sql
SELECT title, release_year, views FROM movies WHERE release_year > 2020 ORDER BY views DESC LIMIT 3;
```
| title | release_year | views |
| --- | --- | --- |
| Pushpa 2: The Rule | 2024 | 2,300,000 |
| Jawan | 2023 | 2,200,000 |
| RRR | 2022 | 2,100,000 |

*Rows returned: 3*

### Challenge 5 (Premium Movies)
**Requirement:** Find movies whose price is greater than the average movie price. Use AVG().

```sql
SELECT title, price FROM movies WHERE price > (SELECT AVG(price) FROM movies);
```
| title | price |
| --- | --- |
| Avengers: Endgame | 199 |
| Interstellar | 249 |
| KGF: Chapter 1 | 179 |
| KGF: Chapter 2 | 199 |
| RRR | 199 |
| Baahubali: The Beginning | 179 |
| Baahubali 2: The Conclusion | 199 |
| Pushpa: The Rise | 179 |
| Pushpa 2: The Rule | 199 |
| Jawan | 199 |
| Pathaan | 179 |
| War | 189 |
| Enthiran 2.0 | 169 |
| Vikram | 189 |

*Rows returned: 14*

### Challenge 6 (Director Spotlight)
**Requirement:** Find all movies directed by S. S. Rajamouli and sort them by release year.

```sql
SELECT title, release_year FROM movies WHERE director = 'S. S. Rajamouli' ORDER BY release_year ASC;
```
| title | release_year |
| --- | --- |
| Baahubali: The Beginning | 2015 |
| Baahubali 2: The Conclusion | 2017 |
| RRR | 2022 |

*Rows returned: 3*

### Challenge 7 (Production House Report)
**Requirement:** Find all movies produced by Hombale Films and display title, year, rating and views.

```sql
SELECT title, release_year, rating, views FROM movies WHERE production_company = 'Hombale Films';
```
| title | release_year | rating | views |
| --- | --- | --- | --- |
| KGF: Chapter 1 | 2018 | 8.4 | 1,400,000 |
| KGF: Chapter 2 | 2022 | 8.4 | 1,800,000 |
| Kantara | 2022 | 8.2 | 1,350,000 |

*Rows returned: 3*

### Challenge 8 (Franchise Search)
**Requirement:** Find every movie whose title contains Baahubali or KGF.

```sql
SELECT title FROM movies WHERE title LIKE '%Baahubali%' OR title LIKE '%KGF%';
```
| title |
| --- |
| KGF: Chapter 1 |
| KGF: Chapter 2 |
| Baahubali: The Beginning |
| Baahubali 2: The Conclusion |

*Rows returned: 4*


## FINAL BOSS — CEO Challenge

### CEO Report
**Requirement:** Best-performing movies: rating>8, views>500000, price between 100 and 250. Title, genre, rating, price, views, director, production_company. Sort by views DESC, top 5.

```sql
SELECT title, genre, rating, price, views, director, production_company FROM movies WHERE rating > 8 AND views > 500000 AND price BETWEEN 100 AND 250 ORDER BY views DESC LIMIT 5;
```
| title | genre | rating | price | views | director | production_company |
| --- | --- | --- | --- | --- | --- | --- |
| Baahubali 2: The Conclusion | Epic | 8.2 | 199 | 2,500,000 | S. S. Rajamouli | Arka Media Works |
| KGF: Chapter 2 | Action | 8.4 | 199 | 1,800,000 | Prashanth Neel | Hombale Films |
| Vikram | Action | 8.3 | 189 | 1,450,000 | Lokesh Kanagaraj | Raaj Kamal Films International |
| KGF: Chapter 1 | Action | 8.4 | 179 | 1,400,000 | Prashanth Neel | Hombale Films |
| Kantara | Drama | 8.2 | 149 | 1,350,000 | Rishab Shetty | Hombale Films |

*Rows returned: 5*
