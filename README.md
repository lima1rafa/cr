#main {
    width: 940px;
    margin: 0 auto;
}

form {
    margin: 40px 0;
}

form label {
    display:block;
    font-size: 20px;
    margin: 0 0 10px;
}

form input {
    display: block;
    margin: 0 0 20px;
    padding: 10px 25px;
    width: 50%;
}
<main>
<form>
<label> Grifinória </label>
<input type="radio" value="grifinoria" id="radio-grifinoria">
<label> Sonserina </label>
<input type="radio" value="sonserina" id="radio-sonserina">
<label> Lufa-Lufa </label>
<input type="radio" value="lufa-lufa" id="radio-lufa-lufa">
<label> Corvinal </label>
<input type="radio" value="corvinal" id="radio-corvinal">
<input type="submit" value="Enviar formulário" />
</form>
</main>
<p class="paragrafo">

p {
    color: blue;
}

p.paragrafo {
    color: red;
}

.paragrafo {
    color: purple;
}
<label for="mensagem">Mensagem</label>
<textarea cols="70" rows="10" id="mensagem" class="input-padrao"></textarea>
<div>
    <p>Como prefere o nosso contato?</p>
    <label for="radio-email">
        <input type="radio" name="contato" value="email" id="radio-email">
        Email
    </label>
    
    <label for="radio-telefone">
        <input type="radio" name="contato" value="telefone" id="radio-telefone"> 
        Telefone
    </label>
    
    <label for="radio-whatsapp">
        <input type="radio" name="contato" value="whatsapp" id="radio-whatsapp">
        WhatsApp
    </label>
</div>
<div>
    <p>Qual horário prefere ser atendido?</p>
    <select>
        <option>Manhã</option>
        <option>Tarde</option>
        <option>Noite</option>
    </select>
</div>
<label class="checkbox">
    <input type="checkbox">
    Gostaria de receber nossas novidades por email?
</label>
form label {
    display:block;
    font-size: 20px;
    margin: 0 0 10px;
}
form label, form p {
    display:block;
    font-size: 20px;
    ma
}
form input {
    display: block;
    margin: 0 0 20px;
    padding: 10px 25px;
    width: 50%;
}
.input-padrao {
    display: block;
    margin: 0 0 20px;
    padding: 10px 25px;
    width: 50%;
}
.checkbox {
    margin: 20px 0;
}
