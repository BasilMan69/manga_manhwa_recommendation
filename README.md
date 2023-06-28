# manga_manhwa_recommendation

### Topic
- Manga and Manhwa Recommendation System

### Database
- Read Manga and Manhwa divided into categories

### How it works
1. List all categories
2. Take user input of a string of letter
3. Find the category that starts with that string
4. List the categories that start with that string (If there are more than one, else move to step 6)
5. Ask the user to enter more characters to choose one of the categories
6. Confirm user choice (y/n)
7. Asks the user if they want to select another category
a. If yes: Go back to step 1
b. Else:
    - Using selected categories to find matched manga and manhwa recommendations
    - display the found manga and manhwa, including:
      - name
      - genre/category
      - rating
      - synopsis


