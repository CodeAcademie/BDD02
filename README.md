# Expression de besoin

On désire concevoir une base de données pour un centre de recherche. 
L’activité de ce centre est découpée en départements dans lesquels sont menés des projets de recherche. 

Pour chaque département, la base doit contenir son numéro (unique), un intitulé, un budget et le numéro de l’employé qui le dirige. Pour chaque projet, la base doit contenir son numéro (unique), un intitulé, un budget ainsi que l’information permettant de retrouver le département dans lequel il est mené. 

Les  locaux  du  centre  de recherche sont décrits par les bureaux occupés par les employés. Chaque bureau est décrit par un numéro (unique) et par sa surface. Les postes téléphoniques installés dans les bureaux sont également  décrits  par  un  numéro  d’appel  (unique).  L’information  permettant  de  retrouver  le  bureau  où  se trouve un poste téléphonique doit aussi être stockée. 

Les informations à stocker concernant les employés du centre sont les suivantes :

 * un numéro unique 
 * le nom de l’employé 
 * les titres des différentes études qu’il à menées depuis son arrivée au centre ainsi que l’historique (date) des différents salaires qu’il a perçus pour chaque étude qu’il a menée (plusieurs salaires sont possibles pour une même étude). Ces études sont sans rapport avec les projets menés dans ce centre. 
 * les informations permettant de retrouver le projet, le département, le bureau et le téléphone de l’employé. 

On connaît les contraintes suivantes sur les données à stocker dans la base de données : 

 * un département a un directeur et un seul parmi les  employés 
 * un projet est mené dans un seul département 
 * un employé travaille sur un seul projet 
 * un employé se trouve dans le département de rattachement du projet sur lequel il travaille 
 * un employé ne peut mener qu’une seule étude et ne toucher qu’un seul salaire à une date donnée 
 * les études sont indépendantes des projets 
 * un employé ne possède qu’un seul bureau 
 * un employé dispose d’un seul poste téléphonique 
 * un employé se trouve dans le bureau de son poste téléphonique 
 * un poste téléphonique se situe dans un seul bureau
 * un bureau est affecté à au plus un département 