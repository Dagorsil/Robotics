STO USANDO QUESTA CARTELLA COME PACKAGE PRINCIPALE


IDEA SULLA STRUTTURA GENERALE:
il pub legge i valori dal bag e li pubblica. il sub riceve ivalorie li converte in enu, dopo di che da da client per un server (manda al serveri valori convertiti), eun ultimo nodo (il server) calcolerà la distanza e restituirà il risultato al client-sub che si occuperà di convertirli in "custom message" e pubblicarli.


//PUB
controllare rate (10)



//MSG
NEL MSG IL FLAG LO VUOLE INTERO O UNA STRINGA?(TPO "CRASH");
Ho il dubbio se nel cMke file, va inserito custom_message_generate_messages_cpp OPPURE lla2enu_generate_messages_cpp
