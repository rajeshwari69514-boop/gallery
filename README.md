# gallery

# Coding
<!DOCTYPE html>
<html>
<head>
    <title>Gallery</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .gallery-container {
            width: 90%;
            padding: 30px;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(15px);
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.5);
        }

        h1 {
            text-align: center;
            color: white;
            margin-bottom: 30px;
            letter-spacing: 2px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            position: relative;
            overflow: hidden;
            border-radius: 15px;
            cursor: pointer;
            transition: transform 0.4s;
        }

        .card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 15px;
            transition: transform 0.5s;
        }

        .card:hover img {
            transform: scale(1.1);
        }

        .caption {
            position: absolute;
            bottom: 0;
            width: 100%;
            background: rgba(0, 0, 0, 0.6);
            color: white;
            text-align: center;
            padding: 10px;
            font-size: 16px;
            backdrop-filter: blur(5px);
        }

        .card:hover {
            transform: translateY(-8px);
        }

        @media(max-width: 600px) {
            .card img {
                height: 200px;
            }
        }
    </style>
</head>
<body>

<div class="gallery-container">
    <h1>📸 Gallery</h1>

    <div class="gallery">

        <div class="card">
            <img src="https://picsum.photos/400/300?1">
            <div class="caption">Beautiful Nature</div>
        </div>

        <div class="card">
            <img src="https://picsum.photos/400/300?2">
            <div class="caption">Mountain View</div>
        </div>

        <div class="card">
            <img src="https://picsum.photos/400/300?3">
            <div class="caption">City Lights</div>
        </div>

        <div class="card">
            <img src="https://picsum.photos/400/300?4">
            <div class="caption">Ocean Sunset</div>
        </div>

        <div class="card">
            <img src="https://picsum.photos/400/300?5">
            <div class="caption">Forest Path</div>
        </div>

        <div class="card">
            <img src="https://picsum.photos/400/300?6">
            <div class="caption">Sky & Clouds</div>
        </div>

        <!-- Newly Added 4 Photos -->

        <div class="card">
            <img src="https://picsum.photos/400/300?7">
            <div class="caption">Golden Desert</div>
        </div>

        <div class="card">
            <img src="https://picsum.photos/400/300?8">
            <div class="caption">Snow Mountains</div>
        </div>

        <div class="card">
            <img src="https://picsum.photos/400/300?9">
            <div class="caption">River Bridge</div>
        </div>

        <div class="card">
            <img src="https://picsum.photos/400/300?10">
            <div class="caption">Night Sky</div>
        </div>

    </div>
</div>

</body>
</html>

# Website
<img width="1851" height="792" alt="image" src="https://github.com/user-attachments/assets/824075e3-acda-4d35-bc9c-ab0184c6cd9e" />


# Output
https://rajeshwari69514-boop.github.io/gallery/
