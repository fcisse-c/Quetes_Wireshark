# Quetes_Wireshark
1. les protocoles ont été utilisés dans la trace réseau capturée sont :
   Sur la colonne Protocol:
   - ARP 
   - ICMP

  2.  Les adresses IP et les adresses MAC des interfaces ayant échangé des informations sont :
     
   - les adresses IP:                                 45 00
     00 54 8e b7 00 00 40 01 d5 ed  0a 01 01 01 0a 01
     01 01

     45 00
     00 54 8e b7 00 00 40 01 d5 ed  0a 01 01 02 0a 01
     01 02
     
   - les adresses MAC:
     
      00 50 79 66 68 01 00 50 79 66 68 00 08 00
     
      00 50 79 66 68 00 00 50 79 66 68 01 08 00

     
     
  4. filtre d'affichage qui permet de ne plus afficher les paquets ARP  est :
     Filtres de capture (icmp)
     
  6. Les informations disponibles dans la colonne info de la liste des paquets pour la ligne 3 est :
     
     0.001031	10.1.1.1	10.1.1.2	3	ICMP	98	Echo (ping) request  id=0xb78e, seq=1/256, ttl=64 (reply in 4)
     
  8. Le paquet N°8 est-il une question ou une réponse ? et quel est le paquet correspondant (la question, si c'est une réponse ou la réponse, si c'est une question ?
     Le paquet N°8 est une réponse
2.003536	10.1.1.2	10.1.1.1	8	ICMP	98	Echo (ping) reply    id=0xb98e, seq=3/768, ttl=64 (request in 7)

