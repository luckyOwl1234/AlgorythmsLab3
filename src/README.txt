Grupp 45
Johan Martinson
Joakim Willard

toString, man ittererar på listan och hämtar elementet på varje nod som läggs på en tom sträng allt efetersom.

contain, ittererar genom listan och kollar om varje nod och jämnför det med tecknet man skickat med till metoden.
         Om nodens element är den samma som tecknet så returneras true.

copyUppercase,  skapar ett nytt listhuvud och två pekare, en för varje lista. Man ittererar genom den ursprungliga listan
                med den ena pekaren och där man hittar versaler så med hjälp av den andra pekaren så lägger man till en ny
                nod i den nya listan och kopierar över det nya elementet. Listhuvud för den nya listan returneras.

addFirst,   Skapar en ny nod som länkas till den nuvarande första noden i listan. Sedan så länkas sidhuvudet om till den nya noden.

getLastNode,    Ittererar över listan tills den hittar att nästa nod är lika med null. Då returnerar den noden som pekaren pekar på.

addLast,    Skapar en ny nod som länkas till den nuvarande sista noden i listan. Sedan så länkas den sista noden om med
            hjälp av getLastNode till den nya noden.

concat,     Hittar sista noden i lista 1 m.h.a. getLastNode. Sen länkar man på första noden i lista 2 till sista noden i lista 1.
            Sist nulltermineras listhuvudet för att tömma listan.

addAll,     Här kopieras varje nod från lista 2 till lista 1. Man itterar över lista 2 och lägger till kopior av dess noder i lista 1 efter sista noden,
            som fås av getLastNode.

reverse,    Här ittererar vi först igenom listan för att få antalet noder. Nollställer pekaren till listhead. Pekaren plockar sen den sista noden
            och lägger till den i en ny lista, counter minskas med 1 så att pekaren nästa gång hämtar det näst sista elementet som den lägger till
            i den nya listan osv. När counter = 0 så returneras den nya listan som nu är omvänd.