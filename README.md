# posters
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Posters</title>
  <style>
    body {
      margin: 0;
      padding: 0;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 0; /* no space between posters */
    }
    .gallery img {
      width: 100%;
      display: block;
    }
  </style>
</head>
<body>
  <div class="gallery">
    <img src="poster1.jpg" alt="Poster 1">
    <img src="poster2.jpg" alt="Poster 2">
    <img src="poster3.jpg" alt="Poster 3">
    <img src="poster4.jpg" alt="Poster 4">
    <img src="poster5.jpg" alt="Poster 5">
    <!-- add more posters as needed -->
  </div>
</body>
</html>
