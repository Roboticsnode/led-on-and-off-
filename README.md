<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/0e6bb701-9396-46d9-be52-7b705a04bd46" /># led-on-and-off-
void setup() {
  pinMode(13, OUTPUT);   // LED pin as output
}

void loop() {
  digitalWrite(13, HIGH);   // LED ON
  delay(1000);              // 1 second delay
  digitalWrite(13, LOW);    // LED OFF
  delay(1000);              // 1 second delay
}
