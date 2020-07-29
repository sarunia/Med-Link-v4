# MED-LINK-v.4
Pilot do pompy insulinowej Medtronic Veo i 722 w wersji bez wyświetlacza i przycisków. Jest to wersja w pełni obsługiwana poprzez połączenie Bluetooth przez napisaną na telefony Android aplikację "MedLinkUI". Wspólne pliki z instrukcjami i opisami są dostępne w folderze z dokumentacją pilota Med-Link v3 z wyświetlaczem.

opis pilota na polskiej grupie Nightscout:

http://nightscout.pl/medtronic/minimed-serii-5xx-i-7xx/minimed-veo/med-link-dla-veo-i-722/

projekt pilota Med-Link v4 z wyświetlaczem:

https://github.com/sarunia/MED-LINK

aplikacja „MedLinkUI” do współpracy z pilotem:

https://github.com/cino893/med-link-ui

grupa na facebooku dla użytkowników i zainteresowanych pilotem:

https://www.facebook.com/groups/492021978253801/

wątek opisujący zagadnienia technicze przy projekcie pilota na grupie Nightscout Polska:

https://www.facebook.com/groups/NightscoutPoland/permalink/1563178353790345/

Programowanie pilota:
najpierw wgrać firmware opisany jako Med-Link v4 long BT config.s19
który wykona pełną konfigurację modułu bluetooth w pilocie, 
a następnie zrestartować pilot i wgrać plik Med-Link v4 29_07_20 last release.s19
