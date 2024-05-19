Logowanie się do DockerHub i budowanie obrazu:
![image](https://github.com/Hiubertus/zad1/assets/138579706/758e1a5d-a2be-4efa-8a4c-27c144ed9773)
Schemat projektu:
![image](https://github.com/Hiubertus/zad1/assets/138579706/2ab28bd4-0c1a-4e16-a0f4-cd2e566123b2)
Plik package.json:
![image](https://github.com/Hiubertus/zad1/assets/138579706/97642e9b-cb38-4a19-b5fc-31bbba99e2c9)
Plik server.ts
![image](https://github.com/Hiubertus/zad1/assets/138579706/66eeccf5-b052-47ca-b226-9ed51251751e)
Plik Dockerfile
![image](https://github.com/Hiubertus/zad1/assets/138579706/c4e4f24f-a503-49e7-8d49-d7297fa2c77c)
Uruchamianie obrazu
![image](https://github.com/Hiubertus/zad1/assets/138579706/c48d6fe5-8e12-47b0-8e93-51f85612952f)
Wygląd strony
![image](https://github.com/Hiubertus/zad1/assets/138579706/ef943c31-f0a1-442e-908d-ccbb9b639e5f)

*serwer.ts:

1) zonedTime - zmienna odpowiadająca za ukazywanie godziny na podstawie strefy czasowej.
W sekcji timeZone używamy API Intl, by uzyskać timezone, a następnie z pomocą niego 
wyświetlamy na stronie daną godzinę. Wpisując w timeZone statycznie 'Australia/Sydney'
otrzymalibysmy inna godzine niż wchodząc tam z aktualnego adresu ip. 

2) app.get - służy do wyświetlania pod konkretnym adresem wiadomości

3) app.use - pojawi się w razie problemu

4) app.listen - Słucha na portcie, i wyświetla dane na konsoli

*Dockerfile















