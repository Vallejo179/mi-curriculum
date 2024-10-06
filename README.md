<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Currículum Vitae</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #FFE1FF;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background-color:  #E4B1F0;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1, h2 {
            color: #7E60BF;
        }
        .profile {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            margin-right: 20px;
        }
        .contact-info, .education, .skills {
            margin-bottom: 20px;
        }
        .contact-info ul {
            list-style: none;
            padding: 0;
        }
        .contact-info ul li {
            margin-bottom: 10px;
        }
        .skills ul {
            list-style: none;
            padding: 0;
        }
        .skills ul li {
            display: inline-block;
            margin-right: 10px;
            background-color: #333;
            color: #fff;
            padding: 5px 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile">
            <img src="C:\Users\ameri\Downloads\WhatsApp Image 2024-10-06 at 1.22.57 PM.jpeg" alt="Foto de perfil">
            <div>
                <h1>America Vallejo</h1>
                <p>Estudiante de Ing. en Tecnologías de la Información y Comunicación</p>
            </div>
        </div>
        <hr>

        <!-- Información de contacto -->
        <div class="contact-info">
            <h2>Información de contacto</h2>
            <ul>
                <li>Email: vallejoamerica17@gmail.com</li>
                <li>Teléfono: (52)899-108-4364</li>
                <li>Ubicación:  Calle Santa Teresa #102, Hacienda Bugambilias, Reynosa</li>
               
            </ul>
        </div>

        <!-- Educación -->
        <div class="education">
            <h2>Educación</h2>
            <p><strong>Kínder</strong> - Jardín de Niños Arturo Lerma Anaya (2012 - 2013)</p>
            <p><strong>Primaria</strong> - Casa Hogar M.A.M.I. (2013 - 2019)</p>
            <p><strong>Secundaria</strong> - Escuela Secundaria General #3 Prof. Rafael Balandrano Balandrano (2019 - 2022)</p>
            <p><strong>Preparatoria</strong> - Universidad Tamaulipeca (2022 - 2024) Bachillerato Tecnológico en Programación</p>
        </div>

        <!-- Habilidades -->
        <div class="skills">
            <h2>Habilidades</h2>
            <ul>
                <li>Creativa</li>
                <li>Buena Ortografía</li>
                <li>JavaScript</li>
                <li>React</li>
            </ul>
        </div>
    </div>
</body>
</html>
