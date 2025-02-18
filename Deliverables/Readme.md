## Ονοματεπώνυμο: Αλεξάνδρα Αργυρού
## ΑΜ: ΤΧ2018027
## My Character: Ο Σοφός

## Παραδοτέο 1

*Εφαρμογή Navigation για το Campus του Ψυχιατρείου*

Η εφαρμογή καλείται να επιλύσει προβλήματα που αντιμετωπίζουν οι φοιτητές του Τ.Ηχ.Ει., κυρίως πρωτοετείς, στην πλοήγησή τους στον χώρο του Ψυχιατρείου και τα κτήρια αυτού.

Τα προβλήματα στα οποία εστιάζει η εφαρμογή είναι ο εντοπισμός κτιρίων/αιθουσών και η πλοήγηση προς αυτά, ο καλύτερος συντονισμός αυτών με το ωρολόγιο πρόγραμμα (κυρίως ως προς τις ονομασίες), καθώς και γενικές πληροφορίες για τον χώρο.

Ο χώρος στο Campus του Ψυχιατρείου που αφορά φοιτητές του Τ.Ηχ.Ει. και με τον οποίο θα ασχοληθούμε είναι ο παρακάτω:

![map2](https://user-images.githubusercontent.com/93123676/228939696-d1282502-cbcf-4fcb-a92b-9a6459dbf4f7.jpg)

(Είσοδος και Αίθριο Ψυχιατρείου, Κτήριο Γκούσης (Τμήμα Τ.Η.Ε.), Κτήριο Αρεταίος (Τμήμα Πληροφορικής), Κτήριο Χαλεπάς (Εργαστήρια), Φοιτητική Λέσχη.)

*Σχεδίαση εφαρμογης:*

Η εφαρμογή λειτουργεί με την χρήση 4 markers, 1 στην είσοδο του Ψυχιατρείου και 1 σε κάθε είσοδο των 3 κτιρίων που μας αφορούν.

![map3](https://user-images.githubusercontent.com/93123676/228956648-8fb6b4ff-6752-4a19-bf3c-108e75df4461.jpg)

Το κάθε marker έχει πάνω embedded ένα QR code το οποίο οδηγεί στην σελίδα του AR Scanner, με το οποίο ο χρήστης σκανάρει τα markers. Κάθε marker εμφανίζει ένα menu ή slideshow επιλογών, το οποίο έχει navigation με buttons.

Στο πρώτο marker, στην είσοδο του Ψυχιατρείου, ο χρήστης οδηγείται στην αρχική σελίδα της εφαρμογής και επιλέγει σε ποιό από τα 3 κτήρια θέλει να πάει, ή στην φοιτητική λέσχη. Έπειτα, σε κάθε κτίριο το marker που του αντιστοιχεί εμφανίζει τις αίθουσες που χρησιμοποιούνται για μαθήματα του Τ.Ηχ.Ει.. Από αυτές ο χρήστης επιλέγει σε ποιά θέλει να πάει και λαμβάνει οδηγίες πλοήγησης προς αυτήν μέσω slideshow οδηγιτικών εικόνων.

*Στόχοι εφαρμογής*

Οι στόχοι που επιδιώκονται από την εφαρμογή είναι

1. Καλύτερη κατανόηση, περιήγηση και εξοικείωση με το Campus
2. Ευχρηστία, απλή και κατανοητή σχεδίαση
3. Λειτουργικότητα
4. Προσβασιμότητα με βοηθητικές τεχνολογίες

## Παραδοτέο 2

*Εγχειρίδιο χρήσης*

Η εφαρμογή μας δημιουργήθηκε για να διευκολύνει επισκέπτες/χρήστες του Campus να πλοηγηθούν και να εξοικειωθούν με αυτό και τους χώρους του. 
Τα βήματα που πρέπει να ακολουθήσουν οι χρήστες είναι τα εξής:

1. Ο χρήστης σκανάρει το QR code που βρίσκεται μαζί με τα markers στην κεντρική είσοδο του campus. Αυτό τον οδηγεί στην αρχική σελίδα της εφαρμογής, μέσω της οποίας θα μπορέσει να σκανάρει τα markers.
2. Στην είσοδο υπάρχουν 5 διαφορετικά markers που αντιστοιχούν σε 5 διαφορετικούς χώρους του campus. Ο χρήστης σκανάρει το marker του χώρου στον οποίο επιθυμεί να πλοηγηθεί. 
    - Marker #1: Κτήριο Γαληνός - Τμήμα Ξένων γλωσσών, Μετάφρασης και Διερμηνείας
    - Marker #2: Εργαστήρια / Τμήμα Πληροφορικής - Γραμματεία
    - Marker #3: Κτήριο Αρεταίος- Τμήμα Πληροφορικής
    - Marker #4: Κτήριο Γκούσης - Τεχνών Ήχου και Εικόνας - Γραμματεία
    - Marker #5: Φοιτητική Λέσχη Ιονίου Πανεπιστημίου
3. Με το σκανάρισμα του marker η εφαρμογή θα εμφανίσει ένα slideshow, το οποίο μέσα από καθοδηγητικές εικόνες υποδεικνύει στον χρήστη πώς να πλοηγηθεί στον χώρο που επέλεξε.
4. Όταν ο χρήστης φτάσει στον προορισμό του, στην είσοδο κάθε ενός από τους 5 χώρους υπάρχει άλλο ένα marker με embedded το QR code της αρχικής σελίδας της εφαρμογής σε περίπτωση που το χρειαστεί ξανά ο χρήστης. Τα markers αυτά εμφανίζουν περεταίρω πληροφορίες για τα κτήρια, όπως το πού βρίσκεται η κάθε αίθουσα και ποιά μαθήματα γίνονται σε αυτήν.


## Παραδοτέο 3
*Coding schema*
![image](https://github.com/t18argy/Sxediasmos-Perivallontwn-Diepafhs/assets/93123676/8ce10a81-a0da-47b7-b11f-fbb72f9743fa)

*Συμπεράσματα*

Συγκρίνοντας τους αρχικούς στόχους με τα αποτελέσματα της έρευνας:

1. Καλύτερη κατανόηση, περιήγηση και εξοικείωση με το Campus

    - Οι χρήστες κατάφεραν στο τέλος να εκπληρώσουν τον σκοπό τους, να φτάσουν δηλαδή στον προορισμό τους, αλλά με αξιοσημείωτη δυσκολία. Συνεπώς, δεν εξοικειώθηκαν και κατανόησαν καλύτερα το Campus.

2. Ευχρηστία, απλή και κατανοητή σχεδίαση

    - H εφαρμογή θεωρήθηκε επι το πλείστον δύσχρηστη με ανάγκη για περαιτέρω επεξηγήσεις για την χρήση της.
    - Η σχεδίαση του περιβάλλοντος διεπαφής μπέρδεψε τους χρήστες. Θα προτιμούσαν τα κουμπιά να εμφανίζονται μόνο όταν μπορούν να χρησιμοποιηθούν και να είναι πιο ξεκάθαρα.
    - Τα μάρκερς δεν σκανάρονταν εύκολα και μπερδεύονταν μεταξύ τους, λόγω μεγέθους και διάταξης αλλά και αδυναμίας της τεχνολογίας AR. Η χρήση του AR στην εφαρμογή θεωρήθηκε γενικά μη απαραίτητη.
    - Οι χρήστες βρήκαν τα γραφικά αρκετά ικανοποιητικά, αλλά σε ορισμένες περιπτώσεις παραπλανητικά αφου παρέπεμπαν σε κουμπιά.
   
3. Λειτουργικότητα

    - Η εφαρμογή αργεί να φορτώσει, ειδικά την πρώτη φορά, το οποίο μπορεί να φέρει επιπλοκές.
    - Η εικόνες θα έπρεπε να μένουν και να λειτουργεί το slideshow και ας απομακρυνθούμε από το marker.
   
4. Προσβασιμότητα με βοηθητικές τεχνολογίες

    - Η απαραίτητη δουλειά για το κριτήριο δεν έγινε και μεταφέρεται σε μελλοντικούς στόχους.

Λοιπά Συμπεράσματα

    - Παρά την τελική επίτευξη του στόχου τους, οι χρήστες δεν φαίνεται να προτιμούσαν την εφαρμογή αυτή σε σχέση με άλλες μεθόδους, βαθμολογόντας την μέτρια με μέσο όρο 4.3/10.

