# Part 1: Plain Aggregates and Privacy

## Question 1

Kinan very likely likes metal music. Every person that's older than 28 years old in the query result either likes metal music or prefer not to answer. Kinan is very likely either 29 or 30 years old, because he obtained this undergraduate degree in 2015. Kinan also indicates on this personal webpage that he likes metal music. It's hard to deteremine what genre is impossible, because there is a person who's 29 years old and selected "Prefer not to answer" in the music column, so any genre is still possible.

## Question 2

It's hard to determine if Kinan is 29 or 30 years old with just the query result, but I found on his Facebook page where it indicates that Kinan's is born in 1994. This means Kinan is either 28 or 29 years old depending on the month of his birthday. Since no one is 28 years old in the query result, Kinan must be 29 years old.

## Question 3

I can't say with certainty, but Kinan very likely likes the color, black. There are two people of the age, 29. They like black and yellow colors seperately. However, Kinan likes metal music, and people who like metal music usually wear black clothes. In addition, in all his Facebook photos, he wears black clothes. So he probably likes the black color. This is easy to identify once I know his favorite music genre and his exact age.

## Question 4

I can't learn much from the query, because there are 9 people who are 25 years old or older. They like baseball, basketball, E-Sports or soccer. Kinan could like either one of these sports with the same probability if I just look at the query result.

## Question 5

Soccer. If I run this query: "python3 client.py count age sport ", the result shows that the two people who are 29 years ago like basketball and soccer. However, in the query result from the previous semester, no one who are 25 years old or older likes basketball. Therefore, Kinan must like soccer.

However, this makes my previous answers about Kinan's age invalid. After I'm certain Kinan likes soccer, I run this query: "python3 client.py count age sport color music", I noticed the only person who likes both soccer and metal music is 30 years old, which means the age on his Facebook page is not correct. This also means Kinan actually likes the color blue instead of black, which is a surprising finding.

# Part 2: Implementing Differential Privacy

## Question 6:

## Question 7:

## Question 8:

## Question 9:

## Question 10:
