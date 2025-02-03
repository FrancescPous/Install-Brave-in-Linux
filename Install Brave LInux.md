Install Brave Linux

PAS 1: COMANDES
1:
   ```
 sudo apt update
   ```
2:
   ```
 sudo apt install apt-transport-https curl
   ```
3:
   ```
 curl -fsSL https://brave-browser-apt-release.s3.brave.com/brave-core.asc | sudo gpg --dearmor -o /usr/share/keyrings/brave-browser-archive-keyring.gpg
   ```
4:
   ```
 echo "deb [signed-by=/usr/share/keyrings/brave-browser-archive-keyring.gpg] https://brave-browser-apt-release.s3.brave.com/ stable main" | sudo tee /etc/apt/sources.list.d/brave-browser.list
   ```
PAS 2: COMANDES:
1:
   ```
 sudo apt update
   ```
2:
   ```
 sudo apt install brave-browser 
   ```
PAS 3: INICIAR BRAVE

Dintre de la terminal escribirem la seguent comanda
   ```
brave-browser
   ```
