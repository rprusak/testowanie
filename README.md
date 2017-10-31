# Testowanie
## Instalacja w3af
W3AF instalujemy na maszynie wirtualnej z Ubuntu 17.04 64bit. Maszynę można pobrać z osboxes.com.
Aby zainstalować aplikację musimy wykonać następujące polecenia:

```
sudo apt-get update
sudo apt-get upgrade

sudo apt-get install git
sudo apt-get install python-pip
sudo apt-get install libxslt-dev libssl-dev

git clone https://github.com/andresriancho/w3af.git
cd w3af/
./w3af_console
. /tmp/w3af_dependency_install.sh

```

Następnie możemy uruchomić aplikację za pomocą polecenia:

```
./w3af_console
```

Na chwilę obecną nie udało odpalić się gui, ponieważ paczka _webkit_ została usunięta z repozytorium systemowego.