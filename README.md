<center><h1>🌐 E-Commerce</h1></center> <p>This project is an online store application for Tech products (mice, mousepads, computer components, monitors, etc.).</p> <p><b>Back-end:</b> C# .NET, MySQL, Entity Framework Core</p> <p><b>Front-end:</b> Vue.js, Nuxt.js</p> <p><b>API Documentation:</b> Swagger</p> <h2>Team</h2> <ul> <li><a href="https://github.com/tom-marchandise" target="_blank">Tom Marchandise</a> (Project Manager / Scrum Master) - Overall project coordination and Agile methodology (Scrum) management.</li> <li><a href="https://github.com/DdorAa12" target="_blank">Dora Kerarsi</a> (Full Stack Developer) - Back-end development management (+) database optimization.</li> <li><a href="https://github.com/ewaewa23" target="_blank">Mateo Gibert</a> (Full Stack Developer) - Project initialization, back-end setup, and front-end foundations with Vue.js.</li> <li><a href="https://github.com/antonyEpitec" target="_blank">Antony Rinaldo</a> (Full Stack Developer)</li> <li><a href="https://github.com/HugoNannucci" target="_blank">Hugo Nannucci</a> (Full Stack Developer) - Front-end development, integration of Vue.js and Nuxt.js for data and view rendering.</li> <li><a href="https://github.com/antonyEpitec" target="_blank">Thyssem Makhlouf</a> (Full Stack Developer) - Design of all application interfaces and creation of back-end services.</li> </ul> <h2>📂 Architecture</h2> <p align="left"> MVC architecture, with controllers handling HTTP requests on the server side, a view containing the application's front-end, Models, and DTOs (Data Transfer Objects). </p> <p align="left"> DTOs are used to transfer data between different layers of the application. They simplify the structure of data sent and received by the API. Here’s why DTOs are essential: <ul> <li><b>Separation of concerns:</b> DTOs allow the separation of application logic from data structure. For example, data sent from the database can be transformed into DTOs tailored for the user interface.</li> <li><b>Performance:</b> Using DTOs, we can precisely control which data is sent to the user, reducing unnecessary data overload.</li> <li><b>Security:</b> DTOs allow us to hide sensitive or unnecessary data that should not be exposed to the user.</li> <li><b>Ease of maintenance:</b> If changes occur in data structure or APIs, DTOs allow for maintaining some independence between the front-end and back-end.</li> </ul> </p> <h2>🚀 Installation</h2> <h3>🔒 Prerequisites</h3> <p>Before starting, make sure you have the following prerequisites installed:</p> <ul> <li><b>Dotnet SDK 6.0 or higher</b> - To run the back-end application in C#.</li> <li><b>Node.js and npm</b> - To manage dependencies and run the front-end application with Vue.js and Nuxt.js.</li> <li><b>MySQL</b> - Used to manage the application's data.</li> <li><b>Redis</b> - For OTP and other temporary data management.</li> </ul> <h3>🔧 Database Configuration</h3> <p>To configure the database, follow these steps:</p> <ol> <li>Install the necessary packages for Entity Framework Core and MySQL database management: <ul> <li><code>dotnet add package Microsoft.EntityFrameworkCore --version 6.0.16</code></li> <li><code>dotnet add package Pomelo.EntityFrameworkCore.MySql --version 6.0.3</code></li> </ul> </li> <li>Run the migrations to initialize the database with the following command: <code>dotnet ef database update</code> </li> <li>Configure your database settings in the <code>appsettings.json</code> file under the <code>ConnectionStrings</code> section.</li> </ol> <h3>🔧 Running the Project</h3> <p>To run the project, follow these steps:</p> <ol> <li><b>Backend (C# .NET)</b>: From the project root, run the following command to start the back-end server: <pre><code>dotnet run</code></pre> </li> <li><b>Frontend (Vue.js)</b>: Go to the <code>ClientApp</code> folder and install the front-end dependencies with npm: <pre><code>npm install</code></pre> Then run the Vue.js application with: <pre><code>npm run dev</code></pre> </li> </ol> <h2>🛠 Features</h2> <ul> <li>Authentication system with JWT, OTP, Google.</li> <li>Cart management: <ul> <li>Cart cleaning on logout</li> <li>Indicator for number of items in the cart</li> <li>"Empty Cart" button</li> <li>Redirects from the cart and sidebar</li> </ul> </li> <li>Order management: <ul> <li>Order details (total price, VAT, shipping/billing addresses)</li> <li>Order tracking with statuses (In progress, Shipped, Delivered, Return)</li> </ul> </li> <li>Redis integration for OTP management</li> <li>Email notifications for stock updates and password reset</li> </ul> <h2>⚙️ Database Configuration</h2> <p>Database configuration is done via <code>appsettings.json</code>. MySQL connection information must be specified, and the database context should be configured with Entity Framework Core.</p> <p>Migrations should be applied using the <code>dotnet ef database update</code> command to ensure the database is up-to-date with the latest model changes.</p> <h2>⚙️ Ports Used</h2> <ul> <li>Port 3000</li> </ul> <h2>📧 Sending Emails</h2> <p>The project uses <b>MailKit</b> for sending email notifications. You can configure an SMTP server to send emails (for example, for password reset or product availability notifications).</p> <p>Make sure to configure your SMTP server and MySQL logs properly in the <code>appsettings.json</code> file under the <code>SmtpSettings</code> section.</p>

