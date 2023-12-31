# Personal Password Manager/Generator 
Welcome to the Password Manager/Generator project! This is a small web application that allows users to generate secure passwords and manage their login credentials in a secure manner. Please note that this project is intended for educational purposes and personal challenges, and it's not recommended for real-world use due to potential security vulnerabilities. 

<h3> Features </h3>
<ul>
    <li>User account creation and authentication system.
    <li>Secure 16-digit password generation with a mix of uppercase, lowercase, digits, and special characters.
    <li>Store website/application details along with generated passwords.
    <li>Search functionality to retrieve stored credentials.
    <li>Responsive UI design for a seamless experience on various devices.
</ul>

<h3> Technologies Used </h3>
<ul> 
    <li>Python 3.11.4
    <li>Flask Framework
    <li>HTML
    <li>CSS
    <li>Bootstrap
</ul>

<h3> Getting Started </h3>
<ol>
    <li> Clone Repository 
    <pre>
    <code>git clone https://github.com/JoshPatton26/PasswordManager.git</code>
    </pre>
    <li> Naviagte to Repository 
    <pre>
    <code>cd PasswordManager</code>
    </pre>
    <li> Install Flask Library 
    <pre>
    <code>pip install Flask</code>
    </pre>
    Or
    <pre>
    <code>pip3 install Flask</code>
    </pre>
    <li> Install sqlite Module (may give error but should be fine)
    <pre>
    <code>pip install pysqlite</code>
    </pre>
    Or
    <pre>
    <code>pip3 install pysqlite</code>
    </pre>
    <li> Install Cipher.crypto Module 
    <pre>
    <code>pip install pycryptodome</code>
    </pre>
    Or
    <pre>
    <code>pip3 install pycryptodome</code>
    </pre>
    <li> Run Python File / Launch Server 
    <pre>
    <code>python run.py</code>
    </pre>
    <li> For first time use you will need uncomment lines 21 and 23, then save and run the code, then comment them back out and run code again. (working to fix this issue in the future)
</ol>

<h3> Usage </h3>
<ol> 
    <li>Create a new account or log in using existing credentials.
    <li>Generate a secure password by clicking the "Generate Password" button.
    <li>Enter the name and username of the website/application and save the record.
    <li>Use the "Manage Passwords" functionality to find and retrieve stored credentials.
</ol>

<h3> Future Enhancements </h3>
The project is still in progress, and the following enhancements are planned:
<ul> 
    <li>Get the project into a more completed state (fix bugs / finish code).
    <li>Password strength indicator for generated passwords.
    <li>Ability to update and delete stored credentials.
    <li>Two-factor authentication for added security.
    <li>Implement the use of the myEncrypt.py (AES 128) for encryption of stored data.
    <li>Backup and restore functionality.
</ul><br>

<h3> Preview </h3>
<h4>Home
<img alt="ERROR" src="images\ss1.png">
<h4>Sign-up
<img alt="ERROR" src="images\ss2.png">
<h4>Login
<img alt="ERROR" src="images\ss3.png">
<h4>User Home
<img alt="ERROR" src="images\ss4.png">
<h4>Generate
<img alt="ERROR" src="images\ss5.png">
<h4>Manager
<img alt="ERROR" src="images\ss6.png">
<h4>Results
<img alt="ERROR" src="images\ss7.png">

<br><br>
<h2></h2>
<footer>
Note: This project is intended for educational purposes and personal challenges. It is not recommended for actual password management due to potential security vulnerabilities. Always use trusted and well-tested password management solutions for real-world applications.
