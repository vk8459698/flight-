# Airplane Ticket Booking and Management System







- **User Management**
- **Flight Search and Booking**
- **QR Code Verification**
- **Admin Panel**
- **Responsive Design**




```bash
cd airplane-ticket-booking
```

for frontend
```bash
cd frontend
```
```bash
npm install
```
for backend
```bash
cd backend
```
```bash
npm install
```

   - Created a `.env` file in the backend directory.
   - Added environment variables for MongoDB connection, API keys, and other sensitive information.


```bash
npm run dev
```

6. Open browser and visit `http://localhost:5173` to access the application.

Once the application is running, users can:

- Register or log in to their accounts.
- Search for flights based on their preferences.
- Book tickets securely and make payments.
- Manage booked tickets, including viewing QR codes for verification.

Admin users can access additional functionalities through the admin panel, such as managing flight listings and user information.
we can make any user admin by going to the mongodb database and editing isadmin:true from false

use valid card number for stripe like 4242 4242 4242 4242



admin is

email->vk8459698@gmail.com
password->Vivek@123456

u have to create user in one tab and go to http://localhost:5173/login in incognito tab and login as admin.