<br>
<br>
<br>
-------

<center><h1>🌐 E-Commerce</h1></center>

<p>Ce projet est une application de vente en ligne de produits Tech (souris, tapis de souris, composants informatiques, écrans, etc.).</p>

<p><b>Back-end :</b> C# .NET, MySQL, Entity Framework Core</p>
<p><b>Front-end :</b> Vue.js, Nuxt.js</p>
<p><b>Documentation API :</b> Swagger</p>

<h2>Groupe</h2>
<ul>
    <li><a href="https://github.com/tom-marchandise" target="_blank">Tom Marchandise</a> (Chef de projet / Scrum Master) - Coordination générale du projet et gestion de la méthodologie Agile (Scrum).</li>
    <li><a href="https://github.com/DdorAa12" target="_blank">Dora Kerarsi</a> (Développeuse Full Stack) - Gestion du développement côté back-end (+) optimisation de la base de données </li>
    <li><a href="https://github.com/ewaewa23" target="_blank">Mateo Gibert</a> (Développeur Full Stack) - Initialisation du projet, mise en place du back-end et des fondations front-end avec Vue.js.</li>
    <li><a href="https://github.com/antonyEpitec" target="_blank">Antony Rinaldo</a> (Développeur Full Stack)</li>
    <li><a href="https://github.com/HugoNannucci" target="_blank">Hugo Nannucci</a> (Développeur Full Stack) - Développement de la partie front-end, intégration de Vue.js et Nuxt.js pour l'affichage des données et des vues.</li>
    <li><a href="https://github.com/antonyEpitec" target="_blank">Thyssem Makhlouf</a> (Développeuse Full Stack) - Design de toutes les interfaces de l'application et création de services back-end</li>
</ul>

<h2>📂 Architecture</h2>
<p align="left">
    Architecture MVC, avec des controllers gérant les requêtes HTTP côté serveur, une vue qui contient le front de l'application, des Models, des DTOs (Data Transfer Objects).
</p>
<p align="left">
    Les DTOs sont utilisés pour transférer des données entre les différentes couches de l'application. Ils permettent de simplifier la structure des données envoyées et reçues par l'API. Voici pourquoi les DTOs sont essentiels :
    <ul>
        <li><b>Séparation des préoccupations :</b> Les DTOs permettent de séparer la logique de l'application de la structure des données. Par exemple, les données envoyées depuis la base de données peuvent être transformées en DTOs adaptés à l'interface utilisateur.</li>
        <li><b>Performance :</b> En utilisant des DTOs, nous pouvons contrôler exactement quelles données sont envoyées à l'utilisateur, réduisant ainsi la surcharge de données inutiles.</li>
        <li><b>Sécurité :</b> Les DTOs nous permettent de masquer certaines données sensibles ou inutiles qui ne doivent pas être exposées à l'utilisateur.</li>
        <li><b>Facilité de maintenance :</b> En cas de modifications dans la structure des données ou des API, les DTOs permettent de maintenir une certaine indépendance entre le front-end et le back-end.</li>
    </ul>
