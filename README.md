
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Jitin's Profile Card</title>

<style>
/* Width includes padding and border */
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #eef2f8;
}

/* Sticky Header */
header {
    position: sticky;
    top: 0;
    z-index: 10;
    background: #12203a;
    color: white;
    padding: 14px;
    text-align: center;
}

/* Profile Card */
.card {
    width: 280px;
    margin: 24px auto;
    background: white;
    border: 2px solid #2f5bea;
    border-radius: 16px;
    padding: 20px;
    text-align: center;
}

/* Avatar Circle */
.avatar {
    width: 90px;
    height: 90px;
    border-radius: 50%;
    background: #2f5bea;
    color: white;
    font-size: 36px;
    line-height: 90px;
    margin: 0 auto 10px;
}

/* Bio Scrollbar */
.bio {
    height: 80px;
    overflow: auto;
    text-align: left;
    border: 1px solid #ccd;
    padding: 8px;
    margin-top: 12px;
    font-size: 14px;
}

/* Floating Button */
.fab {
    position: fixed;
    right: 16px;
    bottom: 16px;
    width: 52px;
    height: 52px;
    border: 0;
    border-radius: 50%;
    background: #ffb703;
    font-size: 26px;
    cursor: pointer;
}
</style>
</head>

<body>

<header>My Profile Page</header>

<div class="card">

    <div class="avatar">J</div>

    <h2>Jitin Gangwar</h2>

    <p>B.Tech AI Student</p>

    <div class="bio">
        Hi! I am Jitin Gangwar.
        I am a first year B.Tech Artificial
        Intelligence student.

        I am learning Java, HTML and CSS.
        I like coding and creating websites.
        My goal is to become a successful
        software developer.
    </div>

</div>

<button class="fab">+</button>

</body>
</html>
