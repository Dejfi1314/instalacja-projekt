/*************************************************************
  Pobierz najnowszą bibliotekę z linku poniżej:
    https://github.com/blynkkk/blynk-library/releases/latest
 *************************************************************/

#define BLYNK_PRINT Serial
#include <ESP8266WiFi.h>
#include <BlynkSimpleEsp8266.h>

// Powinieneś uzyskać Auth Token w aplikacji Blynk.
// Przejdź do Ustawień projektu.

char auth[] = "680b00f1d61946d9b09257cd1ad2b8db"; //Token uwierzytelniania uzyskasz drogą mailową , jeśli zarejestrujesz aplikację Blynk przy użyciu swojego identyfikatora E-mail.

// Twoje dane logowania do Wi-Fi.
// Hasło zostaw puste w przypadku niezabezpieczonych sieci WI-FI.

char ssid[] = "SSID :p"; //Nazwa SSID sieci.
char pass[] = "1122334455";//Hasło do sieci.

void setup()
{
  // Debug console
  Serial.begin(9600);
  pinMode(D1,OUTPUT);
  pinMode(D2,OUTPUT);
  pinMode(D3,OUTPUT);
  pinMode(D4,OUTPUT);
  pinMode(D5,OUTPUT);
  pinMode(D6,OUTPUT);
  pinMode(D7,OUTPUT);
  pinMode(D8,OUTPUT);

  digitalWrite(D1,HIGH);
  digitalWrite(D2,HIGH);
  digitalWrite(D3,HIGH);
  digitalWrite(D4,HIGH);
  digitalWrite(D5,HIGH);
  digitalWrite(D6,HIGH);
  digitalWrite(D7,HIGH);
  digitalWrite(D8,HIGH);
  

  Blynk.begin(auth, ssid, pass);
  // Możesz również określić serwer:
  //Blynk.begin(auth, ssid, pass, "blynk-cloud.com", 8442);
  //Blynk.begin(auth, ssid, pass, IPAddress(192,168,1,100), 8442);
}

void loop()
{
  Blynk.run();
}

