!DOCTYPE html>
<html lang="sv">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device.width, inital-scale="1">
        <title> Om Html </title>
    </head> 
    <footer>
        <p>Author: Olliver Rydh</p>
        <p><a href="mailto:olliver.rydh@edu.gnosjo.se"> Mail Directly </a> </p>
        <p><a href="https://accounts.google.com/v3/signin/identifier?dsh=S-1375134495%3A1661867316363326&continue=https%3A%2F%2Fmail.google.com%2Fmail%2Fu%2F0%2F&emr=1&followup=https%3A%2F%2Fmail.google.com%2Fmail%2Fu%2F0%2F&osid=1&passive=1209600&service=mail&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AQN2RmU16_QfFjtT-CIgKIc68MDyeRwfh2NuuT9QwRAhreC-RB6UXmsbFx0aTHPBItwnxQZPp37KEg">olliver.rydh@edu.gnosjo.se</a></p>
        <p>____________________________________________________________________________________________________________________________________________________________</p>
    </footer>
    <body>
        <h1>Om Html</h1> <!-- en kommentar -->
            <h5>- HyperText Markup Language </h5> (ungefär "markeringsspråk för hypertext")
            <h5>- hypertext </h5> är en text som man kan börja och sluta läsa varsomehelst
            <h5>- html består av taggar </h5> och börjar med "< >", slutar med "< / >"
            <br>några exempel är: style, h1 (header), p (paragraph), br (breakrow)
            <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiWyrze0u75AhXEQvEDHfL9B7gQwqsBegQIBBAB&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DxvFZjo5PgG0&usg=AOvVaw1bR_FN-SnfIGtKD3fjAA5P" target="_blank" title="Info">Klicka här för mer information.</a> <!-- En link med eget namn -->
            <br>Ställ in datum nedan. <br> <input type="date"> <input type="time">
            <marquee>Ställ in datum åvan.</marquee> <!-- weeeeeeee -->
            <h1>påverka text</h1>
            <a href="theme.html"> Themes </a><br>
            <img src="bilder\logga.png" alt="en bild på en logga" title="loggan"><br>
            <h5>Bättre väg att skapa bilder</h5><br>
            <!---Image taggen-->
            <img src="FörstaProjekt.png" alt="Text-bild" title="Första Projekt"><br>
            <!---Figure taggen-->
            <h5>&NonBreakingSpace;</h5><br>
            <figure>
                <img src="FörstaProjekt.png" alt="Text-bild" title="Första Projekt">
                <figcaption> Min första bild </figcaption>
            </figure><br>
            <!--Picture taggen-->
            <picture>
                <source media="(max-width:450px)" srcset="FörstaProjektSmall.png">
                <img src="FörstaProjekt.png" alt="Text-bild" title="Första Projekt">
            </picture><br>
            &aring;, &Aring;, &auml;, &Auml;, &ouml;, &Ouml;, Hej&nbsp;Hej <!-- för å, ä, ö ( och mellanrum för t.ex. tabeller ) ifall det inte fungerar--><br>
            <h1>tips på webbsidor</h1>
            <a href="https://lipsum.com/"> lipsum.com</a> <br>
            <a href="https://www.w3schools.com/"> w3schools.com</a> <br>
            <a href="https://www.w3schools.com/"> developer.mozilla.org</a><br>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/qz0aGYrrlhU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </body>
</html>
