[eTwinning & AGRUINO](https://twinspace.etwinning.net/104669)

Το Agruino είναι μια κινητή πλατφόρμα Arduino που θα κινείται στον υποδεδειγμένο χώρο και θα παίρνει μετρήσεις Θερμοκρασίας,Υγρασίας ατμόσφαιρας και Υγρασίας Εδάφους.

Οι μετρήσεις αυτές θα επεξεργάζονται απο τη φορητή πλατφόρμα και σε πρώτο στάδιο εφόσον κρίνεται απαραίτητο θα ενημερώνει για την αναγκαιότητα ενεργοποίησης του αυτόματου ποτίσματος εφόσον έχουμε ξηρασία ή την ενεργοποίηση της υδρονέφωσης εφόσον πρόκειται να επικρατήσουν συνθήκες δημιουργίας παγετού. 

Οι σπουδαστές που προέρχονται απο τα τμήματα Α1 και Α2 της ειδικότητας "Τεχνικός Λογισμικού Η/Υ" του Δ.ΙΕΚ Πατρών υπο την καθοδήγηση του Υποδιευθυντή κ.Γιωτόπουλου και του εκπαιδευτικού κ.Αντρέα Νικολόπουλου σε πρώτο στάδιο χωρίστηκαν σε 3 ομάδες 'Βραχίονα,Αισθητήρων και Κίνησης' και παρουσίασαν κατασκευές τους στη Χριστουγεννιάτικη Εκδήλωση του ΔΙΕΚ 2019.

[Εκδήλωση Μέρος 1](https://www.youtube.com/watch?v=K1ToebXxp4s)

[Εκδήλωση Μέρος 2](https://www.youtube.com/watch?v=RxfkprJKBaw)

Στη συνέχεια οι ομάδες σε συνεχή συνεργασία με τους επιβλέποντες εκπαιδευτικούς βελτιστοποιούν τις κατασκευές τους και συνεργάζονται για τη δημιουργία ενός τετρακίνητου Arduino Car Robot (AGRUINO)το οποίο θα μπορεί να κινηθεί σε υποδεδειγμένο χώρο και με τη βοήθεια του βραχίονα να προσεγγίσει τα σημεία ενδιαφέροντος παίρνοντας ακριβείς μετρήσεις. Οι μετρήσεις αυτές καθώς και η ενέργεια που επιλέγει να εκτελέσει το AGRUINO σε πρώτο στάδιο θα παρουσιάζονται σε μια Lcd 20x4(I2C) οθόνη.

#Υλικά κατασκευής

ΑΑ  | Ποσότητα | Περιγραφή | Τιμή / Τεμ. € | Σύνολο €
--|-----|------|------|-----|
1|1 | [Arduino UNO R3 SMD (Compatible)](https://www.devobox.com/el/compatible-boards/163-arduino-uno-r3-compatible.html)|6,6|6,6
2|1 | [L298N](https://grobotronics.com/dual-motor-driver-module-l298n.html)|4,2|4,2
3|1 | [4WD Chassis+Motors](https://grobotronics.com/robot-smart-car-4wd-chassis-26cm.html)|16,9|16,9
4|1 | [20X4 LCD (Supporting I2C)](https://grobotronics.com/basic-20x4-character-lcd-white-on-blue-5v-i2c-protocol.html)|9,9|9,9
5|1 | [DHT22](https://grobotronics.com/rht03-dht22.html)|6,9|6,9
6|1 | [Soil humidity Sensor](https://grobotronics.com/soil-humidity-sensor.html)|1,9|1,9
7|3 | [18650 x 3,6V](https://grobotronics.com/battery-lithium-18650-3.6v-2600mah.html)|4,8|14,4
8|1 | [Battery Holder 3 X 18650](https://grobotronics.com/3x18650-wire-leads.html)|1,5|1,5
9|2 | [Servo ( MG996R)](https://grobotronics.com/servo-standard-11kg.cm-metal-gears-waveshare-mg996r.html)|8,9|17,8
10|3| [3x TCRT5000 Infrared Photoelectric Sensor - Line Track](https://grobotronics.com/infrared-sensor-tcrt5000-with-analog-and-digital-output.html)|1,6|4,8
11|1|[BreadBoard 400](https://grobotronics.com/400.html)|3,2|3,2
12|1|[Ultrasonic Range Finder HC-SR04](https://grobotronics.com/ultrasonic-sensor-sr04.html)|2.5|2.5
13|1|[Transparent Bracket for Ultrasonic HC-SR04](https://grobotronics.com/mounting-bracket-for-ultrasonic.html)|0,6|0,6
14|1|[Buzzer](https://grobotronics.com/buzzer-2-5v-30ma.html)|0,7|0,7
15|1|[Resistor Kit](https://grobotronics.com/resistor-basic-kit-100pcs.html)|1,9|1,9
16|2|[Red Led](https://grobotronics.com/red-led-diffused-10mm.html)|0,4|0,8
17|1|[M-M Jumper Wires](https://grobotronics.com/breadboard-jumper-wires-male-to-male-pack-of-65.html)|3,6|3,6
18|1|[Wires 15cm FF X 10](https://grobotronics.com/jumper-wires-15cm-female-to-female-pack-of-10.html)|1,8|1,8
19|1|[On/Off Switch](https://grobotronics.com/rocker-switch-on-off-red.html)|0,5|0,5
Σύνολο||||100,5

#Βοηθητικά Υλικά Λειτουργικότητας

ΑΑ|Ποσότητα|Ονομασία
--|--|--|
1|1|[18650 Φορτιστής](https://grobotronics.com/charger-for-batteries-li-ion-6x18650-0.5-1a-usb.html)














