<!DOCTYPE html>
<html>
<head>
    <title>Abo's Website</title>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to Abo's Website</h1>
        <nav>
            <ul>
                <li><a href="#xxx">XXX</a></li>
                <li><a href="#premium-xxx">Premium XXX</a></li>
                <li><a href="#who-is-abo">Who is Abo</a></li>
            </ul>
        </nav>
    </header>
    
    <!-- Login/Sign Up Section -->
    <section id="login-signup">
        <!-- Add your login/signup form here -->
    </section>

    <!-- XXX Section -->
    <section id="xxx">
        <h2>XXX</h2>
        <!-- Latest Version Download -->
        <a href="link_to_latest_version.zip" download>Download Latest Version</a>
        <!-- View All Versions Button -->
        <button onclick="showAllVersions()">View All Versions</button>
        <!-- List of Versions (Initially Hidden) -->
        <ul id="all-versions" style="display:none;">
            <!-- List item for each version -->
            <li><a href="link_to_version_1.zip" download>Version 1</a></li>
            <li><a href="link_to_version_2.zip" download>Version 2</a></li>
            <!-- Add more versions as needed -->
        </ul>
    </section>

    <!-- Premium XXX Section -->
    <section id="premium-xxx">
        <h2>Premium XXX</h2>
        <p>Still working on it, coming soon!</p>
    </section>

    <!-- Who is Abo Section -->
    <section id="who-is-abo">
        <h2>Who is Abo</h2>
        <p>Welcome to my realm of victories and epic battles! I am Seddik Alkan, also known as "iwasAbo" in the gaming universe.
            From the inaugural season of Call of Duty Mobile, I have seized victory in a staggering 4550 tournaments. For a dozen seasons,
            I have proudly held the prestigious title of the #1 player on the global leaderboard. Notably, I boast the world's highest kill record.
            🔥🎮</p>
        <p>Telegram ID: @iwasAbo</p>
        <p>Email: iwasAbo@gmail.com</p>
    </section>

    <!-- JavaScript to Show All Versions -->
    <script>
        function showAllVersions() {
            var allVersions = document.getElementById("all-versions");
            allVersions.style.display = "block";
        }
    </script>
</body>
</html>
