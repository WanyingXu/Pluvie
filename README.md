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

label { display: inline; width: 4em; margin-bottom: 0.33em}
input { width: 14em; }

</style>

<h2>Pluvie</h2>
<div class="contenu">
	<form method ="get">
		<div>
			<label for="Date">Date : </label>
			<input type="date" id="txtDate" />
		</div>
	<nobr>
		<div>
			<label for="Horaire au début">Horaire au début:</label>
			<select name="Horaire au début" id="Horaire au début">
				<option value="0">0</option>
				<option value="1">1</option>
				<option value="2">2</option>
				<option value="3">3</option>
				<option value="4">4</option>
				<option value="5">5</option>
				<option value="6">6</option>
				<option value="7">7</option>
				<option value="8">8</option>
				<option value="9">9</option>
				<option value="10">10</option>
				<option value="11">11</option>
				<option value="12">12</option>
				<option value="13">13</option>
				<option value="14">14</option>
				<option value="15">15</option>
				<option value="16">16</option>
				<option value="17">17</option>
				<option value="18">18</option>
				<option value="19">19</option>
				<option value="20">20</option>
				<option value="21">21</option>
				<option value="22">22</option>
				<option value="23">23</option>
				<option value="24">24</option>
		    </select>
		<label for="H">H</label> 
		
		    <select>
				<option value="0">0</option>
				<option value="6">6</option>
				<option value="12">12</option>
				<option value="18">18</option>
				<option value="24">24</option>
				<option value="30">30</option>
				<option value="36">36</option>
				<option value="42">42</option>
				<option value="48">48</option>
				<option value="54">54</option>
				<option value="60">60</option>
		   </select>
			<label for="Min">Min</label>
		</div>
	</nobr>
		<div>
			<input type="button" id="button" value="Envoyer">
		</div>
	</form>
</div>
