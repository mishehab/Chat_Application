  <h1>Chat App</h1>

   <p>A real-time chat application built with Django, Django Channels, and WebSockets. This app allows users to register, log in, and participate in chat rooms with other users. It supports real-time messaging, message search, and displays recent messages for each user.</p>

  <h2>Features</h2>
    <ul>
        <li><strong>User Authentication</strong>: Users can sign up, log in, and log out.</li>
        <li><strong>Real-Time Messaging</strong>: Utilizes Django Channels and WebSockets for real-time chat between users.</li>
        <li><strong>Search Functionality</strong>: Users can search for messages based on content.</li>
        <li><strong>User Message History</strong>: Displays the last message exchanged with each user.</li>
        <li><strong>Responsive Interface</strong>: The app is designed with an intuitive interface for chatting.</li>
    </ul>
    <h2>Prerequisites</h2>
    <p>Before you begin, ensure you have met the following requirements:</p>
    <ul>
        <li>Python 3.x installed</li>
        <li>pip (Python package installer)</li>
        <li>Django 5.1 or above</li>
        <li>Django Channels</li>
        <li>SQLite (default database used in development)</li>
    </ul>
    <h2>Installation</h2>
    <h3>1. Clone the Repository</h3>
    <pre><code>git clone https://github.com/your-username/chat_app.git
cd chat_app</code></pre>
    <h3>2. Set Up a Virtual Environment (optional but recommended)</h3>
    <pre><code>python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate</code></pre>

  <h3>3. Install Dependencies</h3>
  <pre><code>pip install -r requirements.txt</code></pre>

   <h3>4. Apply Migrations</h3>
   <pre><code>python manage.py migrate</code></pre>

   <h3>5. Run the Development Server</h3>
   <pre><code>python manage.py runserver</code></pre>
  <p>The app will be accessible at <code>http://127.0.0.1:8000/</code>.</p>
    <h3>6. Create a Superuser (Optional for Admin Access)</h3>
    <pre><code>python manage.py createsuperuser</code></pre>
    <p>Follow the prompts to set up an admin user.</p>

  <h2>Usage</h2>
    <ol>
        <li><strong>Sign up</strong>: Users can create an account by providing an email, username, and password.</li>
        <li><strong>Log in</strong>: After signing up, users can log in to their account using their credentials.</li>
        <li><strong>Chat</strong>: Once logged in, users can join chat rooms and send messages to others in real time.</li>
        <li><strong>Search</strong>: Users can search for specific messages within their chat room.</li>
    </ol>

  <h2>Structure</h2>
    <ul>
        <li><strong>chat</strong>: Contains the app logic for the chat functionality, including WebSocket routing and message storage.</li>
        <li><strong>users</strong>: Manages user authentication (login, logout, signup).</li>
        <li><strong>templates</strong>: Contains HTML files for the front end.</li>
        <li><strong>static</strong>: Static files like CSS and JavaScript.</li>
    </ul>

   <h2>Technologies Used</h2>
    <ul>
        <li><strong>Django</strong>: A high-level Python web framework used for the back end.</li>
        <li><strong>Django Channels</strong>: Adds support for handling WebSockets for real-time messaging.</li>
        <li><strong>SQLite</strong>: A lightweight database used for development.</li>
        <li><strong>Bootstrap</strong>: For responsive front-end design.</li>
    </ul>

   <h2>Contributing</h2>
    <p>Feel free to fork the project, submit issues, and open pull requests. Contributions are welcome!</p>
    <ol>
        <li>Fork the repository.</li>
        <li>Create a new branch (<code>git checkout -b feature-branch</code>).</li>
        <li>Make changes and commit them (<code>git commit -m 'Add new feature'</code>).</li>
        <li>Push to the branch (<code>git push origin feature-branch</code>).</li>
        <li>Open a pull request.</li>
    </ol>

</body>
</html>
