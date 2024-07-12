# [JSL02] Submission: Debug the DOM Explained 

What was achieved : 
1. Created Variables  That would be used in the validation process.
2. Used For loops in  Javascript to check if any duplicates could be found.
3. Created a function that searches for duplicates and blocks their insertion.
4. Added an Alert to Highlight to the user an error has occurred. 


# Below is the Original Brief of the Activity  

# Debugging Duplicate Goals

**Debugging Brief:**
In the current code, users can add the same fitness goal multiple times, leading to duplicate entries in the goal list. To enhance the user experience and prevent duplicates, you need to implement a check to ensure that the same goal cannot be added more than once. If a duplicate goal is detected, it should NOT be added to the list.

![alt text](JSL02_Solution.png)

**Issue:** Users can add duplicate fitness goals.
**Debugging Task:** Prevent users from adding the same goal more than once.

- The goal is to prevent users from adding duplicate fitness goals to the list.
- You need to check if the goal being added already exists in the list before appending it.
- Display an alert to inform the user if they are trying to add a duplicate goal.
- Focus on the code structure within the function and how to handle duplicates.

**Explanation:**
1. We first retrieve all the existing goals in the `goalList` using `querySelectorAll`.
2. Then, we iterate through each existing goal and compare its text content with the new goal input.
3. If a duplicate is found, we display an alert message and exit the function using `return` to prevent the duplicate goal from being added.
4. If no duplicate is found, we proceed to create and add the new goal as before.

Check out the practice challenges on Scrimba here: https://scrimba.com/playlist/pwVxGLDUW
