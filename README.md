# healthpodcast
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Healthcare Podcasts</title>
    <!-- Import Playfair Display font -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS -->
    <style>
        /* Apply Playfair Display font */
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            font-family: 'Playfair Display', serif;
        }

        .player-container, .video-container {
            width: 100%;
            max-width: 935px;
            margin-bottom: 40px;
        }

        .player {
            margin-bottom: 20px;
        }

        .video-container {
            margin-top: 40px;
        }

        .button-container {
            margin-bottom: 40px;
        }

        /* Testimonial Container with Background Image */
        .testimonial-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 100%;
            max-width: 935px;
            margin-top: 40px;
            padding: 40px;
            background-image: url('healthcare2.jpg');
            background-size: cover;
            background-position: center;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .testimonial {
            width: 80%;
            max-width: 800px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: rgba(255, 255, 255, 0.9);
            text-align: center;
            margin-bottom: 20px;
            font-style: italic;
        }

        /* User Info Form Styling */
        .user-info-form {
            width: 100%;
            max-width: 935px;
            padding: 20px;
            margin-top: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: #fff;
        }

        .user-info-form label {
            display: block;
            margin-bottom: 8px;
        }

        .user-info-form input,
        .user-info-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        .user-info-form button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 12px 24px;
            cursor: pointer;
            font-size: 16px;
            border-radius: 4px;
        }

        .user-info-form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <ul>
            <li><a href="https://www.qure.ai/blog">Medical Experts</a></li>
            <li><a href="https://www.medicalnewstoday.com/">Recent Medical News</a></li>
            <li><a href="google.com/search?sca_esv=1c94ba2c29d9ad4c&rlz=1C1OZZY_enIN1135IN1143&tbm=lcl&q=hospitals+kochi">Hospitals Near Me</a></li>
        </ul>
    </nav>

    <div class="info-box">
        <h2>About Healthcare & Wellness</h2>
        <p>Welcome to our healthcare podcast, your go-to source for expert advice, insightful discussions, and the latest trends in health and wellness. Each episode dives deep into topics ranging from mental health and nutrition to fitness and medical breakthroughs. Whether you're looking to optimize your lifestyle or stay informed on important health issues, we’ve got you covered. Join us as we explore, educate, and empower you on your health journey—listen now on Spotify and stay ahead of the curve!</p>
    </div>

    <div class="player-container">
        <div class="player">
            <h1>Healthcare Podcasts</h1>
            <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/1RpSCEqhwp8nt78rE4NgBl?utm_source=generator" width="100%" height="352" frameborder="0" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
        </div>
        <div class="player">
            <h1>Health & Fitness Podcasts</h1>
            <iframe style="border-radius:12px" src="https://open.spotify.com/embed/show/5QAWGLhMbBzATD2D4lnMKM?utm_source=generator" width="100%" height="352" frameborder="0" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
        </div>
        <div class="player">
            <h1>Wellness Podcasts</h1>
            <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/4FeJZhUyV8gZVjUjRj3zJl?utm_source=generator" width="100%" height="352" frameborder="0" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
        </div>
    </div>

    <div class="video-container">
        <h2>Featured Video: How The Human Connection Improves Healthcare</h2>
        <iframe width="935" height="526" src="https://www.youtube.com/embed/7zk_AJBO60Y" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>

    <div class="button-container">
        <button id="navigateButton1">Healthcare</button>
        <button id="navigateButton2">Wellness</button>
        <button id="navigateButton3">Podcasts</button>
    </div>

    <div class="testimonial-container">
        <div class="testimonial">
            <p>"I love the health tips and insightful discussions on this podcast! It's helped me stay on track with my wellness goals." - Meenakshi Kaimal.</p>
        </div>
        <div class="testimonial">
            <p>"The expert advice on nutrition and fitness has transformed my daily routine. Highly recommend to anyone looking to improve their health!" - Vyshnavi Jayachandran.</p>
        </div>
        <div class="testimonial">
            <p>"These podcasts are a game-changer! I’ve learned so much about mental health and wellness. Can't wait to hear more!" - Aarsha D.</p>
        </div>
    </div>

    <!-- User Information Form Section -->
    <div class="user-info-form">
        <h2>Tell Us About Yourself</h2>
        <form id="userForm">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="goal">Your Wellness Goal:</label>
            <textarea id="goal" name="goal" rows="4" required></textarea>

            <label for="podcast">Types of podcasts you want to listen to:</label>
            <textarea id="podcast" name="podcast" rows="2" required></textarea>

            <button type="submit">Submit</button>
        </form>
    </div>

    <script>
        document.getElementById("navigateButton1").onclick = function() {
            window.location.href = "https://open.spotify.com/show/4pPjIJ3sR1rKIOCwee48ZV";
        };

        document.getElementById("navigateButton2").onclick = function() {
            window.location.href = "https://open.spotify.com/playlist/0mrxIL2fM36cjERDGa9ImO";
        };

        document.getElementById("navigateButton3").onclick = function() {
            window.location.href = "https://open.spotify.com/show/3v2UftCPOdbAmDxYvnwfGB";
        };

        // Handling the form submission
        document.getElementById("userForm").addEventListener("submit", function(event) {
            event.preventDefault(); // Prevent form from refreshing the page

            // Get form data
            const name = document.getElementById("name").value;
            const email = document.getElementById("email").value;
            const goal = document.getElementById("goal").value;
            const podcast = document.getElementById("podcast").value;

            // Store in localStorage (you can store in your database instead)
            const userInfo = {
                name: name,
                email: email,
                goal: goal,
                podcast: podcast
            };
            localStorage.setItem("userInfo", JSON.stringify(userInfo)); // Store user info in local storage

            // Display confirmation message
            alert("Thank you for submitting your info!");

            // Optionally clear the form
            document.getElementById("userForm").reset();
        });
    </script>
</body>
</html>
