<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact Form</title>
    <link rel="stylesheet" href="syle.css">
</head>
<body>

    <div class="contact-container">
        <h2>Contact Us</h2>

        <form>
            <div class="input-group">
                <label>Full Name</label>
                <input type="text" placeholder="Enter your name">
            </div>

            <div class="input-group">
                <label>Email</label>
                <input type="email" placeholder="Enter your email">
            </div>

            <div class="input-group">
                <label>Subject</label>
                <input type="text" placeholder="Enter subject">
            </div>

            <div class="input-group">
                <label>Message</label>
                <textarea placeholder="Write your message"></textarea>
            </div>

            <button type="submit">Send Message</button>
        </form>
    </div>





    CSS


    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    height: 100vh;
    background: rgb(53, 44, 61);
    display: flex;
    justify-content: center;
    align-items: center;
}

.contact-container {
    background: #fff;
    padding: 25px 30px;
    width: 350px;
    border-radius: 10px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.2);
}

.contact-container h2 {
    text-align: center;
    margin-bottom: 20px;
    color: #333;
}

.input-group {
    margin-bottom: 15px;
}

.input-group label {
    display: block;
    margin-bottom: 5px;
    font-size: 14px;
    color: #555;
}

.input-group input,
.input-group textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 6px;
    outline: none;
    font-size: 14px;
}

.input-group textarea {
    resize: none;
    height: 80px;
}

.input-group input:focus,
.input-group textarea:focus {
    border-color: #667eea;
}

button {
    width: 100%;
    padding: 10px;
    background: #667eea;
    border: none;
    color: #fff;
    font-size: 16px;
    border-radius: 6px;
    cursor: pointer;
}

button:hover {
    background: #5a67d8;
}


</body>
</html>
