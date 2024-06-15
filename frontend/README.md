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

for backend
```bash
cd backend
```


```bash
npm install
```

   - Created a `.env` file in the root directory.
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


