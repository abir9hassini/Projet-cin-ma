<b>Objectif de ce Tp : </b> 

Le but de ce tp est de la conception et la création d’une application web qui permet de gérer des cinémas.<br>
•	Chaque cinéma se trouvant dans une ville est défini par son code, son nom et sa position géographique. <br>
•	Le cinéma contient un ensemble de salles.<br>
•	Chaque salle qui est définie par son numéro, son nom contient un ensemble de places.<br>
•	 Chaque place a un numéro et positionnée géographiquement.<br>
•	Quotidiennement, on programme plusieurs projections de films dans des salles.<br>
•	Chaque Projection se déroule dans une séance, concerne un Film et se déroule dans une Salle à un date de projection et un prix fixe.<br>
•	Chaque séance est définie par son numéro et l’heure de début e la séance.<br>
•	Chaque projection on prévoie un ensemble de Tickets.<br>
•	Chaque Ticket concerne une Place et défini par le nom du client, le prix du ticket et le code payement.<br>
•	Les films sont classés par catégories<br>

<b>L’architecture de l’application :</b> 

L’application se compose de 2 Parties : La partie backend et la partie Frontend.<br>

La partie backend est basée sur Spring Boot et se compose des couches DAO, Service (Métier) et Web.<br>
• La couche DAO est basée sur Spring Data, JPA, Hibernate<br>
• La couche Métier est définie par une interface et une implémentation quelques spécifications fonctionnelles qui nécessite des calculs ou des traitements particuliers <br>
• La couche Web est basée sur des API Restful basée sur Spring Data Rest ou des RestController<br>

La partie Frontend est basée sur le Framework Angular.<br>
La sécurité est basée sur Spring Security et Json Web Token
