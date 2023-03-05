## Dual Boot Linux Mint VS Win 10 (Lenovo G750)

1. Formatiranje Win10 (ukoliko je potrebno) :warning: :exclamation:
2. Prilikom formatiranja izbrisati sve particije i particionisati disk (ukoliko je potrebno). :warning: :exclamation:
    - Napomena: Uradite backup fajlova ili sistema za svaki slučaj ako imate samo jedan laptop. :warning: :exclamation:

3. Podjela diska prilikom instalacije  

    - Particija za Windows (kasnije Mint ce biti instaliran na istu particiju pored Windowsa) 
    - Particija za podatke

4. Instalacija Windowsa 


## Priprema USB-a za instalaciju Linux Mint distribucije.

Softver potreban za izradu bootabilnog USB-a je Rufus. 

:heavy_check_mark: [Rufus download](https://rufus.ie/en/)
:heavy_check_mark: USB stick: 32GB

:sparkle: Postavke Rufus
 - Partition scheme: MBR
 - Target system: BIOS or UEFi

Prilikom restarta potrebno je podesiti bootanje sa USB-a, a ne diska, kako bi pokrenuli boot screen sa USB-a. 

Na boot screen meniju koji se pojavio izabrati "Start Linux Mint". To je live mode linuxa Mint u kojem možemo da testiramo wifi, drivere i ostalo  da li je kompatibilno sa našim hardverom.

Na desktopu se nalazi ikonica "Install Linux Mint", pritisnite enter na ikonu kako bi se pokrenula instalacija Mint-a. 

## Instalacija 


1. Language: English
2. Keyboard Layout: izaberite u zavisnosti koja je kod vas tastatura
3. Install Multimedia Codecs (reprodukcija audio i video fajlovi)
4. Izabrati opciju "Install Linux Mint alongside Windows"

   - Izabrati 'Yes' na poruci: "Unmount partitions that are in use?"
    Unmount je potreban kako bi mogli da podijelimo disk i kreiramo prostor za Mint. Ostavi se dovoljno prostora za Windows,
    ali i za Mint. 

5. Izaberite velicinu diska koji cete koristiti za Mint instalaciju. Particija na kojoj je instaliran WIndows10 se koristi za instalaciju Linux Mint. 
6. Izabrati lokaciju (postavlja i vremensku zonu)
7. Unijeti username, computer name i šifru.
8. Nakon što se instalacija završi, pojavi se poruka : "Installation complete ". Izabrati Restart Now. 
9. Izvucite USB
10. Nakon restarta pojavljuje se prozor na kojem možete da unesete šifru za login. 
