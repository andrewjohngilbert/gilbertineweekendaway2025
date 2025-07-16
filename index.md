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
        <h1>Gilbertine Weekend Away - Bristol 2025</h1>
        <p>For the Gilbertine Lab, weekend away 2025, we headed to Bristol to race go-karts and explore the immerisve Wake the Tiger experience.</p>
        <section class="gallery">
            <figure class="gallery-item">
                <a href="images/IMG_1539.jpeg" data-lightbox="gallery" data-title="StoneHenge">
                    <img src="images/IMG_1539.jpeg" alt=" StoneHenge" loading="lazy">
                </a>
                <figcaption class="caption">StoneHenge driveby</figcaption>
                </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0001.jpg" data-lightbox="gallery" data-title="Walking through the fields">
                    <img src="images/IMG-20250703-WA0001.jpg" alt="Walking through the fields" loading="lazy">
                </a>
                <figcaption class="caption">Walking in cheddar</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1542.jpeg" data-lightbox="gallery" data-title="Sadegh and Andy admiring the view">
                    <img src="images/IMG_1542.jpeg" alt="Sadegh and Andy admiring the view" loading="lazy">
                </a>
                <figcaption class="caption">Sadegh and Andy admiring the view</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250702-WA0013.jpg" data-lightbox="gallery" data-title="Morning coffee">
                    <img src="images/IMG-20250702-WA0013.jpg" alt="Morning coffee" loading="lazy">
                </a>
                <figcaption class="caption">The Gilbertines in Cheddar</figcaption>
            </figure> 
            <figure class="gallery-item">
                <a href="images/PXL_20250703_172038311.jpg" data-lightbox="gallery" data-title="Exploring the garden">
                    <img src="images/PXL_20250703_172038311.jpg" alt="Exploring the garden" loading="lazy">
                </a>
                <figcaption class="caption">So many seaguls</figcaption>
            </figure>                       
            <figure class="gallery-item">
                <a href="images/PXL_20250702_180633206.jpg" data-lightbox="gallery" data-title="Unpacking the car">
                    <img src="images/PXL_20250702_180633206.jpg" alt="Unpacking the car" loading="lazy">
                </a>
                <figcaption class="caption">Xu and Sadegh on the BBQ</figcaption>
            </figure> 
            <figure class="gallery-item">
                <a href="images/PXL_20250702_173720249.jpg" data-lightbox="gallery" data-title="Arrival at the house">
                    <img src="images/PXL_20250702_173720249.jpg" alt="Arrival at the house" loading="lazy">
                </a>
                <figcaption class="caption">Chefs Ed and Sadegh</figcaption>
            </figure>                      
            <figure class="gallery-item">
                <a href="images/IMG_1546.jpeg" data-lightbox="gallery" data-title="View of the countryside">
                    <img src="images/IMG_1546.jpeg" alt="View of the countryside" loading="lazy">
                </a>
                <figcaption class="caption">Xu's Birthday Cake</figcaption>
            </figure>                      
            <figure class="gallery-item">
                <a href="images/24C710C9-0995-431B-8362-02E3602AEABF.jpg" data-lightbox="gallery" data-title="The Clifton Suspension Bridge">
                    <img src="images/24C710C9-0995-431B-8362-02E3602AEABF.jpg" alt="The Clifton Suspension Bridge" loading="lazy">
                </a>
                <figcaption class="caption">Clifton Suspension Bridge</figcaption>
            </figure>     
            <figure class="gallery-item">
                <a href="images/IMG-20250702-WA0007.jpg" data-lightbox="gallery" data-title="Relaxing after dinner">
                    <img src="images/IMG-20250702-WA0007.jpg" alt="Relaxing after dinner" loading="lazy">
                </a>
                <figcaption class="caption">The Gilbertines in Bristol</figcaption>
            </figure>   
            <figure class="gallery-item">
                <a href="images/IMG_1575.jpeg" data-lightbox="gallery" data-title="Exploring the woods">
                    <img src="images/IMG_1575.jpeg" alt="Exploring the woods" loading="lazy">
                </a>
                <figcaption class="caption">Walking with purpose</figcaption>
            </figure>                                         
            <figure class="gallery-item">
                <a href="images/IMG_1545.jpeg" data-lightbox="gallery" data-title="Banksy Well hung lover in Bristol">
                    <img src="images/IMG_1545.jpeg" alt="Banksy Well hung lover in Bristol" loading="lazy">
                </a>
                <figcaption class="caption">Banksy "Well hung lover" in Bristol</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/24DB4473-954E-44EB-B515-8AA7820110A8.jpeg" data-lightbox="gallery" data-title="Adrienne and Irene preped for the karting">
                    <img src="images/24DB4473-954E-44EB-B515-8AA7820110A8.jpeg" alt="Adrienne and Irene preped for the karting" loading="lazy">
                </a>
                <figcaption class="caption">Adrienne and Irene preped for the karting</figcaption>
            </figure>                      
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0007.jpg" data-lightbox="gallery" data-title="Lunch stop">
                    <img src="images/IMG-20250703-WA0007.jpg" alt="Lunch stop" loading="lazy">
                </a>
                <figcaption class="caption">After the Karting</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0009.jpg" data-lightbox="gallery" data-title="Exploring Hereford">
                    <img src="images/IMG-20250703-WA0009.jpg" alt="Exploring Hereford" loading="lazy">
                </a>
                <figcaption class="caption">The Winners</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0011.jpg" data-lightbox="gallery" data-title="Group at the cathedral">
                    <img src="images/IMG-20250703-WA0011.jpg" alt="Group at the cathedral" loading="lazy">
                </a>
                <figcaption class="caption">Race 1 times</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0012.jpg" data-lightbox="gallery" data-title="Afternoon stroll">
                    <img src="images/IMG-20250703-WA0012.jpg" alt="Afternoon stroll" loading="lazy">
                </a>
                <figcaption class="caption">Race 2 Times</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0015.jpg" data-lightbox="gallery" data-title="Evening walk">
                    <img src="images/IMG-20250703-WA0015.jpg" alt="Evening walk" loading="lazy">
                </a>
                <figcaption class="caption">Gilbertines in Bristol II</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0020.jpg" data-lightbox="gallery" data-title="Board games night">
                    <img src="images/IMG-20250703-WA0020.jpg" alt="Board games night" loading="lazy">
                </a>
                <figcaption class="caption">The View</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1607.jpeg" data-lightbox="gallery" data-title="Breakfast time">
                    <img src="images/IMG_1607.jpeg" alt="Breakfast time" loading="lazy">
                </a>
                <figcaption class="caption">4th July Fireworks</figcaption>
            </figure> 
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0013.jpg" data-lightbox="gallery" data-title="Looking back">
                    <img src="images/IMG-20250704-WA0013.jpg" alt="Looking back" loading="lazy">
                </a>
                <figcaption class="caption">The fireworks...</figcaption>
            </figure>            
            <figure class="gallery-item">
                <a href="images/IMG_1611.jpeg" data-lightbox="gallery" data-title="Ready for adventure">
                    <img src="images/IMG_1611.jpeg" alt="Ready for adventure" loading="lazy">
                </a>
                <figcaption class="caption">Wake the Tiger</figcaption>
            </figure>  