</p>

<h2>🚀 Installation</h2>

<h3>🔒 Pré-requis</h3>
<p>Avant de démarrer, assurez-vous d'avoir installé les pré-requis suivants :</p>
<ul>
    <li><b>Dotnet SDK 6.0 ou supérieur</b> - Pour exécuter l'application back-end en C#.</li>
    <li><b>Node.js et npm</b> - Pour gérer les dépendances et exécuter l'application front-end avec Vue.js et Nuxt.js.</li>
    <li><b>MySQL</b> - Utilisé pour la gestion des données de l'application.</li>
    <li><b>Redis</b> - Pour la gestion des OTP et d'autres données temporaires.</li>
</ul>

<h3>🔧 Configuration de la base de données</h3>
<p>Pour configurer la base de données, suivez les étapes suivantes :</p>
<ol>
    <li>Ajoutez les packages nécessaires pour l'Entity Framework Core et la gestion de la base de données MySQL :
        <ul>
            <li><code>dotnet add package Microsoft.EntityFrameworkCore --version 6.0.16</code></li>
            <li><code>dotnet add package Pomelo.EntityFrameworkCore.MySql --version 6.0.3</code></li>
        </ul>
    </li>
    <li>Effectuez les migrations pour initialiser la base de données avec la commande suivante :
        <code>dotnet ef database update</code>
    </li>
    <li>Ajoutez la configuration de votre base de données dans le fichier <code>appsettings.json</code>, sous la section <code>ConnectionStrings</code>.</li>
</ol>

<h3>🔧 Lancement du projet</h3>
<p>Pour lancer le projet, suivez ces étapes :</p>
<ol>
    <li><b>Backend (C# .NET)</b> : Depuis la racine du projet, exécutez la commande suivante pour démarrer le serveur back-end :
        <pre><code>dotnet run</code></pre>
    </li>
    <li><b>Frontend (Vue.js)</b> : Allez dans le dossier <code>ClientApp</code> et installez les dépendances front-end avec npm :
        <pre><code>npm install</code></pre>
        Puis lancez l'application Vue.js avec :
        <pre><code>npm run dev</code></pre>
    </li>
</ol>

<h2>🛠 Fonctionnalités</h2>
<ul>
    <li>Système d’authentification avec JWT, OTP, Google.</li>
    <li>Gestion du panier :
        <ul>
            <li>Nettoyage du panier à la déconnexion</li>
            <li>Indicateur de nombre d’articles dans le panier</li>
            <li>Bouton "Vider le panier"</li>
            <li>Redirections depuis le panier et la sidebar</li>
        </ul>
    </li>
    <li>Gestion des commandes :
        <ul>
            <li>Détails de la commande (prix total, TVA, adresses de livraison/facturation)</li>
            <li>Suivi des commandes avec statuts (En cours, Expédié, Livré, Retour)</li>
        </ul>
    </li>
    <li>Intégration Redis pour la gestion des OTP</li>
    <li>Envoi de mails pour les notifications de stock et les réinitialisations de mot de passe</li>
</ul>

<h2>⚙️ Configuration de la base de données</h2>
<p>La configuration de la base de données se fait via <code>appsettings.json</code>. Il est nécessaire de spécifier les informations de connexion MySQL et de configurer le contexte de la base de données avec Entity Framework Core.</p>
<p>Les migrations doivent être appliquées à l'aide de la commande <code>dotnet ef database update</code> pour assurer que la base de données est à jour avec les dernières modifications de modèle.</p>

<h2>⚙️ Ports Utilisés</h2>
<ul>
    <li>Port 3000</li>
</ul>

<h2>📧 Envoi de mails</h2>
<p>Le projet utilise <b>MailKit</b> pour l'envoi de mails de notifications. Vous pouvez configurer un serveur SMTP pour envoyer des mails (par exemple, pour l'envoi de notifications de réinitialisation de mot de passe ou de disponibilité de produit en stock).</p>
<p>Assurez-vous de configurer correctement votre serveur SMTP, vos logs mysql dans le fichier <code>appsettings.json</code> sous la section <code>SmtpSettings</code>.</p>
