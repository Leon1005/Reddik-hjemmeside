<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
    href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700&display=swap"
    rel="stylesheet"
/>
<style>
    * {
        font-family:Montserrat, Arial;
    }
    .main {
        background-color:rgb(210, 210, 210);
        position:relative;
        height:300px;

    }

.logo span {
	font-weight: 700;
}
.main h1 {
    text-align:center;
    font-size:28px;
    margin-top:60px;
}
.pitch {
    text-align:center;
    color:rgb(110, 110, 110);
    margin-left:40px;
    margin-right:40px;
}
.kontakt-button {
    position:absolute;
    left:38%;
    background-color:rgb(130, 130, 130);
    padding:8px 4px;
    border:none;
    border-radius:4px;
    font-weight:500;
    margin-top:15px;
    transition:color 0.15s
}
.kontakt-button:active {
    color:white;

}
.enkel-nettside-div {
    background-color:rgb(210, 210, 210);
    width:300px;
    padding:10px;
    border-radius:8px;
    margin-left:18px;
    margin-bottom:20px;
}
.contact-div{
    display:flex;
    flex-direction:column;
}
.contact-div h4 {
    margin-left:10px;
}
.navn-input {
    background-color:rgb(210, 210, 210);
    border:none;
    padding:6px;
    margin:6px;
    border-radius:4px;
}
.melding-input {
    background-color:rgb(210, 210, 210);
    border:none;
    padding:6px;
    margin:6px;
    height:60px;
    border-radius:4px;
}
.send-button{
    float:right;
    padding:6px 12px;
    border:none;
    font-weight:500;
    border-radius:4px;
    transition:color 0.15s
}
.send-button:active{
    color:white;
}
</style>
<div class="main">
    <p class="logo">Reddik<span>AS</span></p>
    <h1>Vi bygger din nye hjemmeside</h1>
    <p class="pitch">En kort setning om hva vi gjør og hva som skiller oss fra andre.</p>

    <button class="kontakt-button">Kontakt oss</button>
</div>

<h2>Pakkepriser</h2>
<div class="grid-div">
    <div class="enkel-nettside-div">
        <h4>Enkel nettside</h4>
        <h2>15 000</h2>
        <p>Beskrivelse om hva en enkel nettside er, og hvem det passer for</p>
        <ul>
            <li>Noen ting</li>
            <li>Som er</li>
            <li>inkludert i denne pakken</li>
        </ul>
    </div>
    <div class="enkel-nettside-div">
        <h4>Standard nettside</h4>
        <h2>25 000</h2>
        <p>Beskrivelse om hva en standard nettside er, og hvem det passer for</p>
        <ul>
            <li>Noen ting</li>
            <li>Som er</li>
            <li>inkludert i denne pakken</li>
        </ul>
    </div>
    <div class="enkel-nettside-div">
        <h4>Avansert nettside</h4>
        <h2>30 000+</h2>
        <p>Beskrivelse om hva en avansert nettside er, og hvem det passer for</p>
        <ul>
            <li>Noen ting</li>
            <li>Som er</li>
            <li>inkludert i denne pakken</li>
        </ul>
    </div>
</div>

<div class="contact-div">
    <h4>Kontakt Oss</h4>
    <input class="navn-input" type="text" placeholder="Navn">
    <input class="navn-input" type="text" placeholder="Epost">
    <input class="melding-input" type="text" placeholder="Melding">
</div>
<button class="send-button">Send</button>