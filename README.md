<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My  Portfolio</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            background: linear-gradient(135deg, #ffe6f7, #e0f7fa);
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
            min-height: 100vh;
            color: #333;
        }

        header {
            text-align: center;
            padding: 2em 0;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 2em;
            width: 80%;
        }

        header h1 {
            color: #ff69b4; /* Hot pink */
            font-size: 2.5em;
            margin-bottom: 0.5em;
        }

        section {
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 2em;
            margin-bottom: 2em;
            width: 80%;
            text-align: center;
        }

        section h2 {
            color: #8a2be2; /* Violet */
            border-bottom: 2px dashed #ddd;
            padding-bottom: 0.5em;
            margin-bottom: 1em;
        }

        .project {
            border: 2px solid #ddd;
            border-radius: 10px;
            padding: 1.5em;
            margin: 1em 0;
            text-align: left;
        }

        .project h3 {
            color: #00ced1; /* Dark turquoise */
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin-bottom: 0.5em;
        }

        a {
            color: #ff1493; /* Deep pink */
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        form {
            display: flex;
            flex-direction: column;
            align-items: stretch;
        }

        label {
            margin-bottom: 0.5em;
            text-align: left;
        }

        input, textarea {
            padding: 0.8em;
            margin-bottom: 1em;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        button {
            background-color: #9370db; /* Medium purple */
            color: white;
            padding: 1em 1.5em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #800080; /* Purple */
        }

        footer {
            text-align: center;
            padding: 1em 0;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 80%;
            margin-top: 2em;
        }

        img.profile {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 1em;
            border: 5px solid #ffb6c1; /* Light pink border */
        }

    </style>
</head>
<body>

    <header>
        <img src="port.jpg" alt="C:\Users\PURITY\Desktop\HTML" class="profile">
        <h1>WINNIE PURITY's PORTFOLIO!</h1>
    </header>

    <section id="about">
        <h2>About Me! 💖</h2>
        <p>Hi there! I'm winnie purity, a super passionate web developer who loves creating adorable and functional websites. I believe in making the internet a cuter place, one line of code at a time! 🌟</p>
        <p>I am a student taking BSC.ICT from JOOUST.</p>
        <a href="https://drive.google.com/file/d/1qlQ0bmZ2if5cXSo-8wMBJP7aXWSRjrgS/view?usp=drivesdk" download>Download My CV 🐾</a>
        <h2>My Interests! 🌈</h2>
        <ul>
            <li>✨ Web Development (of course!)</li>
            <li>🎨 Creative Design</li>
            <li>🚀 Learning new tech!</li>
            <li>🎮 Video Games</li>
            <li>📚 Reading Fantasy</li>
            <li>✨coding</li>
        </ul>
    </section>

    <section id="projects">
        <h2>My Cute Projects! 🧸</h2>
        <div class="project">
            <h3>Project 1: QRA class attendance system</h3>
            <p>this is all about quick class attendance system. this system leverage qr codes to stream 
                line attendance recording
            </p>
            <a href="https://drive.google.com/file/d/1qlQ0bmZ2if5cXSo-8wMBJP7aXWSRjrgS/view?usp=drivesdk">Check it out! 🎀</a> <p>when am done with it</p>
        </div>
        <div class="project">
            <h3>Project 2:AI tutoring powered system</h3>
            <p>is an educational platform or tool that leverage ai to provide personalised learning experiences 
                and support to students.</p>
            <a href="https://drive.google.com/file/d/1qlQ0bmZ2if5cXSo-8wMBJP7aXWSRjrgS/view?usp=drivesdk">See the magic! 🪄</a>
        </div>
    </section>

    <section id="contact">
        <h2>Let's Chat! 💌</h2>
        <form>
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Your Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send Message! 💖</button>
        </form>
    </section>

    <footer>
        <p>&copy; [2025] [winnie purity// puritywinnie@gmail.com] - Made with lots of love! ✨</p>
    </footer>

</body>
</html>



