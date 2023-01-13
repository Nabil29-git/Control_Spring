# Activite-Pratique-du-Controle
<h1><i>1-Objectif :</i><h1>
<h3>Créer une application basée sur une architecture micro-service qui permet de gérer les factures contenant des produits et appartenant à un client.</h3>
<ol>
  <li>Micro-service customer-service qui permet de gérer les client</li>
  <li>Micro-service inventory-service qui permet de gérer les produits</li>
  <li>Gateway Spring cloud Gateway avec une Configuration statique du système de routage</li>
  <li>Annuaire Eureka Discrovery Service</li>
  <li>Configuration dynamique des routes de la gateway</li>
  <li>Service de facturation Billing-Service en utilisant Open Feign</li>
  <li>Client Web Angular (Clients, Produits, Factures)</li>
  <li>Déployer le serveur keycloak :</li>
  <dl>
  <dt>- Créer un Realm</dt>
  <dt>- Créer un client à sécuriser</dt>
  <dt>- Créer des utilisateurs</dt>
  <dt>- Créer des rôles</dt>
  <dt>- Affecter les rôles aux utilisateurs</dt>
  <dt>- Tester les différents modes d'authentification avec Postman en montrant les contenus de Access-Token, Refresh Token</dt>
  </dl>
  <li>Sécuriser les micro-services et le frontend angular en déployant les adaptateurs Keycloak</li>
</ol>
<h1><i>2-Architecture de l'activité pratique :</i><h1>
<img src="https://user-images.githubusercontent.com/48455549/206859150-63e5c806-86a2-4937-8791-9a7ce2464316.PNG">
<h1><i>3-Simulation :</i><h1>
 <img src="https://user-images.githubusercontent.com/81412369/209435781-072641e5-b151-4b40-ac3e-44db3b5c30f2.png">
 <img src="https://user-images.githubusercontent.com/81412369/209435997-400c182b-f917-4570-a057-90279f130ae7.png"/>
 <img src="hhttps://user-images.githubusercontent.com/81412369/209435859-97e2010c-6181-4af0-9b46-7bb04b254d9c.png"/>
 <img src="https://user-images.githubusercontent.com/81412369/209436063-5d55521a-35f3-4152-a94d-7619e7d29e95.png"/>

  <ul>Eureka Service</ul>
  <img src="https://user-images.githubusercontent.com/74361043/207845098-8d43032c-d999-4269-87d7-21550dcf2a16.png">
<h1><i>4-Partie Front Angular :</i><h1>
<ul>Liste des produits</ul>
<img src="https://user-images.githubusercontent.com/81412369/212188904-9f7f1c4b-834f-4ef9-9d17-324a321b786d.PNG">
<ul>Liste des clients</ul>
<img src="https://user-images.githubusercontent.com/81412369/212298055-3d017af6-ec25-4479-aa38-f34d80925a7c.PNG">
<ul>Liste des factures d'un client</ul>
<img src="https://user-images.githubusercontent.com/81412369/212298140-e48123ea-85a4-4435-8dbc-c2dc13373c72.PNG">
<h1><i>5-Keycloak :</i><h1>
<img src="https://user-images.githubusercontent.com/81412369/212369443-e0d2d674-4814-425e-99a8-be69adeeec7f.PNG">
<ul>authentication with client secret</ul>
<img src="https://user-images.githubusercontent.com/74361043/207850425-4f730ad4-d065-4270-ad92-22fb7fa6f5cb.png">
<ul>authentication with password</ul>
<img src="https://user-images.githubusercontent.com/81412369/212190954-c6135565-04eb-43d6-aa07-9cca2032b032.PNG">
<ul>authentication with refresh token</ul>
<img src="https://user-images.githubusercontent.com/74361043/207848772-e6a144d0-7c3d-48db-a96a-9769d601ed89.png">