<figure class="gallery-item">
                <a href="images/IMG-20250704-WA0027.jpg" data-lightbox="gallery" data-title="Bonus photo 4">
                    <img src="images/IMG-20250704-WA0027.jpg" alt="Bonus photo 4" loading="lazy">
                </a>
                <figcaption class="caption">wake the Tiger </figcaption>
            </figure>            
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0003.jpg" data-lightbox="gallery" data-title="Packing up">
                    <img src="images/IMG-20250704-WA0003.jpg" alt="Packing up" loading="lazy">
                </a>
                <figcaption class="caption">Andy on the slide</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0004.jpg" data-lightbox="gallery" data-title="Final group photo">
                    <img src="images/IMG-20250704-WA0004.jpg" alt="Final group photo" loading="lazy">
                </a>
                <figcaption class="caption">Adrienne on the slide</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0005.jpg" data-lightbox="gallery" data-title="Saying goodbye">
                    <img src="images/IMG-20250704-WA0005.jpg" alt="Saying goodbye" loading="lazy">
                </a>
                <figcaption class="caption">Sadegh on the slide</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0010.jpg" data-lightbox="gallery" data-title="Leaving Hereford">
                    <img src="images/IMG-20250704-WA0010.jpg" alt="Leaving Hereford" loading="lazy">
                </a>
                <figcaption class="caption">King Ferby</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0011.jpg" data-lightbox="gallery" data-title="On the road again">
                    <img src="images/IMG-20250704-WA0011.jpg" alt="On the road again" loading="lazy">
                </a>
                <figcaption class="caption">On the road again</figcaption>
            </figure>            
            <figure class="gallery-item">
                <a href="images/IMG_1621.jpeg" data-lightbox="gallery" data-title="Packing up the canoes">
                    <img src="images/IMG_1621.jpeg" alt="Packing up the canoes" loading="lazy">
                </a>
                <figcaption class="caption">ed and his hands</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0025.jpg" data-lightbox="gallery" data-title="Bonus photo 2">
                    <img src="images/IMG-20250704-WA0025.jpg" alt="Bonus photo 2" loading="lazy">
                </a>
                <figcaption class="caption">Ed and Obi's special lasanges</figcaption>
            </figure>  
                        <figure class="gallery-item">
                <a href="images/PXL_20250704_100932680.jpg" data-lightbox="gallery" data-title="Final morning">
                    <img src="images/PXL_20250704_100932680.jpg" alt="Final morning" loading="lazy">
                </a>
                <figcaption class="caption">King Sadegh</figcaption>
            </figure>    
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0026.jpg" data-lightbox="gallery" data-title="Bonus photo 3">
                    <img src="images/IMG-20250704-WA0026.jpg" alt="Bonus photo 3" loading="lazy">
                </a>
                <figcaption class="caption">Frozen cocktails</figcaption>
            </figure>                  
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0024.jpg" data-lightbox="gallery" data-title="Bonus photo 1">
                    <img src="images/IMG-20250704-WA0024.jpg" alt="Bonus photo 1" loading="lazy">
                </a>
                <figcaption class="caption">The Gilbertines in Bath</figcaption>
            </figure>                                             
        </section>
        <p>Thank you for visiting the gallery!</p>
    </main>
</body>
</html>