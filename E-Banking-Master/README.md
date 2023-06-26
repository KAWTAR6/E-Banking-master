<html>
<h1 align="center">E-Banking Application</h1>
<br>
<p>Cette application web vous permet de gérer des comptes bancaires. Elle est développée à l'aide de Spring Boot pour le backend et Angular pour le frontend.</p>
<h2>Description</h2>
<p>L'Application Bancaire Numérique offre des fonctionnalités pour gérer différents types de comptes bancaires. Il existe deux types de comptes : Compte Courant et Compte Épargne. Chaque compte possède un identifiant unique et des attributs spécifiques en fonction de son type. Les Comptes Courants ont un attribut de découvert autorisé, tandis que les Comptes Épargne ont un taux d'intérêt associé.</p>
<p>En plus des détails du compte, chaque compte bancaire conserve une liste des opérations effectuées. Une opération comprend un identifiant, une date d'opération, un montant, une description et un type (débit, crédit ou transfert). L'historique du compte enregistre le solde du compte après chaque opération.</p>
<p>Les clients sont enregistrés dans le système et ont les attributs suivants : identifiant, nom et adresse e-mail. Les clients peuvent avoir plusieurs comptes bancaires associés à leur profil.</p>
<h2>Backend</h2>
<p>Le backend de l'Application Bancaire Numérique est construit avec Spring Boot. Il fournit des API RESTful pour effectuer différentes opérations sur les comptes bancaires et les clients. L'architecture du backend suit une approche en couches, composée des éléments suivants :</p>
<h3>Contrôleurs</h3>
<p>Les contrôleurs gèrent les requêtes entrantes et délèguent le traitement aux services appropriés. Ils sont responsables de la mise en correspondance des points d'accès de l'API et de la validation des paramètres de requête.</p>
<h3>Services</h3>
<p>Les services contiennent la logique métier de l'application. Ils gèrent les fonctionnalités principales, telles que la création de comptes bancaires, l'exécution des opérations, la récupération des détails du compte et la gestion des informations des clients.</p>
<h3>Repositories</h3>
<p>Les repositories interagissent avec la base de données pour effectuer des opérations CRUD (Create, Read, Update, Delete). Ils fournissent une couche d'abstraction entre l'application et le stockage des données sous-jacent.</p>
<h3>Entités</h3>
<p>Les entités représentent les objets métier de l'application. Elles sont mappées sur des tables de base de données et définissent la structure des données.</p>
<h3>Objets de Transfert de Données (DTO)</h3>
<p>Les DTO sont utilisés pour transférer des données entre le backend et le frontend. Ils encapsulent les informations nécessaires et fournissent une représentation structurée des données.</p>
<h2>Frontend</h2>
<p>Le frontend de l'Application Bancaire Numérique est développé en utilisant Angular. Il offre une interface conviviale pour interagir avec l'application.</p>
<p>L'architecture du frontend suit une approche basée sur les composants, composée des éléments suivants :</p>
<h3>Composants</h3>
<p>Les composants sont responsables du rendu de l'interface utilisateur et de la gestion des interactions utilisateur. Ils encapsulent des fonctionnalités spécifiques et peuvent être réutilisés sur différentes pages.</p>
<h3>Services</h3>
<p>Les services du frontend gèrent la communication avec les API du backend. Ils effectuent des requêtes HTTP pour récupérer les données et mettent à jour l'interface utilisateur en conséquence.</p>
<h3>Modèles</h3>
<p>Les modèles représentent les structures de données utilisées dans le frontend. Ils reflètent les DTO du backend et fournissent un format de données cohérent pour l'application.</p>
<h2>Premiers pas</h2>
<p>Pour exécuter l'Application Bancaire Numérique en local, suivez ces étapes :</p>
<ol>
  <li>Clonez le dépôt depuis [GitHub](https://github.com/El-loussiNawfal/E-Banking.git).</li>
  <li>Configurez le backend en mettant à jour les fichiers de configuration nécessaires, tels que les paramètres de la base de données et les points d'accès de l'API.</li>
  <li>Compilez et exécutez l'application backend à l'aide de votre IDE préféré ou en exécutant les commandes Maven appropriées.</li>
  <li>Configurez le frontend en mettant à jour les URL des points d'accès de l'API pour correspondre à votre configuration backend.</li>
  <li>Installez les dépendances requises pour le frontend en utilisant `npm install`.</li>
  <li>Compilez et exécutez l'application frontend en utilisant `ng serve`.</li>
  <li>Accédez à l'application dans votre navigateur à l'adresse `http://localhost:4200`.</li>
</ol>
<h2>Conclusion</h2>
<p>L'Application Bancaire Numérique offre une solution complète pour la gestion des comptes bancaires et l'exécution d'opérations bancaires. Avec son backend Spring Boot et son frontend Angular, elle propose une interface robuste et conviviale à la fois pour les clients et les administrateurs bancaires. L'application prend en charge diverses opérations telles que la création de profils clients, l'ouverture de différents types de comptes bancaires, l'exécution de transactions de débit et de crédit, le transfert de fonds entre les comptes et la consultation de l'historique des transactions.</p>
<p>En exploitant la puissance de Spring Boot et d'Angular, l'application garantit une évolutivité, une sécurité et une expérience utilisateur transparente. L'architecture modulaire permet une extension et une personnalisation faciles, la rendant adaptée à des améliorations futures et à l'intégration avec d'autres systèmes.</p>
<p>Pour commencer avec l'Application Bancaire Numérique, suivez les instructions fournies dans la section "Premiers pas" ci-dessus. N'hésitez pas à explorer les dépôts backend et frontend pour comprendre les détails de mise en œuvre et contribuer au projet.</p>
