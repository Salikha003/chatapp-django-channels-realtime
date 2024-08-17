ChatApp - Real-Time Chat Application with Django Channels and WebSockets
ChatApp is a real-time chat application built with Django Channels and WebSockets. This app allows users to communicate with each other in real-time.

Features
Real-time messaging
Direct messaging between users
Support for group chats
Auto-update for all messages
Installation and Setup
1. Clone the Repository
bash
```
git clone https://github.com/Salikha003/chatapp-django-channels-realtime.git
cd chatapp-django-channels-realtime
```
2. Create and Activate a Virtual Environment
bash
```
python3 -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```
3. Install the Required Packages
bash
```
pip install -r requirements.txt
```
4. Run Database Migrations
bash
```
python manage.py migrate
```
5. Start the Django Server
bash
```
python manage.py runserver
```
6. Start the WebSocket Server
The WebSocket server is automatically managed by Django Channels. Once the Django server is running, your app will be ready to use.

Usage
Open your browser and navigate to the server address. Join the chat and start messaging in real-time. Each user will be able to see messages as they arrive instantly.

Contributing
If you would like to contribute to this project, please follow these steps:

Fork the repository
Create your branch (git checkout -b feature-branch)
Make your changes (git commit -am 'Add some feature')
Submit a Pull Request
License
This project is licensed under the MIT License. See the LICENSE file for more details.