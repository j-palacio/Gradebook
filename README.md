# Gradebook
This program manages a gradebook for a student and incorporates grades from the last semester along with the current semester. It utilizes lists to store information about subjects and corresponding grades.

Last Semester's Gradebook
python
Copy code
last_semester_gradebook = [["politics", 80], ["latin", 96], ["dance", 97], ["architecture", 65]]
Current Semester's Gradebook
python
Copy code
# Your code below:
subjects = ["physics", "calculus", "poetry", "history"]
grades = [98, 97, 85, 88]

gradebook = [["physics", 98], ["calculus", 97], ["poetry", 85], ["history", 88]]
print(gradebook)

# Add computer science grade
gradebook.append(["computer science", 100])
print(gradebook)

# Add visual arts grade
gradebook.append(["visual arts", 98])
print(gradebook)

# Update poetry grade to "Pass"
gradebook[2].remove(85)
gradebook[2].append("Pass")
print(gradebook)
Full Gradebook
python
Copy code
# Combine last semester's gradebook with the current semester's gradebook
full_gradebook = last_semester_gradebook + gradebook
print(full_gradebook)
This program showcases the addition of new subjects and grades to the gradebook, as well as the update of a grade to a "Pass" status. The final full_gradebook variable combines grades from the last semester with the current semester, providing a comprehensive overview of the student's academic performance.