<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Mail</title>
    <link rel="stylesheet" href="public/css/style.css">
</head>
<body>
    <div class="container">
        <h1 class="brand">
            Twin Teakwondo
        </h1>
        <div class="wrapper">
            <div class="contact">
                <h3>
                    Verschicke ein Email
                </h3>
                {{msg}}
                <form method="POST" action="send">
                    <p>
                        <label>
                            Name
                        </label>
                        <input type="text" name="name">
                    </p>
                    <!--<p>
                        <label>Studio</label>
                        <input type="text" name="Studio">
                    </p>
                    <p>
                        <label>Email Adresse</label>
                        <input type="email" name="email">
                    </p>-->
                    <p class="full">
                        <label>Betreff</label>
                        <textarea name="Betreff" rows="1"></textarea>
                    </p>
                    <p class="full">
                        <label>Nachricht</label>
                        <textarea name="Nachricht" rows="10"></textarea>
                    </p>
                    <p class="full">
                        <button type="submit">
                            Senden
                        </button>
                    </p>
                </form>
            </div>
        </div>
    </div>
</body>
</html>
