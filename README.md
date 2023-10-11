# Movie-Data-Analysis
The goal of this project was to demonstrate proficiency in data curation and analysis. The top 200 movies by lifetime gross was extracted, analyzed, and visualized using APIs.

**Relevant API Documentation**
- https://www.geeksforgeeks.org/python-web-scraping-tutorial/
- https://www.edureka.co/blog/web-scraping-with-python/
- https://www.boxofficemojo.com/chart/top_lifetime_gross/?area=XWW

**License**

MIT License
Copyright (c) 2023 brandonhcheung

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

**Attributes**
- Rank(int): Ranks the top 200 movies by gross income
- Title(str): Title of the movie
- Year(int): Year the movie was released
- Lifetime Gross(int): Lifetime gross income generated

**Known/Potential Issues**
- Timing bias could have played a role, as movies that were released before others had more time to generate more money.
- All of the movies from the dataset were released in the USA, ignoring movies that were released in other countries that could have made more money than some movies on the list.

**Analysis**
The top 200 movies with the highest gross income was analyzed and visualized through descriptive statistics and plots. The bar graph uses the data to show the highest grossing movie of their year in order to determine whether or time plays a significant role in gross income for movies. We can see that there is a very small increase in the gross income of the most popular film of the year as time progresses. The average gross income for the top movies of their year is $908395096.68 and the ranges  [$559852396.00, $2923706026.00]. The standard deviation is $364563849.88
