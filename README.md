# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:
## Step 1:
Clone the github repository into Theia IDE.
## Step 2:
Create a new Django project
## Step 3:
Write the required HTML code
## Step 4:
Run the Django server and execute the HTML files.
### code:
## Map.html:
```
<html>
<head><title>Zoo Image Map</title>
</head>
<body>
<h1 align='center'> Vandalur Zoo</h1>
<h3>Address:</h3>
<h4> Grand Southern Trunk Rd, Vandalur, Tamil Nadu 600048</h4>
<img src="static/images/map1.png" usemap="#image_map">
<map name="image_map">
  <area alt="Entrance" title="Entrance" href="ent.html" coords="12,253 -18,122 198,160 222,255 " shape="polygon">
  <area alt="Deers & Lions" title="Deers & Lions" href="deer.html" coords="225,9 234,108 456,101 565,-9 " shape="polygon">
  <area alt="Elephant Point" title="Elephant Point" href="ele.html" coords="502,306 469,376 533,260 774,362 448,373 497,249 763,284 786,373 " shape="polygon">
  <area alt="Tiger Cave Point" title="Tiger Cave Point" href="tiger.html" coords="710,94 568,163 583,233 796,251 820,152 " shape="polygon">
  <area alt="Hippopotamus" title="Hippopotamus" href="hippo.html" coords="780,166 625,166 623,46 814,76 " shape="polygon">

</map>


</body>
</html>
```
## Deer.html:
```
<html>
    <head><title>Elephant Point</title></head>
<body>
    <h1 align="center">Deers & Lions Point</h1>
    <img src="static/images/lion.png" height="300" width="500" align="center">
    <p>The Arignar Anna Zoological Park, popularly known as Vandalur Zoo, is planning to add more lions and restart the lion safari this summer itself. Lion safari was one of the major attractions at the zoo. The zoological park suspended the safari in 2021 after Covid-19 infected most of the resident lions and two succumbed to the infection. The same year, two more healthy lions died of different ailments bringing down the total count to nine.

“Lion safari is one of most sought after experiences visitors look forward to. Plans are afloat to reopen it possibly by this summer itself, which is the peak tourist season. For this reason, we are adding a few more lions to the current stock through an exchange programme,” zoo director Srinivas R Reddy told TNIE.
Central Zoo Authority has given approval for bringing two lions from Lucknow and Karnataka. “We have already received one lioness from Lucknow zoo and a male lion will be transported from Bengaluru Bannerghatta Biological Park in Karnataka in another 10 days. In exchange, we have given two tigers,” he added

Another important aspect of the exchange programme is to improve the genetic variation in the gene pool of the lions. “The idea is to introduce different bloodlines in the lion population. The current stock of lions are related to each other as excessive inbreeding is not ideal. There has to be genetic diversity to get healthy offspring,” zoo deputy director R Kanchana told TNIE.

Experts had earlier cited lack of genetic diversity among the big cats at the Vandalur Zoo as the reason behind losing so many animals between 2021-22. In 2021, the zoo lost eight big cats, which include four lions, three tigers and a leopard due to various reasons. In 2022, four big cats - a lion, tigress, jaguar and leopard - died. The park has lost 12 big cats in a span of just 15 months, probably the worst period since its inception.

According to sources, the zoo has taken measures under the current leadership to improve animal screening protocols, veterinary care and facilities. Also, several enrichment projects are ongoing to comfort the animals. The zoo hospital has been upgraded with new state-of-art equipment and an additional operation theatre.</p>
</body>
</html>
```
## Elephant.html:
```
<html>
    <head><title>Elephant Point</title></head>
<body>
    <h1 align="center">Elephant Point</h1>
    <img src="static/images/ele.png" height="300" width="500" align="center">
    <p>Elephants, the national heritage animal are one of the largest terrestrial mammals of the planet which spends most of the day in walking and grazing herbs. The Elephant enclosure in Arignar Anna Zoological Park is one of the largest enclosure spreads over an area of around three hectares of land. Elephants were taken for morning and evening walk every day. As Elephants like to spend most of their time in water, hence manually created Swimming pool and a shower is set up in the enclosure. Every day visitors can enjoy watching the shower and feed time of elephants from 3 to 4 pm in its exhibit. </p>
</body>
</html>
```
## Entrance.html:
```
<html>
    <head><title>Zoo Entrance</title></head>
<body>
    <h1 align="center">Zoo Entrance</h1>
    <img src="static/images/ent.png" height="300" width="500" align="center">
    <p>
        An ideal destination for wildlife enthusiasts, photographers, nature admirers, and experience seekers, the Arignar Anna Zoological Park offers a relaxing environment along with a serene ambiance to tourists of all ages. Located at a distance of 32 km from the city center, the park boasts more than160 different species of creatures and is considered as one of the best places to explore the popular wildlife habitat in India.

Perfect for weekend getaways, Arignar Anna Zoological Park, also known as Vandalur Zoo, is a place where you can see a large variety of wild animals such as panthers, jaguars, lions, blackbucks, hyenas, ostriches, bison, Asiatic wolf, white tiger and many more. In addition, the park houses a diverse range of fishes, butterflies, birds, reptiles, and mammals so that you can learn everything about the other life forms on earth.

There is also a Jurassic Park and a Children’s Park for families to have an unlimited dose of entertainment. Other special aspects that double your excitement on a visit to this park are a Butterfly House, a Reptile House, an Amphibian House, the Shark-shaped Aquarium, and Elephant joy rides.
    </p><h3>History</h3>
    <p>Dating its history back to the year 1855, the Arignar Anna Zoological Park is the first public zoo that was earlier formed in Madras City by Dr. Edward Belford. Later, in 1976, it was shifted to the current location of Vandalur Reserve Forest in Chennai. At that time, the park was spreading over an area of 512 ha. However, a few years later, when the work started in 1979, the authorities acquired more land to increase its size, and today, it has a total of 602 hectares of area.

Officially opened to the public in 1985, the Arignar Anna Zoological Park has everything it needs to meet the basic needs of the animals and birds. There is a separate place for every living creature and a special free zone for animals to roam around freely in peace.</p>
</body>
</html>
```
## Hippopotamus:
```
<html>
    <head><title>Hippopotamus</title></head>
<body>
    <h1 align="center">Hippopotamus</h1>
    <img src="static/images/hippo.png" height="300" width="500" align="center">
    <p>The hippopotamus one of the largest African animals exhibited in Arignar Anna Zoological Park. The enclosure is designed with a well spacious exhibit area, elevated platform, and shoreline for basking. Hippos spend around 16 hours of the day in water. For a better view of the visitors, an uprighted elevated bridge was constructed for an excellent aerial view.</p>
    <p>After elephants and rhinos, the hippopotamus is the next largest land mammal. It is also the largest extant land artiodactyl. Despite their physical resemblance to pigs and other terrestrial even-toed ungulates, the closest living relatives of the hippopotamids are cetaceans (whales, dolphins, porpoises, etc.), from which they diverged about 55 million years ago. Hippos are recognisable for their barrel-shaped torsos, wide-opening mouths with large canine tusks, nearly hairless bodies, pillar-like legs, and large size: adults average 1,500 kg (3,300 lb) for bulls (males) and 1,300 kg (2,900 lb) for cows (females). Despite its stocky shape and short legs, it is capable of running 30 km/h (19 mph) over short distances. </p>
</body>
</html>
```
## Tiger.html:
```
<html>
    <head><title>Elephant Point</title></head>
<body>
    <h1 align="center">Tiger Cave Point</h1>
    <img src="static/images/tiger.png" height="300" width="500" align="center">
    <p>The tiger (Panthera tigris) is the largest living cat species and a member of the genus Panthera. It is most recognisable for its dark vertical stripes on orange fur with a white underside. An apex predator, it primarily preys on ungulates, such as deer and wild boar. It is territorial and generally a solitary but social predator, requiring large contiguous areas of habitat to support its requirements for prey and rearing of its offspring. Tiger cubs stay with their mother for about two years and then become independent, leaving their mother's home range to establish their own. </p>
    <p>
        White tiger:
        The white tiger is a pigmentation variant of the Royal Bengal Tiger. The animal is exhibited in a wet moat, the enclosure is enriched with a water pond, an elevated wooden platform for resting, and a walking pathway.
    </p>
    <p>
        The Bengal tiger:
        The Bengal tiger is a population of the Panthera tigris tigris subspecies and the nominate Tiger subspecies.[1] It ranks among the biggest wild cats alive today.[2][3] It is considered to belong to the world's charismatic megafauna.[4]

The tiger is estimated to have been present in the Indian subcontinent since the Late Pleistocene, for about 12,000 to 16,500 years.[5][6][7] Today, it is threatened by poaching, loss and fragmentation of habitat, and was estimated at comprising fewer than 2,500 wild individuals by 2011. None of the Tiger Conservation Landscapes within its range is considered large enough to support an effective population of more than 250 adult individuals.[8] 
    </p>
</body>
</html>
```
### Output:
![zoo output ](https://github.com/pradeepsiva20/places-around-me/assets/120539823/135d1606-c9aa-4e23-8467-ccffab4eec89)
![elephant](https://github.com/pradeepsiva20/places-around-me/assets/120539823/b333c752-3a14-4a79-85ac-c8d3b194e181)
![entrance](https://github.com/pradeepsiva20/places-around-me/assets/120539823/51ffaecd-0df7-46d0-95ef-53a12b92a8de)
![hippo](https://github.com/pradeepsiva20/places-around-me/assets/120539823/c727e541-b807-4876-8960-0872c86fcc0d)
![tiger](https://github.com/pradeepsiva20/places-around-me/assets/120539823/fdace7af-4fde-4f88-a5ec-ebb4df2139d3)
![liondeer](https://github.com/pradeepsiva20/places-around-me/assets/120539823/85dcf9f9-deb7-4217-8892-4ca7e958aec1)
