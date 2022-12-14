# Βήμα 1: Εκπαίδευση του μοντέλου σας

Ένα μοντέλο custom vision 

## Δημιουργία του project

Ένα project είναι ένα μοντέλο custom vision. Χρησιμοποιείται για τον χαρακτηρισμό των εικόνων με την κατάλληλη ετικέτα (ή κατηγορία) και για την διεξαγωγή της εκπαίδευσης. Ας ξεκινήσουμε με τη δημιουργία του project. 

1. Επισκεφθείτε το [Custom Vision](https://www.customvision.ai?WT.mc_id=academic-49102-chrhar) και συνδεθείτε
1. Επιλέξτε **New Project**
1. Βάλτε σαν όνομα πρότζεκτ **Dog Classification**
1. Δίπλα στο Resource, επιλέξτε το κλειδί που δημιουργήσατε νωρίτερα, το οποίο θα έχει το όνομα που χρησιμοποιήσατε κατά την [εγκατάσταση](setup.el.md).
1. Στο **Project Types** επιέξτε **Classification**
1. Στο **Classification Types** επιλέξτε **Multiclass**, καθώς οι σκύλοι που θα χρησιμοποιήσουμε θα έχουν μόνο μία ράτσα
1. Στο **Domains** επιλέξτε **General \[A2\]**
1. Επιλέξτε **Create project**

## Ανέβασμα των εικόνων

Μετά την δημιουργία του project, ήρθε η ώρα να ανεβάσετε τις εικόνες. Αυτές οι εικόνες θα χρησιμοποιηθούν για την εκπαίδευση του μοντέλου.

> **Συμβουλή**: Σαν γενικός κανόνας, όσο περισσότερες εικόνες χρησιμοποιήσετε για την εκπαίδευση του μοντέλου τόσο καλύτερα. Ιδανικά, προτιμήστε να συμπεριλάβετε όσο γίνεται μεγαλύτερη ποκιλία στις εικόνες, συμπεριλαμβανομένων διαφορετικού φωτισμού, γωνιών και ρυθμίσεων.

1. Επιλέξτε **Add images**
1. Πηγαίντε το **training-images**
1. Επιλέξτε όλες τις εικόνες της ράτσας **american-staffordshire-terrier** στον φάκελο, και επιλέξτε **Open**
1. Εισάγετε **american-staffordshire-terrier** σαν tag (ετικέτα) και επιλέξτε **Upload 8 files**
1. Επιλέξτε **Done**
1. Επαναλάβετε τα παραπάνω βήματα και για τις υπόλοιπες ράτσες:
    - **australian-shepherd**
    - **buggle**
    - **german-wirehaired-pointer**
    - **shorkie**
1. Επιλέξτε **Train** για να εμφανίσετε το παράθυρο εκπαίδευσης
1. Αφήστε επιλεγμένο το **Quick Training** και επιλέξτε **Train** για να εκκινήσετε την εκπαίδευση.

> **Σημείωση**: Η εκπαίδευση του μοντέλου μπορεί να διαρκέσει μερικά λεπτά 

## Σύνοψη

Συγχαρητήρια! Έχετε εκπαιδεύσει ένα μοντέλο Custom Vision το οποίο μπορεί να αναγνωρίζει ράτσες σκύλων. Στην συνέχεια [θα ελέγξετε και θα χρησιμοποιήσετε το μοντέλο](predict.el.md).
