#Forms
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro</title>
</head>
<body>
    <div>
        <h1>Cadastro De DEVs</h1>
        <p>Complete suas informações</p>
        <br>
    </div>

<form>
    <fieldset>
        <div>
            <label>Nome</label>
            <input type="text" name="Nome" id="Nome">
        </div>

        <div>
            <label>Sobrenome</label>
            <input type="text" name="Sobrenome" id="Sobrenome">
        </div>
    </fieldset>

    <div>
        <label>Email</label>
        <input type="email" name="email" id="email">
    </div>

    <div>
    <label>De qual lado da aplicação você desenvolve</label>
    <label>
        <input type="radio" name="devweb" value="Frontend" checked>Front-end
    </label>
    <label>
       <input type="radio" name="Devweb" value="Backend">Back-end
    </label>
    <label>
        <input type="radio" name="Devweb" value="Fullstack">Fullstack
    </label>
    </div>

    <div>
    <label>Senioridade:</label>
        <select id="Senioridade">
        <option selected disabled value="">Selecione</option>
        <option>Junior</option>
        <option>Pleno</option>
        <option>Sênior</option>
        <select>
    </div>
</form>


<fieldset>
    <div>
        <label>Selecione as tecnologias que utiliza:</label><br><br>
        <input type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
        <label for="tecnologia1">HTML</label>
        <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
        <label for="tecnologia2">CSS</label>
        <input type="checkbox" id="tecnologia3" name="tecnologia3" value="Javascript">
        <label for="tecnologia3">Javascript</label>
        <input type="checkbox" id="tecnologia4" name="tecnologia4" value="PHP">
        <label for="tecnologia4">PHP</label>
        <input type="checkbox" id="tecnologia5" name="tecnologia5" value="C#">
        <label for="tecnologia5">C#</label>
        <input type="checkbox" id="tecnologia6" name="tecnologia6" value="Python">
        <label for="tecnologia6">Python</label>
        <input type="checkbox" id="tecnologia7" name="tecnologia7" value="Java">
        <label for="tecnologia7">Java</label>
    </div>
</fieldset>

<div>
    <br><br> 
    <label>Conte Um Pouco Sobre A Sua Experiência</label>
    <textarea rows="6" style="width:26em" id="experiencia" name="experiencia"></textarea>
</div>

<button type="submit">Concluido</button>

</body>
</html>
