# QR_OO
Erzeugen eines EPC-QR-Codes in Writer-Dokumenten

- Grundgerüst für eine Rechnung mit einem QR-Code als Überweisungsvorlage
- durch Drücken des Buttons wird ein standardisierter QR-Code ("EPC") eingefügt, der von gängiger Zahlungsverkehrssoftware eingelesen werden kann
  https://de.wikipedia.org/wiki/EPC-QR-Code

Voraussetzung ist das Open-Source-Programm qrencode.exe (Getestet mit Version 3.4.0 unter Windows) im Unterordner "QREncode" des Open-Office-Programmverzeichnisses.
(also z.B.: %programfiles%\OpenOffice 4\program\QREncode) Download hier: https://github.com/fukuchi/libqrencode

Kontonummer und -inhaber oder Schlüsselwörter zum Extrahieren des Verwendungszwecks und des Betrags, sowie Position des QR-Codes werden direkt im Makro hinterlegt.
Hier müssen also für die individuelle Verwendung mindestens die Zeilen "epc_name=" und "epc_iban=" geändert werden. 

Es handelt sich um eine für eigene Zwecke erstellte Anwendung, die nur wenig für Einsatz durch andere modifiziert wurde.

--

https://github.com/cscode2000/QR_OO
