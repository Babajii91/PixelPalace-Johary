<script>
    let goodies = [
        {
	"nom":"sac_mario_danse_enfant",
	"image":"https://boutiquemario.fr/277-medium_default/mario-danse.jpg",
	"prix": "29.90",
	"category":"sac",
	"license": "Mario"
},
{
	"nom":"trousse_mario_danse",
	"image":"https://boutiquemario.fr/188-medium_default/mario-danse.jpg",
	"prix": "19.90",
	"category":"trousse",
	"license": "Mario"
},
{
	"nom":"figurine_mario",
	"image":"https://boutiquemario.fr/51-medium_default/mario-geant.jpg",
	"prix": "29.90",
	"category":"figurine",
	"license": "Mario"
},
{
	"nom":"pop_ellie",
	"image":"https://www.derivefigurine.com/65033/pop-part-ii-figurine-ellie-601.jpg",
	"prix": "14.90",
	"category":"figurine",
	"license": "The_last_of_us"
},
{
	"nom":"sac_the_last_of_us",
	"image":"https://www.derivefigurine.com/60363/sac-dos-firefly.jpg",
	"prix": "44.90",
	"category":"sac",
	"license": "The_last_of_us"
},
{
	"nom":"pelluche_ellie",
	"image":"https://www.derivefigurine.com/54265/peluche-ellie-stubbins.jpg",
	"prix": "17.90",
	"category":"pelluche",
	"license": "The_last_of_us"
},
{
	"nom":"figurine_atreus",
	"image":"https://www.1001hobbies.fr/1899729-large_default/good-smile-company-222378-god-of-war-atreus-pop-up-parade-16cm.jpg",
	"prix": "59.99",
	"category":"figurine",
	"license": "God_of_war"
},
{
	"nom":"figurine_kratos",
	"image":"https://www.1001hobbies.fr/2182355-large_default/numskull-nmsk-ns4477-god-of-war-tubbz-figurine-pvc-kratos-boxed-editio.jpg",
	"prix": "22.99",
	"category":"figurine",
	"license": "God_of_war"
},
{
	"nom":"blades_of_chaos",
	"image":"https://i.etsystatic.com/33277842/r/il/e61ec4/5614622772/il_794xN.5614622772_lzo7.jpg",
	"prix": "149.70",
	"category":"replique",
	"license": "God_of_war"
},
{
	"nom":"mug_braum",
	"image":"https://www.abystyle.com/7093432-large_default/league-of-legends-mug-braum-poros.jpg",
	"prix": "9.99",
	"category":"mug",
	"license": "Lol"
},
{
	"nom":"tapis_souris_lol",
	"image":"https://www.abystyle.com/7092186-large_default/league-of-legends-tapis-de-souris-souple-poro.jpg",
	"prix": "9.99",
	"category":"tapis_souris",
	"license": "Lol"
},
{
	"nom":"coupe_vent_valorant",
	"image":"https://images.contentstack.io/v3/assets/blt5bbf09732528de36/bltb36e5b0bb016ca50/6042b29c1322a9094ddee7ae/Jacket_04.jpg",
	"prix": "127.50",
	"category":"vetement",
	"license": "Valorant"
}
    ];
    
{#each goodies as goodie}
    <div class="container-goodies">
        <div class="goodie-info">
            <img src={goodie.image} alt={goodie.nom} />
            <h2>{goodie.nom}</h2>
            <p>Prix: {goodie.prix}</p>
            <p>Catégorie: {goodie.category}</p>
            <p>Licence: {goodie.license}</p>
            <div class="buy-button">
                <button>Acheter</button>
            </div>
        </div>
        <div class="description">
            <p>{goodie.description}</p>
        </div>
    </div>
{/each}