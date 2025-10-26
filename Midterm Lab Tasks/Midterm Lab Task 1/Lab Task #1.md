Midterm Lab Task 1

Problem 1. Use Appropriate Escape Sequence( \n, \t \b \ ..etc)
for the problem below

<img width="1076" height="616" alt="image" src="https://github.com/user-attachments/assets/36ef41b0-8eb0-48a6-b989-7ca336cb4fe0" />

Source Code:
     
      print("Database Record ")
      print("\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\ ")
      
      first_name = "John"
      last_name = "Doe"
      email = "john.doe@example.com"
      university = "ABC University"
      
      print(f"Name:\t\t\t\t\t {first_name } {last_name }")
      print(f"Email: \t\t\t\t\t {email}" )
      print(f"University: \t\t {university}" )

Output:

<img width="701" height="284" alt="Screenshot (88)" src="https://github.com/user-attachments/assets/bfefc3d9-66fb-49f2-9709-ee49873779dc" />



Problem 2. Using Placeholders for Email Details: Use appropriate type specifiers %s, %d, %f
etc… for this task

<img width="833" height="568" alt="image" src="https://github.com/user-attachments/assets/938b8d73-0adf-44ed-bf8b-e8bedf73e16d" />


Source Code:
   
    message ="Dear John, I hope this email finds you well.  \nI wanted to reach out and say hello. \nI hope you are doing well and enjoying your day. \nIt's been
    a while since we last spoke, and I wanted to catch up with you.  \nLet's plan to meet up soon and have a great time together!"
    subject = "Greetings"
    Sender = "Jane"
    version = 1.2
    discount = "10.50%"
    status = "A"
    code = "ABCD123"
    location = "City XYZ"
    age = 30
    company = "ABC Corporation"
    website = "www.example.com"
    phone = "+1 123-456-7890"
    job_title = "Software Engineer"
    department = "Engineering"
    
    print("%s\nSubject: %s \nSender: %s \nVersion: %.1f \nDiscount: %s \nStatus: %c\nCode: %s \nLocation: %s \nAge: %d \nCompany: %s \nWebsite: %s  \nPhone: %s
    \nJob Title: %s \nDepartment: %s" % (message, subject, sender, version, discount, status, code, location, age, company, website, phone, job_title, department))



Output:

<img width="450" height="338" alt="Screenshot (89)" src="https://github.com/user-attachments/assets/dca63bf1-3af8-4fb6-a616-5c30baf4f0cf" />



Problem 3. Book Reservation; Accept User Input

<img width="770" height="278" alt="image" src="https://github.com/user-attachments/assets/03c18810-af02-4d1d-aa3b-b0d9169f9948" />

Source Code:
   
    book_title = input("Enter the book title:  ")
    book_author = input("Enter the book author:  ")
    year_of_publication =int(input("Enter the year of publication:  "))
    book_genre = input("Enter the book genre:  ")
    library = input("Enter the library:  ")
    member_id = input("Enter your member ID:  " )
    return_date = input("Enter the return date:  ")
    
    print(f"You have successfully reserved the book '{book_title}' by {book_author}.")
    print(f"Year of Publication: {year_of_publication}")
    print(f"Genre: {book_genre}")
    print(f"Library: {library}")
    print(f"Member ID: {member_id}")
    print(f"Return Date: {return_date}")


Output:

<img width="873" height="333" alt="Screenshot (90)" src="https://github.com/user-attachments/assets/5ab8f152-cfed-436e-9389-994015e8a163" />


Problem 4. Day Identifier

<img width="714" height="603" alt="image" src="https://github.com/user-attachments/assets/10e36142-6c97-4fbc-8e53-4670d4b073b9" />


Source Code:
   
     day = int(input("Enter day:   "))
 
    if day == 1 :
      print("Monday")
    elif day == 2 :
      print("Tuesday")
    elif day == 3 :
      print("Wednesday")
    elif day == 4 :
      print("Thursday")
    elif day == 5 :
      print("Friday")
    elif day == 6 :
      print("Saturday")
    elif day == 7 :
      print("Sunday")
    else:
      print("Invalid input")


Output:

<img width="535" height="287" alt="Screenshot (91)" src="https://github.com/user-attachments/assets/b9ebb365-fcce-4b4b-815e-f7d1a1fb4c79" />
