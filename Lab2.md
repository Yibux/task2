## Zadanie 1
Podczas tworzenia nowego klienta - obiekt Customer - zostało zaobserwowane logowanie powstałego obiektu z widocznymi danymi wrażliwymi tj. pesel i adres.
![Logowanie peselu i adresu klienta](https://raw.githubusercontent.com/Yibux/task2/refs/heads/main/Logowanie_peselu_i_adresu.png)

### Poprawki w kodzie
Dodałem "maskę" w logowaniu peselu i adresu klienta.
![Logowanie peselu i adresu klienta po poprawie](https://raw.githubusercontent.com/Yibux/task2/refs/heads/main/Logowanie_peselu_i_adresu_po_poprawie.png)
## Zadanie 2
Gitleaks wykryło 3 wycieki secretów w repozytorium:
![Wycieki secretów](https://raw.githubusercontent.com/Yibux/task2/refs/heads/main/wycieki_secretow.png)

Każdy z wycieków to rodzaj `True Positive`, ponieważ zawiera klucze publiczne i prywatne. Gitleaks nie wykrył występowania zmiennych o nazwie `password`.
## Zadanie 3
