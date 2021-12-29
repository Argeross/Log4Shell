# Server Under Control - Log4Shell
Demonstracja i omówienie podatności Log4Shell

## Wymagania wstępne - konto na TryHackMe i połączenie z serwerem VPN
1. Załóż konto na https://tryhackme.com

2. Aby połączyć się z serwerem VPN, ściągnij plik konfiguracyjny VPN:
   Ikonka profilu -> Access -> "Download My Configuration File"

3. Połącz się z serwerem VPN:
   sudo openvpn PLIK_KONFIGURACYJNY
   (Jeśli openvpn nie jest zainstalowany to: sudo apt install openvpn)

4*. W przypadku problemów z połączeniem VPN, można użyć AttackBox'a (nierekomendowane, maszyna wirtualna THM z interfejsem w oknie przeglądarki).

## Zadania

Room: https://tryhackme.com/room/solar

### Zadanie 1.
Wykonaj wszystkie zadania do podpunktu 4. ("Task 4 - Proof of Concept") włącznie, jako potwierdzenie wykonania zrób zrzut ekranu z komunikatem o tym, iż otrzymano połączenie od maszyny atakowanej ("Connection received from MACHINE_IP").

### Zadanie 2.
Wykonaj zadanie 5. ("Task 5 - Exploitation), jako potwierdzenie wykonania zrób zrzut ekranu z rezultatem komendy "whoami && hostname" na atakowanej maszynie. 
