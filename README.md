# quadros-flexiveis-usando-javascript-e-css
como criar 4 quadros flexiveis usando javascript e css

Para criar quatro quadros flexíveis usando JavaScript e CSS, você pode seguir os seguintes passos:

Inicie criando um novo arquivo HTML e adicione o seguinte código HTML para definir a estrutura básica da sua página:
```
<!DOCTYPE html>
<html>
<head>
  <title>Quadros flexíveis</title>
</head>
<body>
  <div id="container">
    <div id="quadro-1"></div>
    <div id="quadro-2"></div>
    <div id="quadro-3"></div>
    <div id="quadro-4"></div>
  </div>
</body>
</html>
```

Em seguida, adicione o seguinte código CSS para estilizar os quadros e torná-los flexíveis:

```
#container {
  display: flex;
  flex-direction: row;
}

#quadro-1, #quadro-2, #quadro-3, #quadro-4 {
  width: 50%;
  height: 200px;
  background-color: #ccc;
}
```

Agora, você pode adicionar o JavaScript se desejar que os quadros tenham alguma funcionalidade interativa. Por exemplo, você pode adicionar o seguinte código JavaScript para alternar a cor de fundo dos quadros quando o usuário clica neles:

```
var quadros = document.querySelectorAll("#quadro-1, #quadro-2, #quadro-3, #quadro-4");

for (var i = 0; i < quadros.length; i++) {
  quadros[i].addEventListener("click", function() {
    this.style.backgroundColor = "#333";
  });
}
```

Isso é apenas um exemplo básico de como criar quatro quadros flexíveis usando JavaScript e CSS. Você pode personalizar o código de acordo com as suas necessidades e adicionar mais funcionalidades conforme desejar.
