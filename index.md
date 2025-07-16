<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.3/css/lightbox.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        main {
            width: 100%;
            max-width: 1100px;
        }
        h1 {
            color: #333;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            max-width: 1000px;
            width: 100%;
        }
        .gallery-item {
            position: relative;
            text-align: center;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }
        .gallery img:hover {
            transform: scale(1.30);
        }
        .caption {
            position: absolute;
            bottom: 8px;
            left: 50%;
            transform: translateX(-50%);
            background-color: rgba(0, 0, 0, 0.5);
            color: white;
            padding: 5px 10px;
            border-radius: 8px;
            font-size: 14px;
            max-width: 90%;
            white-space: pre-line;
        }
        @media (max-width: 600px) {
            .gallery {
                grid-template-columns: 1fr;
            }
            main {
                padding: 0 5px;
            }
        }
    </style>
</head>
<body>
    <main>
        <h1>Gilbertine Weekend Away - Hereford 2024</h1>
        <p>For the Gilbertine Lab, weekend away 2024, we headed to Hereford to sample the River Wye, through a day of canoeing.</p>
        <section class="gallery">
            <figure class="gallery-item">
                <a href="images/IMG_5436.jpg" data-lightbox="gallery" data-title="The weekend Logo">
                    <img src="images/IMG_5436.jpg" alt="Gilbertine Weekend Away 2024 Logo" loading="lazy">
                </a>
                <figcaption class="caption">The weekend Logo</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240712-WA0003.jpg" data-lightbox="gallery" data-title="On top of the Malvern Hills">
                    <img src="images/IMG-20240712-WA0003.jpg" alt="Group on top of the Malvern Hills" loading="lazy">
                </a>
                <figcaption class="caption">On top of the Malvern Hills</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240712-WA0007.jpg" data-lightbox="gallery" data-title="A cow">
                    <img src="images/IMG-20240712-WA0007-w.jpg" alt="A cow on the hillside" loading="lazy">
                </a>
                <figcaption class="caption">A cow</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240712-WA0013.jpg" data-lightbox="gallery" data-title="Pretty view of Malvern Hills">
                    <img src="images/IMG-20240712-WA0013.jpg" alt="Pretty view of Malvern Hills" loading="lazy">
                </a>
                <figcaption class="caption">Pretty view of Malvern Hills</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240713-WA0001.jpg" data-lightbox="gallery" data-title="Canoeing on the River Wye">
                    <img src="images/IMG-20240713-WA0001.jpg" alt="Canoeing on the River Wye" loading="lazy">
                </a>
                <figcaption class="caption">Canoeing on the River Wye</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240713-WA0003.jpg" data-lightbox="gallery" data-title="The Group, with Sadegh and I after just capsizing">
                    <img src="images/IMG-20240713-WA0003.jpg" alt="The Group, with Sadegh and I after just capsizing" loading="lazy">
                </a>
                <figcaption class="caption">The Group, with Sadegh and I after just capsizing</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240713-WA0004.jpg" data-lightbox="gallery" data-title="Ed and Xu">
                    <img src="images/IMG-20240713-WA0004.jpg" alt="Ed and Xu" loading="lazy">
                </a>
                <figcaption class="caption">Ed and Xu</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240713-WA0007.jpg" data-lightbox="gallery" data-title="Adrienne and Mona">
                    <img src="images/IMG-20240713-WA0007.jpg" alt="Adrienne and Mona" loading="lazy">
                </a>
                <figcaption class="caption">Adrienne and Mona</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240713-WA0009.jpg" data-lightbox="gallery" data-title="Moored up for lunch">
                    <img src="images/IMG-20240713-WA0009.jpg" alt="Moored up for lunch" loading="lazy">
                </a>
                <figcaption class="caption">Moored up for lunch</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240713-WA0013.jpg" data-lightbox="gallery" data-title="We did it! 11 miles 4.5 hours">
                    <img src="images/IMG-20240713-WA0013.jpg" alt="We did it! 11 miles 4.5 hours" loading="lazy">
                </a>
                <figcaption class="caption">We did it! 11 miles 4.5 hours</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240713-WA0016.jpg" data-lightbox="gallery" data-title="Hay on Wye Castle for Lunch">
                    <img src="images/IMG-20240713-WA0016.jpg" alt="Hay on Wye Castle for Lunch" loading="lazy">
                </a>
                <figcaption class="caption">Hay on Wye Castle for Lunch</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/PXL_20240713_195348632.MP.jpg" data-lightbox="gallery" data-title="Sadegh and Ed playing Pool">
                    <img src="images/PXL_20240713_195348632.MP.jpg" alt="Sadegh and Ed playing Pool" loading="lazy">
                </a>
                <figcaption class="caption">Sadegh and Ed playing Pool</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/PXL_20240713_091408242.jpg" data-lightbox="gallery" data-title="Paddling">
                    <img src="images/PXL_20240713_091408242.jpg" alt="Paddling" loading="lazy">
                </a>
                <figcaption class="caption">Paddling</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240713-WA0008.jpg" data-lightbox="gallery" data-title="Flowers">
                    <img src="images/IMG-20240713-WA0008.jpg" alt="Flowers" loading="lazy">
                </a>
                <figcaption class="caption">Flowers</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240712-WA0001.jpg" data-lightbox="gallery" data-title="Tesco">
                    <img src="images/IMG-20240712-WA0001.jpg" alt="Tesco" loading="lazy">
                </a>
                <figcaption class="caption">Tesco</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240714-WA0000.jpg" data-lightbox="gallery" data-title="Treasure Trail in Hereford">
                    <img src="images/IMG-20240714-WA0000.jpg" alt="Treasure Trail in Hereford" loading="lazy">
                </a>
                <figcaption class="caption">Treasure Trail in Hereford</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240714-WA0001.jpg" data-lightbox="gallery" data-title="Edgar and Xu">
                    <img src="images/IMG-20240714-WA0001.jpg" alt="Edgar and Xu" loading="lazy">
                </a>
                <figcaption class="caption">Edgar and Xu</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20240714-WA0006.jpg" data-lightbox="gallery" data-title="The King Pigeon">
                    <img src="images/IMG-20240714-WA0006.jpg" alt="The King Pigeon" loading="lazy">
                </a>
                <figcaption class="caption">The King Pigeon</figcaption>
            </figure>                        
        </section>
        <p>Thank you for visiting the gallery!</p>
    </main>
</body>
</html>