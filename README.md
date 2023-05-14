# BLYNK-STARTER

#define BLYNK_TEMPLATE_ID "..."
#define BLYNK_TEMPLATE_NAME "..."
#define BLYNK_AUTH_TOKEN "..."

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
