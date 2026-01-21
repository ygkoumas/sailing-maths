---
layout: post
title:  "Υπολογισμός απόστασης μετάκεντρου και κέντρου άνωσης σκάφους"
author: Γιάννης Γκούμας
--- 

> Με απλά λόγια:
> \\[BM = \frac{I_{wl}}{\nabla} \\]
> όπου:
> 
> \\(BM\\) η απόσταση μετάκεντρου και κέντρου άνωσης σκάφους
> 
> \\(I_{wl}\\) η ροπή αδράνειας επιφάνειας της τομής γάστρας και επιπέδου της θάλασσας
>
> \\( \nabla \\) ο όγκος του σκάφους που βρίσκεται μέσα στο νερό.

![sextant-angles]({{site.baseurl}}/images/bm-stability.png)


Χωρίς βλάβη της γενικότητας θα υποθέσουμε οτι το σκάφος δεν έχει μήκος και θα δουλέψουμε στην γεωμετρία των δύο διαστάσεων που βλέπουμε στο σχήμα.

Στο σχήμα βλέπουμε μια μικρή μεταβολή στο σκάφος κατά την γωνία \\(α\\). Η μπλε διακεκομένη γραμμή είναι η θάλασσα μετά την μεταβολή \\(α\\).

Η παρακάτω εξίσωση θα μπορούσε να είναι ο ορισμός του μετακέντρου:

\begin{equation}
BB' = α \cdot BM  \label{eq:clock}
\end{equation}


Με την μεταβόλη κατα \\(α\\) μοίρες το κέντρο άνωσης μετατοπίζεται. Μπορούμε να υπολογίσουμε την μετατόπηση ολοκληρόνοντας!!

  \\[BB' \approx \frac{\int_{O\overset{\triangle}{L}L'} r dA}{\nabla} + \frac{\int_{O\overset{\triangle}{R}R'}  r dA}{\nabla}\\]


  όπου \\(r\\) η απόσταση από το σημείο \\(O\\).
 
Συνεπώς:

\\[
  BB' \approx \frac{\int_0^{OL} α' \cdot r \cdot r dr}{\nabla} + \frac{\int_0^{OR} α'' \cdot r \cdot r dr}{\nabla}
\\]
Είναι εύκολο να αποδείξουμε πως \\(α = α' = α'' \\)

άρα:

 \\[ BB' \approx α \frac{\int_0^{OL} r^2 dr}{\nabla} + α \frac{\int_0^{OR}  r^2 dr}{\nabla} \\]
 ή
 \\[ BB' \approx α \frac{\int_0^{OL} r^2 dr + \int_0^{OR}  r^2 dr}{\nabla} \\]
 ή
\begin{equation}
  BB' \approx α \frac{I_{wl}}{\nabla}
  \label{eq:wl} 
\end{equation}

Συνδιάζοντας τις σχέσεις
\eqref{eq:clock}
\eqref{eq:wl}
καταλήγουμε στο υπέροχο συμπέρασμα.

\begin{equation}
BM \approx \frac{I_{wl}}{\nabla} 
\end{equation}


