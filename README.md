<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Profile Card</title>
  <link rel="stylesheet" href="Assignment.css">
  <script>
    * {
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #141414;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
}

.container {
  display: flex;
  justify-content: center;
}

.card {
  background-color: #1f1f1f;
  padding: 25px;
  border-radius: 15px;
  text-align: center;
  width: 300px;
}

.profile-img {
  width: 100px;;
  height: 100px;
  border-radius: 50%;
  margin-bottom: 10px;
}

h2 {
  font-size: 25px;
  margin-bottom: 15px;
}

.location {
  color: #c4f82a;
  margin-bottom: 1rem;
  font-weight: bold;
}

.bio {
  font-style: italic;
  margin-bottom: 25px;
  color: #ccc;
}

.links a {
  display: block;
  margin: 10px;
  padding: 8px;
  background-color: #333;
  color: white;
  border-radius: 8px;
  text-decoration: none;
}

.links a:hover {
  background-color: #c4f82a;
  color: black;
}
  </script>
</head>
<body>
  <div class="container">
    <div class="card">
      <img src="https://static.vecteezy.com/system/resources/previews/038/974/578/non_2x/ai-generated-professional-portrait-of-a-competent-woman-free-photo.jpg" alt="Profile" class="profile-img">
      <h2>Ms. LakshmiKrishna</h2>
      <p class="location">Chennai, tamilnadu</p>
      <p class="bio">"Front-end developer and avid reader."</p>
      <div class="links">
        <a href="#">GitHub</a>
        <a href="#">Frontend Mentor</a>
        <a href="#">LinkedIn</a>
        <a href="#">Twitter</a>
        <a href="#">Instagram</a>
      </div>
    </div>
  </div>
</body>
</html>
