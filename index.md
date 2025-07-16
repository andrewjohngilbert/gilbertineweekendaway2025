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
            <figure class="gallery-item">
                <a href="images/24C710C9-0995-431B-8362-02E3602AEABF.jpg" data-lightbox="gallery" data-title="Group photo by the river">
                    <img src="images/24C710C9-0995-431B-8362-02E3602AEABF.jpg" alt="Group photo by the river" loading="lazy">
                </a>
                <figcaption class="caption">Group photo by the river</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/24DB4473-954E-44EB-B515-8AA7820110A8.jpeg" data-lightbox="gallery" data-title="Smiling faces on the trail">
                    <img src="images/24DB4473-954E-44EB-B515-8AA7820110A8.jpeg" alt="Smiling faces on the trail" loading="lazy">
                </a>
                <figcaption class="caption">Smiling faces on the trail</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1539.jpeg" data-lightbox="gallery" data-title="Canoes ready for launch">
                    <img src="images/IMG_1539.jpeg" alt="Canoes ready for launch" loading="lazy">
                </a>
                <figcaption class="caption">Canoes ready for launch</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1542.jpeg" data-lightbox="gallery" data-title="Paddling down the Wye">
                    <img src="images/IMG_1542.jpeg" alt="Paddling down the Wye" loading="lazy">
                </a>
                <figcaption class="caption">Paddling down the Wye</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1545.jpeg" data-lightbox="gallery" data-title="Lunch break on the riverbank">
                    <img src="images/IMG_1545.jpeg" alt="Lunch break on the riverbank" loading="lazy">
                </a>
                <figcaption class="caption">Lunch break on the riverbank</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1546.jpeg" data-lightbox="gallery" data-title="View of the countryside">
                    <img src="images/IMG_1546.jpeg" alt="View of the countryside" loading="lazy">
                </a>
                <figcaption class="caption">View of the countryside</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1549.jpeg" data-lightbox="gallery" data-title="Canoeing team in action">
                    <img src="images/IMG_1549.jpeg" alt="Canoeing team in action" loading="lazy">
                </a>
                <figcaption class="caption">Canoeing team in action</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1568.jpeg" data-lightbox="gallery" data-title="Evening gathering">
                    <img src="images/IMG_1568.jpeg" alt="Evening gathering" loading="lazy">
                </a>
                <figcaption class="caption">Evening gathering</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1569.jpeg" data-lightbox="gallery" data-title="Sunset over Hereford">
                    <img src="images/IMG_1569.jpeg" alt="Sunset over Hereford" loading="lazy">
                </a>
                <figcaption class="caption">Sunset over Hereford</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1575.jpeg" data-lightbox="gallery" data-title="Exploring the woods">
                    <img src="images/IMG_1575.jpeg" alt="Exploring the woods" loading="lazy">
                </a>
                <figcaption class="caption">Exploring the woods</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1577.jpeg" data-lightbox="gallery" data-title="Team selfie">
                    <img src="images/IMG_1577.jpeg" alt="Team selfie" loading="lazy">
                </a>
                <figcaption class="caption">Team selfie</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1607.jpeg" data-lightbox="gallery" data-title="Breakfast time">
                    <img src="images/IMG_1607.jpeg" alt="Breakfast time" loading="lazy">
                </a>
                <figcaption class="caption">Breakfast time</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1611.jpeg" data-lightbox="gallery" data-title="Ready for adventure">
                    <img src="images/IMG_1611.jpeg" alt="Ready for adventure" loading="lazy">
                </a>
                <figcaption class="caption">Ready for adventure</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1612.jpeg" data-lightbox="gallery" data-title="River reflections">
                    <img src="images/IMG_1612.jpeg" alt="River reflections" loading="lazy">
                </a>
                <figcaption class="caption">River reflections</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG_1621.jpeg" data-lightbox="gallery" data-title="Packing up the canoes">
                    <img src="images/IMG_1621.jpeg" alt="Packing up the canoes" loading="lazy">
                </a>
                <figcaption class="caption">Packing up the canoes</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250702-WA0002.jpg" data-lightbox="gallery" data-title="Arriving at the cottage">
                    <img src="images/IMG-20250702-WA0002.jpg" alt="Arriving at the cottage" loading="lazy">
                </a>
                <figcaption class="caption">Arriving at the cottage</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250702-WA0003.jpg" data-lightbox="gallery" data-title="Unpacking the van">
                    <img src="images/IMG-20250702-WA0003.jpg" alt="Unpacking the van" loading="lazy">
                </a>
                <figcaption class="caption">Unpacking the van</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250702-WA0005.jpg" data-lightbox="gallery" data-title="First group meal">
                    <img src="images/IMG-20250702-WA0005.jpg" alt="First group meal" loading="lazy">
                </a>
                <figcaption class="caption">First group meal</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250702-WA0006.jpg" data-lightbox="gallery" data-title="Evening games">
                    <img src="images/IMG-20250702-WA0006.jpg" alt="Evening games" loading="lazy">
                </a>
                <figcaption class="caption">Evening games</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250702-WA0007.jpg" data-lightbox="gallery" data-title="Relaxing after dinner">
                    <img src="images/IMG-20250702-WA0007.jpg" alt="Relaxing after dinner" loading="lazy">
                </a>
                <figcaption class="caption">Relaxing after dinner</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250702-WA0013.jpg" data-lightbox="gallery" data-title="Morning coffee">
                    <img src="images/IMG-20250702-WA0013.jpg" alt="Morning coffee" loading="lazy">
                </a>
                <figcaption class="caption">Morning coffee</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0000.jpg" data-lightbox="gallery" data-title="Setting off for the day">
                    <img src="images/IMG-20250703-WA0000.jpg" alt="Setting off for the day" loading="lazy">
                </a>
                <figcaption class="caption">Setting off for the day</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0001.jpg" data-lightbox="gallery" data-title="Walking through the fields">
                    <img src="images/IMG-20250703-WA0001.jpg" alt="Walking through the fields" loading="lazy">
                </a>
                <figcaption class="caption">Walking through the fields</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0002.jpg" data-lightbox="gallery" data-title="Crossing the bridge">
                    <img src="images/IMG-20250703-WA0002.jpg" alt="Crossing the bridge" loading="lazy">
                </a>
                <figcaption class="caption">Crossing the bridge</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0007.jpg" data-lightbox="gallery" data-title="Lunch stop">
                    <img src="images/IMG-20250703-WA0007.jpg" alt="Lunch stop" loading="lazy">
                </a>
                <figcaption class="caption">Lunch stop</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0009.jpg" data-lightbox="gallery" data-title="Exploring Hereford">
                    <img src="images/IMG-20250703-WA0009.jpg" alt="Exploring Hereford" loading="lazy">
                </a>
                <figcaption class="caption">Exploring Hereford</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0011.jpg" data-lightbox="gallery" data-title="Group at the cathedral">
                    <img src="images/IMG-20250703-WA0011.jpg" alt="Group at the cathedral" loading="lazy">
                </a>
                <figcaption class="caption">Group at the cathedral</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0012.jpg" data-lightbox="gallery" data-title="Afternoon stroll">
                    <img src="images/IMG-20250703-WA0012.jpg" alt="Afternoon stroll" loading="lazy">
                </a>
                <figcaption class="caption">Afternoon stroll</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0013.jpg" data-lightbox="gallery" data-title="Enjoying the sunshine">
                    <img src="images/IMG-20250703-WA0013.jpg" alt="Enjoying the sunshine" loading="lazy">
                </a>
                <figcaption class="caption">Enjoying the sunshine</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0015.jpg" data-lightbox="gallery" data-title="Evening walk">
                    <img src="images/IMG-20250703-WA0015.jpg" alt="Evening walk" loading="lazy">
                </a>
                <figcaption class="caption">Evening walk</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0019.jpg" data-lightbox="gallery" data-title="Group dinner">
                    <img src="images/IMG-20250703-WA0019.jpg" alt="Group dinner" loading="lazy">
                </a>
                <figcaption class="caption">Group dinner</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0020.jpg" data-lightbox="gallery" data-title="Board games night">
                    <img src="images/IMG-20250703-WA0020.jpg" alt="Board games night" loading="lazy">
                </a>
                <figcaption class="caption">Board games night</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250703-WA0021.jpg" data-lightbox="gallery" data-title="Relaxing in the lounge">
                    <img src="images/IMG-20250703-WA0021.jpg" alt="Relaxing in the lounge" loading="lazy">
                </a>
                <figcaption class="caption">Relaxing in the lounge</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0003.jpg" data-lightbox="gallery" data-title="Packing up">
                    <img src="images/IMG-20250704-WA0003.jpg" alt="Packing up" loading="lazy">
                </a>
                <figcaption class="caption">Packing up</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0004.jpg" data-lightbox="gallery" data-title="Final group photo">
                    <img src="images/IMG-20250704-WA0004.jpg" alt="Final group photo" loading="lazy">
                </a>
                <figcaption class="caption">Final group photo</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0005.jpg" data-lightbox="gallery" data-title="Saying goodbye">
                    <img src="images/IMG-20250704-WA0005.jpg" alt="Saying goodbye" loading="lazy">
                </a>
                <figcaption class="caption">Saying goodbye</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0006.jpg" data-lightbox="gallery" data-title="Last look at the cottage">
                    <img src="images/IMG-20250704-WA0006.jpg" alt="Last look at the cottage" loading="lazy">
                </a>
                <figcaption class="caption">Last look at the cottage</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0007.jpg" data-lightbox="gallery" data-title="Journey home">
                    <img src="images/IMG-20250704-WA0007.jpg" alt="Journey home" loading="lazy">
                </a>
                <figcaption class="caption">Journey home</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0008.jpg" data-lightbox="gallery" data-title="Car packed and ready">
                    <img src="images/IMG-20250704-WA0008.jpg" alt="Car packed and ready" loading="lazy">
                </a>
                <figcaption class="caption">Car packed and ready</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0009.jpg" data-lightbox="gallery" data-title="Final goodbyes">
                    <img src="images/IMG-20250704-WA0009.jpg" alt="Final goodbyes" loading="lazy">
                </a>
                <figcaption class="caption">Final goodbyes</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0010.jpg" data-lightbox="gallery" data-title="Leaving Hereford">
                    <img src="images/IMG-20250704-WA0010.jpg" alt="Leaving Hereford" loading="lazy">
                </a>
                <figcaption class="caption">Leaving Hereford</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0011.jpg" data-lightbox="gallery" data-title="On the road again">
                    <img src="images/IMG-20250704-WA0011.jpg" alt="On the road again" loading="lazy">
                </a>
                <figcaption class="caption">On the road again</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0012.jpg" data-lightbox="gallery" data-title="Trip memories">
                    <img src="images/IMG-20250704-WA0012.jpg" alt="Trip memories" loading="lazy">
                </a>
                <figcaption class="caption">Trip memories</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0013.jpg" data-lightbox="gallery" data-title="Looking back">
                    <img src="images/IMG-20250704-WA0013.jpg" alt="Looking back" loading="lazy">
                </a>
                <figcaption class="caption">Looking back</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0014.jpg" data-lightbox="gallery" data-title="Last photo of the trip">
                    <img src="images/IMG-20250704-WA0014.jpg" alt="Last photo of the trip" loading="lazy">
                </a>
                <figcaption class="caption">Last photo of the trip</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0024.jpg" data-lightbox="gallery" data-title="Bonus photo 1">
                    <img src="images/IMG-20250704-WA0024.jpg" alt="Bonus photo 1" loading="lazy">
                </a>
                <figcaption class="caption">Bonus photo 1</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0025.jpg" data-lightbox="gallery" data-title="Bonus photo 2">
                    <img src="images/IMG-20250704-WA0025.jpg" alt="Bonus photo 2" loading="lazy">
                </a>
                <figcaption class="caption">Bonus photo 2</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0026.jpg" data-lightbox="gallery" data-title="Bonus photo 3">
                    <img src="images/IMG-20250704-WA0026.jpg" alt="Bonus photo 3" loading="lazy">
                </a>
                <figcaption class="caption">Bonus photo 3</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/IMG-20250704-WA0027.jpg" data-lightbox="gallery" data-title="Bonus photo 4">
                    <img src="images/IMG-20250704-WA0027.jpg" alt="Bonus photo 4" loading="lazy">
                </a>
                <figcaption class="caption">Bonus photo 4</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/PXL_20250702_173720249.jpg" data-lightbox="gallery" data-title="Arrival at the house">
                    <img src="images/PXL_20250702_173720249.jpg" alt="Arrival at the house" loading="lazy">
                </a>
                <figcaption class="caption">Arrival at the house</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/PXL_20250702_180633206.jpg" data-lightbox="gallery" data-title="Unpacking the car">
                    <img src="images/PXL_20250702_180633206.jpg" alt="Unpacking the car" loading="lazy">
                </a>
                <figcaption class="caption">Unpacking the car</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/PXL_20250703_172038311.jpg" data-lightbox="gallery" data-title="Exploring the garden">
                    <img src="images/PXL_20250703_172038311.jpg" alt="Exploring the garden" loading="lazy">
                </a>
                <figcaption class="caption">Exploring the garden</figcaption>
            </figure>
            <figure class="gallery-item">
                <a href="images/PXL_20250704_100932680.jpg" data-lightbox="gallery" data-title="Final morning">
                    <img src="images/PXL_20250704_100932680.jpg" alt="Final morning" loading="lazy">
                </a>
                <figcaption class="caption">Final morning</figcaption>
            </figure>
        </section>
        <p>Thank you for visiting the gallery!</p>
    </main>
</body>
</html>