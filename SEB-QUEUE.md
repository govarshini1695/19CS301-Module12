INSERT AND DISPLAY THE SLOT OR POSITION

AIM:
To write a python program to the candidates appeared for the interview and display the slot (or) position of third candidate.

ALGORITHM:
STEP 1:Start the program.
STEP 2:A queue is initialized using the Queue class.
STEP 3:Candidates are added to the queue using put().
STEP 4:To access the third candidate, we dequeue three candidates using get(), which removes them one by one.
STEP 5:Finally, the third candidate is displayed.
STEP 6:End the program.

PROGRAM:

```
interview = []

interview.append("Suresh")
interview.append("Padma")
interview.append("Xavier")

print("List of candidates appeared for the interview:")
print(interview)

print('Display the slot number allotted for "Candidate_2":')
print(interview.index("Xavier"))
```

OUTPUT:

![image](https://github.com/user-attachments/assets/fb040659-052a-4538-90ca-b51d45dbb548)


RESULT: 
Thus the python program to the candidates appeared for the interview and display the slot (or) position of third candidate is executed successfully.
