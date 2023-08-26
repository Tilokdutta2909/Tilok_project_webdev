# Tilok_project_webdev
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile card UI Design</title>

    <!-- css styling -->
    <link rel = "stylesheet" href = "profile_card.css">

    <!-- Boxicons CSS -->
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    <div class="profile_card">
        <div class="image">
            <img src="profile.jpg" alt="" class="profile_img">
        </div>
        <div class="text-data">
            <span class="name">Tilok Dutta</span>
            <span class="job">Engineer & Developer</span>
        </div>
        <div class="media-button">
            <a href="#" style="background: #0072b1" class="link">
                <i class='bx bxl-linkedin-square'></i>
            </a>
            <a href="#" style ="background:#E4405F" class="link">
                <i class='bx bxl-instagram'></i>
            </a>
            <a href="#" style ="background:#1DA1F2" class="link">
                <i class='bx bxl-twitter' ></i>
            </a>
            <a href="#" style ="background:black" class="link">
                <i class='bx bxl-github' ></i>
            </a>
        </div>
        <div class="buttons">
            <button class="button">Subscribe</button>
            <button class="button">Connect</button>
        </div>
    </div>
</body>
</html>
