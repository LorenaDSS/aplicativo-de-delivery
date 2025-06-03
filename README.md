# 📦 Aplicativo de Delivery

Este README tem como objetivo **explicar linha por linha**, de forma específica mas fácil de entender, o que acontece no código HTML do nosso site de delivery.

Vamos começar com o **início do arquivo**, que define configurações essenciais do HTML, como codificação, responsividade, título e estilos usados.

---

## 🔍 Código analisado:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tasty Bites</title>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css"
        integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</head>

---

# 🧠 Explicação de cada linha:
<!DOCTYPE html>
Diz ao navegador que o documento está usando HTML5.

É obrigatório no início para garantir que o site funcione corretamente nos navegadores modernos.

<html lang="en">
Abre o documento HTML.

O atributo lang="en" indica que o conteúdo está em inglês.

Se você quiser mudar para português, use lang="pt-br".

<head>
Inicia a parte não visível diretamente na tela, mas essencial para configurações da página.

Aqui ficam títulos, links de estilo, scripts, entre outros.

<meta charset="UTF-8">
Define o conjunto de caracteres como UTF-8, que permite o uso de acentos, símbolos e emojis.

Evita que palavras como "coração" ou "ação" apareçam com erros.

<meta http-equiv="X-UA-Compatible" content="IE=edge">
Garante que o site funcione com o modo mais moderno possível em navegadores antigos, como o Internet Explorer.

O X-UA-Compatible diz: "Use a versão mais atual disponível, não algo ultrapassado."

<meta name="viewport" content="width=device-width, initial-scale=1.0">
Deixa o site responsivo, ou seja, adaptável a celulares, tablets e computadores.

width=device-width: ajusta a largura da tela.

initial-scale=1.0: define o nível de zoom inicial.

<title>Tasty Bites</title>
Define o título da aba do navegador.

Neste caso, o nome da aba será "Tasty Bites".

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css" ...>
Importa a biblioteca Font Awesome, que permite o uso de ícones prontos (como coração, carrinho, estrela etc).

rel="stylesheet" diz que é um arquivo de estilo CSS.

href contém o link para esse estilo externo.

Detalhes de segurança:
integrity="...": garante que o arquivo baixado não foi modificado. Proteção contra ataques.

crossorigin="anonymous": permite carregar o arquivo sem enviar dados pessoais (cookies, etc).

<link rel="stylesheet" href="style.css">
Importa o arquivo CSS do projeto, que está salvo localmente com o nome style.css.

Aqui é onde você define cores, tamanhos, espaçamentos, fontes, etc do seu site.


