# Python-Neural-Style-Transfer
O scurtă prezentare care demonstrează cum se efectuează transferul stilului neuronal cu un model pre-antrenat.


Neural-Style-Transfe este o tehnică de optimizare folosită pentru a lua două imagini — o imagine de conținut și o imagine de referință de stil 
  (cum ar fi o lucrare de artă a unui pictor celebru) — și pentru a le amesteca împreună, astfel încât imaginea de ieșire să arate ca imaginea de conținut, dar „pictată” 
  în stilul imaginii de referință de stil.
  
Acest lucru este implementat prin optimizarea imaginii de output pentru a se potrivi cu statisticile de conținut ale imaginii de conținut și statisticile de stil ale imaginii 
  de referință de stil. Aceste statistici sunt extrase din imagini folosind o rețea convoluțională.

De exemplu, să luăm o imagine a acestui câine și a compoziției 7 a lui Wassily Kandinsky:
![image](https://user-images.githubusercontent.com/60985084/163541000-1cc3b8fc-9cda-4bcb-ab58-fb27a357c9bc.png)
...
![image](https://user-images.githubusercontent.com/60985084/163541064-3b6ead05-0c5a-4896-b74f-951b06e2d03b.png)
Rezultat:

![image](https://user-images.githubusercontent.com/60985084/163541096-85960467-b129-4142-85f2-d9b58f178862.png)
