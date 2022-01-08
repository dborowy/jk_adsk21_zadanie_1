# Zadanie ADSK - Dominik Borowy

## Ansible - Wordpress
Zadanie: https://e-uczelnia.uek.krakow.pl/mod/assign/view.php?id=738743

Ansible playbook tego zdania znajduję się w pliku *wordpress-playbook.yml*


- Uruchomienie
![wp_run](img/wp_run.png)
- Wynik
![wp_run](img/wp_result.png)

## Ansible - Status-page + proxy
Zadanie: https://e-uczelnia.uek.krakow.pl/mod/assign/view.php?id=738744

Ansible playbook tego zdania znajduję się w pliku *status-page-playbook.yml*

Playbook instaluje Dockera i następnie wystawia skonteneryzowane wersje serwera proxy oraz prostego status-page'a.<br>
Proxy przekierowuje zapytania z portu 80 i domeny podanej jako zmienna *status_host* w pliku *vars/default.yml* na port 3001 kontenera status-page.

- Uruchomienie
![wp_run](img/status_run.png)
- Wynik
![wp_run](img/status_result.png)
- Infrastruktura sieciowa w ramach której działa usługa proxy i aplikacja
![wp_run](img/status_network.png)