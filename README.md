# interview-management
About the project:
An interview creation page where the admin can create an interview by selecting participants, start time and end time. Backend should throw error with proper error message if: 
Any of the participants is not available during the scheduled time (i.e, has another interview scheduled)
No of participants is less than 2
An interviews list page where admin can see all the upcoming interviews.
An interview edit page where admin can edit the created interview with the same validations as on the creation page
Send emails to participants on interview creation.
![1](https://user-images.githubusercontent.com/55074362/158085779-59ae2bca-6711-49b5-b5db-14c94781c894.png)
![2](https://user-images.githubusercontent.com/55074362/158085876-22cf340c-a807-4e06-b762-30b1bcb7a6f6.png)



Steps to run this project :


npm install


npm start


project will open in the browser https://localhost:3000


Database schema:
![Screenshot (662)](https://user-images.githubusercontent.com/55074362/158085902-c7070dd6-c4e3-4713-91f1-0f1d1d5398ac.png)


Twilio SMS Notification
![3](https://user-images.githubusercontent.com/55074362/158085884-cc4c864b-1f72-459d-a19a-8afd6301b9b1.jpeg)


Scope for Improvement
Resume Upload/Download functionality, MongoDB Integration or Firebase RealTime DB
