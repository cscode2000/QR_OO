# QR_OO
Erzeugen eines EPC-QR-Codes in Open-Office-Writer-Dokumenten

- Grundgerüst für eine Rechnung mit einem QR-Code als Überweisungsvorlage
- durch Drücken des Buttons wird ein standardisierter QR-Code ("EPC") eingefügt, der von gängiger Zahlungsverkehrssoftware eingelesen werden kann
  https://de.wikipedia.org/wiki/EPC-QR-Code

Voraussetzung ist das Open-Source-Programm qrencode.exe (Getestet mit Version 3.4.0 unter Windows) im Unterordner "QREncode" des Open-Office-Programmverzeichnisses.
Download hier: https://github.com/fukuchi/libqrencode

Kontonummer und -inhaber oder Schlüsselwörter zum Extrahieren des Verwendungszwecks und des Betrags werden direkt im Makro hinterlegt.
Hier müssen also für die individuelle Verwendung mindestens die Zeilen "epc_name=" und "epc_iban=" geändert werden. 

Es handelt sich um ein für eigene Zwecke erstelltes Dokument, das nur wenig für Einsatz durch andere modifiziert wurde.

--

https://github.com/cscode2000/QR_OO
