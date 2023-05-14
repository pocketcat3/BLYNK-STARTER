# BLYNK-STARTER

#define BLYNK_TEMPLATE_ID "TMPL4j6UoSo_7"
#define BLYNK_TEMPLATE_NAME "Quickstart Template"
#define BLYNK_AUTH_TOKEN "d4WZEqpvoI3nrAXHsAl8vpIBbkNVh8At"

#include <WiFi.h>
#include <WiFiClient.h>
#include <Blynk.h>

char ssid[] = "Robocode";
char pass[] = "robocode";

void setup() {
  Blynk.begin(BLYNK_AUTH_TOKEN, ssid, pass);
}

void loop() {
}
