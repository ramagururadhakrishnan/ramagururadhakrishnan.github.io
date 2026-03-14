---
title: "System and Method for Securing Clipboard Data in a Windows Operating System Environment"
collection: Patent
permalink: /publication/2026-02-20-clipboard
excerpt: 'The present disclosure relates to a system (102) and method (200) for securing clipboard data in a Windows operating system environment. The system (102) includes a processor (104) configured to monitor copy and paste actions initiated by applications and classify them as semi-trusted or untrusted based on a predetermined access threshold. The system (102) determines whether both the copying and pasting applications exist in a predefined authorised application list and allows clipboard operations only if both applications are authorised. During a copy action, clipboard data is received and processed to generate a hashed message authentication code using a timestamp and a secret code provided after each device restart. During pasting, data integrity is verified by regenerating the hashed code. The data is further encrypted, encoded, and stored in the clipboard. Upon a valid paste request, the data is decoded and decrypted using a regenerated decryption key and delivered to the pasting application.' 
date: 2026-02-20
paperurl: 
citation: 'Ramaguru R., Aishwarya G., Alagu Soundarya., Deepthi J., Adhwaith S., Suvetha D P., & Yaswanth G. (2026). System and Method for Securing Clipboard Data in a Windows Operating System Environment (Indian Patent Application Number: 202541133689). Indian Patent Office. https://ipindiaservices.gov.in/'
---

The present disclosure relates to a system (102) and method (200) for securing clipboard data in a Windows operating system environment. The system (102) includes a processor (104) configured to monitor copy and paste actions initiated by applications and classify them as semi-trusted or untrusted based on a predetermined access threshold. The system (102) determines whether both the copying and pasting applications exist in a predefined authorised application list and allows clipboard operations only if both applications are authorised. During a copy action, clipboard data is received and processed to generate a hashed message authentication code using a timestamp and a secret code provided after each device restart. During pasting, data integrity is verified by regenerating the hashed code. The data is further encrypted, encoded, and stored in the clipboard. Upon a valid paste request, the data is decoded and decrypted using a regenerated decryption key and delivered to the pasting application.


