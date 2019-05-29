# Pluvie
<!DOCTYPE html>
<meta charset="utf-8">
<title>Pluvie</title>

<style>
/* fond de page */
body {
  background-image: linear-gradient(0deg, silver, #040, black);
  background-size: 100%;
  background-repeat: no-repeat;
  color: white;
  height: 100vh;
  margin: 0;
  /* pour éviter l'ascenseur */
  border: 1px solid transparent;
  box-sizing: border-box;
}

/* bandeau de titre */
h2 { 
  color: white;
  border: none;
  box-shadow: none;
  background-color: rgba(255,255,255,0.3);
  border-top: 3px solid rgba(255,255,255,0.6);
  border-bottom: 3px solid rgba(255,255,255,0.6);
  margin-top: 1.33em;
  text-shadow: 3px 3px 3px black;
  padding-top: 0.5em;
  padding-bottom: 0.5em;
  margin-bottom: 1.33em;
}
#reponse {
  padding-top: 30px;
}
img {
  position: absolute;
  width: 90%;
  left: 5%;
  border-radius: 7px;
  box-shadow: 5px 5px 5px black;
}
/* contenu de la page */
body > * { padding-left: 20px; }

/* polices de caractères */
body { font-family: Roboto, sans-serif; }
h2 span { font-family: "Roboto Mono"; }

label { display: inline-block; width: 4em; margin-bottom: 0.33em}
input { width: 14em; }
</style>
<h2>Pluvie</h2>
<div class="contenu">
	<form method="get">
		<div>
			<label for="Date">Date : </label>
			<input type="date" id="txtDate" />
		</div>
		<div>
			<nobr>
				<label for="Horaire au début">Horaire au début:</label>
			</nobr>

			<select name="Horaire au début" id="Horaire au début"> 
				<option value="0">0</option> 
				<option value="1">1</option> 
			</select> 
			<label for="H">H</label>  
		</div>
		<div>
			<input type="button" id="button" value="Envoyer">
		</div>
	</form>
</div>
