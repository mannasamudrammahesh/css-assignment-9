<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive webpage</title>
</head>
<style>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-color:black;
    color:white;
}

header {
    background: #f9a004;;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}
nav ul li a:hover{
background-color:#ffedaf;
padding:7px;
border-radius:5px;
color:black;
}

main {
    padding: 1rem;
}

.blog-post {
    margin-bottom: 2rem;
}

.blog-post img {
    max-width: 100%;
    height: 300px;
    display: block;
}

footer {
  
    color: #fff;
    text-align: center;
    padding: 1rem;
}

h1 {
    font-size: 1.75rem;
}

h2 {
    font-size: 1.5rem;
}

p {
    font-size: 1rem;
}
.foot{
height:180px;
background-color:#f9a004;
color:white;
padding:20px;
line-height:30px;
cursor:pointer;
text-align:center;
position:relative;
}
#f1:hover{
color:lightgrey;
padding:10px;
}
#f2:hover{
color:lightgrey;
padding:10px;
}
#f3:hover{
color:lightgrey;
padding:10px;
}
#f4:hover{
color:lightgrey;
padding:10px;
}
#f5:hover{
color:lightgrey;
padding:10px;
}

@media (min-width: 600px) {
    header {
        padding: 1.5rem;
    }

    h1 {
        font-size: 2rem;
    }

    h2 {
        font-size: 1.75rem;
    }

    p {
        font-size: 1.125rem;
    }

    .blog-post {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
}

@media (min-width: 1024px) {
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    nav ul {
        display: flex;
    }
    nav ul li {
        display: block;
        margin-right: 2rem;
    }
    main {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        gap: 2rem;
    }
    .blog-post {
        flex: 1;
        max-width: calc(50% - 1rem);
    }
    h1 {
        font-size: 2.5rem;
    }
    h2 {
        font-size: 2rem;
    }
    p {
        font-size: 1.25rem;
    }
}
</style>
<body>
    <header>
        <h1>Indian Elephant</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="blog-post">
            <h2>Indian Elephant Habitat</h2>
<img src="https://media.istockphoto.com/id/1138828533/photo/thailand-elephants-background.jpg?s=612x612&w=0&k=20&c=X8X4pKe79WSKtoKApUcosdS869rBhoJqzzJfmMcsbtg=" alt="Elephant">
            <p>The Indian elephant is the largest land mammal in Asia. These elephants are distinguishable by their large ears and long trunk. The trunk is used for a variety of purposes, such as picking up food, drinking water, and spraying water to cool themselves down. Indian elephants live in forested areas and eat a variety of plants. In India, they are often used for labor or tourism purposes. Some conservation efforts are currently in place to help protect these animals from extinction.</p>
        </section>
        <section class="blog-post">
            <h2>Indian Elephant Behavior</h2>
<img src="https://media.istockphoto.com/id/1921338606/photo/majestic-elephant-in-vibrant-jungle.jpg?s=612x612&w=0&k=20&c=iZWZYfcX_CehKLZgOpiSaJtlc3X_52ABoSYg2BpZBGM=">
            <p>Indian elephants are large mammals that are native to the Indian subcontinent. Indian elephants are characterized by their long trunk, large ears, and thick skin. Indian elephants typically weigh between two and four tonnes, and they can grow to be up to six metres long. Indian elephants are herbivores, and they primarily eat leaves, grasses, and fruits. Indian elephants are social animals, and they live in families called “herds”. Herds typically consist of related females and their young offspring. Indian elephants typically reproduce every four to six years, and female elephants usually give birth to a single calf. Indian elephants have a lifespan of around 60 years. Indian elephants are endangered due to habitat loss and hunting.</p>
</section>
<section class="blog-post">
        <h2>Indian Elephant Habitat </h2>
 <img src="https://media.istockphoto.com/id/1515608413/photo/majestic-asian-elephant-strolling-through-the-enchanting-forest.jpg?s=612x612&w=0&k=20&c=tQ8nSf4qFAigrI7HJ121Y-S6LR6FDmww_hqwhmzlyMk=" alt="Elephant">
<p>Indian elephants are the largest living land animals and they weigh around two hundred sixty to two thousand pounds. Indian elephants have a trunk that is used for smelling, touching, drinking, and grabbing things. Indian elephants live in hot places such as the Indian subcontinent. Indian elephants eat mainly grasses, roots, fruit, and bark. Indian elephants need to drink about fifty gallons of water per day. Indian elephants usually live in small herds of six to eight family members led by an adult female. The Indian elephant habitat has shrunk due to farming, forests being cut down, and development. Indian elephants are now an endangered species because their habitat keeps getting smaller and there are only about forty thousand Indian elephants left in the wild. People can help save Indian elephants by not cutting down forests, learning more about them, and supporting organizations that are helping to save them. Herds of Indian elephants typically consist of six to eight individuals led by an adult female. The Indian elephant’s habitat has shrunk due to farming, deforestation, and development. As a result, they are now an endangered species; with only around 40,000 individuals remaining in the wild.</p> </section>
<section class="blog-post">
<h2>Conclusion </h2><br><br>
 <img src="https://media.istockphoto.com/id/625905688/photo/wild-elephant-in-the-river-image-contains-grain-and-noise.jpg?s=612x612&w=0&k=20&c=Lrnr_7B46jRxBbHvD_fngJzUisExlvSs4ZD5Wzu-DcY=" alt="Elephant">
<p>The Indian elephant is the largest land animal in Asia and one of the two species of elephants found on the continent. These massive creatures can weigh up to six tons and stand over three meters tall at the shoulder. They are distinguishable by their large ears, which they use to fan themselves and cool down. Indian elephants are herbivores, feeding mainly on bamboo, leaves, fruit, and bark. They live in herds of ten to fifteen animals led by a dominant adult male known as a bull. Female elephants, or cows, do most of the day-to-day care for calves and lead the herd when the bull is absent. </p>
        </section>

    </main>
    <footer>
<div class="foot">
<div id="f1">Privacy Policy </div>
<div id="f2">License </div>
<div id="f3">Imprint </div>
<div id="f4">Cookies Policy </div>
<div id="f5">© 2024 all rights are reserved Terms of Use </div>
</div>
    </footer>
</body>
</html>
