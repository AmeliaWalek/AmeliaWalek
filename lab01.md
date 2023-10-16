Inicjalizacja katalogu repozytorium:
Należy utworzyć katalog repozytorium:

cd /
mkdir ppo
cd ppo
mkdir 123456
cd 123456
Kolejne polecenia oznaczają:

przejdź do głównego katalogu
utwórz katalog o nazwie ppo
przejdź do katalogu o nazwie ppo
utwórz katalog o nazwie 123456 (tutaj dobrze wpisać swój numer indeksu)
przejdź do katalogu o nazwie 123456 (ponownie: indeks)
Inicjalizacja repozytorium:
Znając adres repozytorium (np. https://github.com/collegiumwitelona/2023-ppo1-twojanazwauzytkownika) należy wykonać następujące polecenia:

git init
git remote add origin https://github.com/collegiumwitelona/2023-ppo1-twojanazwauzytkownika
git pull origin master
git status
Kolejne polecenia oznaczają:

oznacz folder jako repozytorium git
ustaw połączenie z serwerem
ściąga dane z serwera
pokazuje stan repozytorium
Wprowadzanie zmian do repozytorium
Prawdopodobnie przy pierwszych zmianach będzie trzeba dodać poświadczenia uwierzytelniające:

git config user.name "Imię Nazwisko"
git config user.email "imie.nazwisko@student.collegiumwitelona.pl"
Warto podać swoje prawdziwe dane, aby Github później przyjął żądanie. Po jakiejkolwiek zmianie, dodaniu lub usunięciu pliku, należy zapisać swoje zmiany:

git add .
git status
git commit -am "zmiany"
git push origin master
Kolejne polecenia oznaczają:

dodaje wszystkich niedodanych plików z katalogu "." do repozytorium
pokazuje stan repozytorium
tworzy commit o nazwie "zmiany"
przesyła commity na serwer
