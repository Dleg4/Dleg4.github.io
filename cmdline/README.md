byte0: Εκτελώ ls και έπειτα κάνω cd στο αρχείο που υπάρχει (i_wanna_be). Επαναλαμβάνω την διαδικασία ή κάνω cd και πατάω το tab μέχρι να βρω το αρχείο treasure. Εκτελώ cat treasure και βρίσκω τον μυστικό κωδικό.

byte1: Εκτελώ man supercalifragilisticexpialidocious για να μάθω τι κάνει αυτή η εντολή και βρίσκω το keyphrase.`

byte2: Eκτελώ grep "will find" shakespeare.txt και παρατηρώ τη φράση No one will find this: grep_is_your_friend.

byte3: Εκτελώ diff shakespeare.modified.txt shakespeare.txt και έτσι την πρόταση στην οποία έγινε η αλλαγή λέξης (programmers-players).

byte4: Εκτελώ find /home/byte4 -name *.txt και έπειτα μπορώ να παρατηρήσω σε ποιο filepath βρίσκεται το αρχείο cup.txt. Εναλλακτικά μπορώ να εκτελέσω find /home/byte4 -name *.txt | grep -v box.txt και θα έχω ολα τα αρχεία εκτός από τα box.txt δηλαδή μόνο το αρχείο cup.txt. Σε κάθε περίπτωση κάνω cd  το filepath  του αρχείου cup.txt και τέλος εκτελώ  cat cup.txt για να βρω το keyphrase.

byte5: 1.)Εκτελώ cd /tmp
       2.)Δημιουργώ έναν καινούριο φάκελο με την εντολή mkdir. Π.χ. mkdir newfile
       3.)Αντιγράφω τον πρόγραμμα byte5.c στον καινούριο φάκελο. cp byte5.c newfile
       4.)Εκτελώ cd newfile
       5.)Εκτελώ gcc -o byte5 byte5.c 
       6.)Εκτελώ ./byte5 sdi2400106 πατάω enter κα έχω το keyphrase.
