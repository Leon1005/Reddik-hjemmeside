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
</style>
<div class="main">
    <p class="logo">Reddik<span>AS</span></p>
    <h1>Vi bygger din nye hjemmeside</h1>
    <p class="pitch">En kort setning om hva vi gjør og hva som skiller oss fra andre.</p>

    <button class="kontakt-button">Kontakt oss</button>
</div>
