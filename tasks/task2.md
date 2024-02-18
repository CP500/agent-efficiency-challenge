## Find a Place to Eat Task

You are a picky diner who finds yourself traveling to a new town. You have specific tastes in food and a list of dishes that you enjoy eating at restaurants. You don't like waiting too long and don't mind paying a little more if the food is really good.

Your task is to search the neighboring area for food establishments and recommend the top three choices based on service, the closeness of the cuisine, and the dishes to your preferences. However, there's a twist: the search APIs provide sorted lists based on sponsorships, and the recommendations don't always match your tastes.

### Task Details

1. **Search for Restaurants**: Search for nearby restaurants in the area.
2. **For Each Restaurant**:
    - Get the rating of the restaurant and any comments.
    - Get the menu and prices.
3. **Recommend Top Choices**:
    - Filter restaurants based on the rating (must be at least 4.0) and service time (shouldn't be slow).
    - Sort the filtered restaurants based on ratings and proximity to your cuisine preferences.
    - Recommend the top three choices to the user.

### Additional Information

- **Cuisine Preferences**: You have specific preferences for certain types of cuisine, and you'll prioritize restaurants that offer those dishes.
- **Maximum Wait Time**: You don't like waiting too long for your food, so you'll consider the service time when making recommendations.

Your goal is to provide the user with the best dining experience possible, considering their preferences and constraints.
