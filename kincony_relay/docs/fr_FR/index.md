Ce plugin permet le lien avec le controlleur Relay kincony.com.
Il s'agit d'un controller réseau cablé ou wifi avec des entrée digitales possibles.
Vous pouvez retrouver les différents modèles sur : https://www.kincony.com/product/relay-controller

On peut les trouver facilement sur aliexpress.

Configuration :

Choissisez une adresse ip fixe pour l'appareil ou configurez une réservation ip de sa mac adresse dans votre serveur DHCP.
Tout d'abord vous devez utiliser l'outils VirCom pour paramétrer l'appareil:
1. Choisissez l'adresse ip (fixe ou DHCP)
2. Indiquez le Work Mode : TCP Server
3. Choisissez un port (par exemple 4192)
4. Cliquez sur le bouton "Modify Settings"
5. Redémarrer l'appareil en coupant son alimentation

Vous pouvez vérifier que tout fonctionne correctement en utilisant le logiciel "KC868Hx-Debug-Client.exe".
Entrez l'adresse ip et le port et vérifier que relais et entrées fonctionnent correctement.

Maintenant, you pouvez aller dans le plugin et rajouter l'équipement.
Entrez l'adresse ip et le port ainsi que le nombre de relais et d'entrées. 
Cela créera automatiquement les commandes correspondantes.
