Cosmic Occasions – User & Event Manager
A Linux-based shell script that helps manage system users along with their event bookings through a simple whiptail-based interactive UI. 📁 Project Type: Linux Shell Scripting 🎓 Submitted for: Project Evaluation
📋 Features This script allows root users to:

👤 Add a new Linux user and book an event for them

❌ Delete a user and their associated bookings

✏️ Modify existing usernames

📄 View all system users

📅 List upcoming event bookings

📜 View and clear the activity log

All actions are logged in a dedicated log file for tracking and auditing purposes.

🛠️ Requirements Make sure the following packages/tools are available:

bash (default shell)

whiptail (for GUI dialog boxes)

Run as root or via sudo for user management

🚀 How to Run ✅ Step-by-Step Instructions Open Terminal (Ctrl + Alt + T)

Switch to Root User If you're not root already:

sudo su Download or Place the Script Make sure your script is saved as:

/root/user_event_manager.sh Make the Script Executable

chmod +x /root/user_event_manager.sh Run the Script ./user_event_manager.sh Navigate the Menu You'll see a friendly interface like this:

| Cosmic Occasions |
| 1. Add User + Event Booking | | 2. Delete User + Booking | | 3. Modify User Name | | 4. List All Users | | 5. View Log File | | 6. View All Bookings | | 7. Clear Log File | | 0. Exit |
🔐 Password Handling When you choose "Add User + Event Booking": image
![image](https://github.com/user-attachments/assets/408b8c17-03c7-44e1-8f01-ea5a91e19b2d)

The script prompts for a new username.

You'll be asked to set a password for the new user.

You'll then input:

🎉 Event Name image image image
![image](https://github.com/user-attachments/assets/c80f2978-9123-484b-a491-ae80bca614c2)
![image](https://github.com/user-attachments/assets/15c10e94-870f-4d76-993b-f7e0a64fde16)
![image](https://github.com/user-attachments/assets/7788ed45-2d10-4dea-8fe0-27b9058a8df8)

📆 Event Date (must be in the future – format YYYY-MM-DD) image
![image](https://github.com/user-attachments/assets/8f4c3a30-e7a2-481a-97e1-de344b6eb412)

📍 Venue Name image image image
![image](https://github.com/user-attachments/assets/155109a8-1906-42d1-9c90-7a746b918ec9)
![image](https://github.com/user-attachments/assets/9a2edeb6-9e27-4e73-bc6f-171279bd451f)
![image](https://github.com/user-attachments/assets/3e5a259a-9d5d-4e70-99d5-ba721b814acf)

If the date or venue conflicts with an existing booking, you’ll be alerted, and the user will not be created. image
![image](https://github.com/user-attachments/assets/96f8f839-aeca-495b-9a2f-44ae21add96b)

All this is securely logged in the system for future reference. image image
![image](https://github.com/user-attachments/assets/a29d1bd6-91fb-4e68-86c3-e056d4a80be1)
![image](https://github.com/user-attachments/assets/e5e78514-660e-4a8e-8b5c-f8a92e52fe4d)

📁 Data & Logs ✅ Booking Data: Stored in: /root/event_bookings.csv Format: username,event_name,date,venue

📝 Action Logs: Stored in: /root/user_management.log Automatically trimmed if size exceeds 5MB.

🧪 Testing Tips You can test the script on any Linux distro with bash. Best viewed on full terminal screen for better dialog presentation.

🏁 Exit Message When done, select option 0 to safely exit. You'll be greeted with a message:

Thanks for using the User Manager! 🤝 Contribution Team Members:

👩‍💻 Priyanka Chaurasia

👩‍💻 Mehak

👩‍💻 Mahi

👩‍💻 Komal

Proudly created as part of our Linux System Administration Project. 
