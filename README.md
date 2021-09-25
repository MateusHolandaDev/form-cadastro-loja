# form-cadastro-loja

![form2 0](https://user-images.githubusercontent.com/90210126/134777306-cd647063-f33f-4216-b144-b1ac8922b06c.png)


<h4>HTML</h4>

```
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nome da loja</title>
    <link rel="stylesheet" href="designer/cadastroloja.css">
</head>

<body>

    <main>
        <div class="cadastroloja">
            <form>
                <div class="cadastro">
                <div class="texto">
                    <label id="cadastre-se">CADASTRE-SE</label>
                    <br>
                    <br>
                    <p>Potencialize o número de vendas da sua loja e decole para o sucesso</p>
                </div>
                <label class for="nome">
                    <span>NOME</span>
                    <input type="text" id="nome" placeholder="Nome completo">
                </label>
                <BR>

                <label for="email">
                    <span>E-MAIL</span>
                    <input type="email" id="email" placeholder="nome@gmail.com.br">
                </label>
                <BR>

                <label for="telefone">
                    <span>TELEFONE</span>
                    <input type="text" id="telefone" placeholder="(xx) xxxxx-xxxx">
                </label>
            </div>
                <br>
                <br>
                
                <input type="checkbox" id="termos">
                <label id="texto" for="termos">Li e concordo com os <a href="#">termos de uso</a></label>
                </input>
                
                <button type="submit" id="">AVANÇAR</button>

            </form>
        </div>
    </main>
</body>

</html>
```
<br>
<br>

<h4>CSS</h4>

```
body {
    margin: 0;
    padding: 0;
    font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji";
    background-color: rgb(46, 134, 193);
}

main form{
    
    display:flex;
    flex-direction: column;
    background-color: rgb(250, 246, 246);
    box-shadow: 10px 6px 100px rgb(12, 11, 11);
    border-radius: 20px;
    width: 350px;
    padding:40px;
    position:absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    text-align: left;
    
    
}

main form label span {
    font-size: 16px;
    padding:20px;
    display: flex;
    flex-direction: column;
    color:#24292f;

}

main form input {
    padding:10px;
    width:300px;
    background-color:transparent;
    

}

input[type="text"], input[type="email"]{
    color:#24292f;
    border: 2px solid rgb(70, 162, 223);
    border-radius: 12px;
    
}

input::placeholder {
font-size: 17px;

}

.texto {
    text-align: center;
    color:#24292f;
    transform: translate(-4%,-7%);
    
    
    
}

#cadastre-se{
    font-size:30px;
}

button{

    padding:10px;
    width:100px;
    background-color:transparent;
    transform: translate(120%,1%);
    border:solid 2px #0ca30ce1;
    border-radius:28px;
    cursor:pointer;
    transition: .30s;
}

button:hover{
    background-color:#68d368
    
}

#termos {
    transform: translate(-49%,-50%);
}

#texto {
transform: translate(7%,-130%);
cursor: pointer;
}

a{
    color:#24292f;
}
```
