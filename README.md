# nosql-challenge

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

# Dataset:

[uk_food establishments](https://github.com/dilqvl62/nosql-challenge/tree/main/Resources)

# Objectives

## Part 1 - Database and Jupyter Notebook Set Up

1. Import the data
2. import the libraries: PyMongo and Pretty Print
3. Create an instance of the Mongo Client
4. Confirm that I created the database and loaded the data properly:
   * List the databases i have in MongoDB. Confirm that uK_food is listed.
   * List the collection(s) in the database to ensure that establishments is there.
   * Find and display one document in the establishment collection using find_one and display with pprint

5. Assing the establishment collection to a variable to prepare the collection for use:

## Part2: Update the Database 

1. **An exciting new halal restaurant just opened in Greenwich, but hasn't been rated yet. The magazine has asked you to include it in your analysis. Add the following restaurant "Penang Flavours" to the database:**

![Screenshot 2023-10-25](https://github.com/dilqvl62/nosql-challenge/assets/107519883/002f6626-e014-477b-aac8-1e5aab2c51ba)

2. Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.
3. Update the new restaurant with the BusinessTypeID I found.

**Note: [This is the code for part 1 and part 2](https://github.com/dilqvl62/nosql-challenge/blob/main/NoSQL_setup.ipynb)**

## Part 3: Explloratory Analysis
1. Which establishments have a hygiene score equal to 20?

![1 1](https://github.com/dilqvl62/nosql-challenge/assets/107519883/74ff7997-d3ea-46af-bbe1-02fb60659573)

2. Which establishments in London have a RatingValue greater than or equal to 4?

![2 2](https://github.com/dilqvl62/nosql-challenge/assets/107519883/4d85e417-593c-4945-9546-56aa815f6891)

3.  What are the top 5 establishments with a RatingValue rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

![3 3](https://github.com/dilqvl62/nosql-challenge/assets/107519883/bf145c23-07f6-46a7-a836-fce1057f5bf3)

4.   How many establishments in each Local Authority area have a hygiene score of 0?

![4 4](https://github.com/dilqvl62/nosql-challenge/assets/107519883/f399279c-c99d-4138-99db-dafe1b4fea43)
