# Student Exam Score Logger

This Java program simulates multiple students submitting exam scores at the same time using threads.  
Scores are written safely to a CSV file using synchronized writing.  

It demonstrates:
- Multiple threads writing concurrently
- Thread-safe file writing
- Storing student data (name, roll number, marks) in a CSV file
- JUnit tests verify file writing and thread completion

---

## Program Output

**Main Output**
Alice,101,85
Bob,102,90
Charlie,103,78



**JUnit Output**
Dev,302,88
Emma,303,95

Both threads completed successfully and data written safely.
