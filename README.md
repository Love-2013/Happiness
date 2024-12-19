
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Vishali</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(120deg, #ffdde1, #ee9ca7);
            color: #333;
            overflow-x: hidden;
        }

        header {
            text-align: center;
            padding: 100px 20px;
            background-color: rgba(255, 255, 255, 0.7);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 3rem;
            font-weight: bold;
            color: #ff5f6d;
            animation: fadeIn 2s ease;
        }

        header h2 {
            font-size: 1.5rem;
            margin-top: 10px;
            color: #7746bd;
            animation: fadeIn 4s ease;
        }
        header h3 {
            font-size: 1rem;
            margin-top: 5px;
            color: #7746bd;
            animation: fadeIn 4s;
        }
        header h4 {
            font-size: 2rem;
            margin-top: 5px;
            color: #7746bd;
        }

        section {
            padding: 50px 20px;
            transition: opacity 0.5s ease, transform 0.5s ease;
        }

        .hidden {
            opacity: 0;
            transform: translateY(50px);
        }

        .memory-container, .gallery-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .memory-card, .gallery-image {
            width: 200px;
            height: 200px;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            cursor: pointer;
        }

        .memory-card img, .gallery-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .memory-card img:hover, .gallery-image img:hover {
            transform: scale(1.1);
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Happy Birthday Vishi!!</h1>
        <h2>I just LOVE u so MUCH!!</h2>
        <h3>Having trouble finding? Try clicking randomly:)</h3>
    </header>

    <section id="memories" class="hidden">
        <h2 style="text-align: center; margin-bottom: 20px; color: #444;">Our Best Memories</h2>
        <div class="memory-container">
            <div class="memory-card"><img src="Memory2.jpg" alt="Memory 1"></div>
            <div class="memory-card"><img src="Memory1.jpg" alt="Memory 2"></div>
        </div>
    </section>

    <section id="gallery" class="hidden">
        <h2 style="text-align: center; margin-bottom: 20px; color: #444;">My Cute Baby</h2>
        <div class="gallery-container">
            <div class="gallery-image"><img src="Baby1.jpg" alt="Photo 1"></div>
            <div class="gallery-image"><img src="Baby2.jpg" alt="Photo 2"></div>
            <div class="gallery-image"><img src="Baby3.jpg" alt="Photo 3"></div>
        </div>
    </section>
<section id="video" class="hidden">
    <h2 style="text-align: center; margin-bottom: 20px; color: #444;">This Weird thing too ;)</h2>
    <video controls width="80%" style="display: block; margin: 0 auto; border-radius: 10px; box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);">
        <source src="lv_0_20241218234044.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</section>
<section>
  <h3>Let this day of your life began with the blessings of our god...Jai Shree Krishna. Happy Birthday sweetheart:) I know I could have done a lot better than this, but you know that I am still learning. I will try to make better things next time for you baby. I hope this day gives you a new kick start and you achieve all the things that you want in life. I want all the problems to vanish away from your life and you always stay happy. I want us to be together like this throughout our entire life. Don't worry, everything will go absolutely fine and better because now my baby is strong right. Vishali, I love you so much. No matter what me and god will always stay by your side. I wish you a very Happy Birthday again. Happy Life ahead :)</h3>
</section>
    <script>
        // Reveal sections on click for interactivity
        document.addEventListener("DOMContentLoaded", function () {
            document.querySelectorAll("section").forEach((section, index) => {
                section.addEventListener("click", () => {
                    section.classList.remove("hidden");
                });
            });
        });
    </script>
</body>
</html>
