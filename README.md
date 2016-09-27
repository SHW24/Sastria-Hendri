int led = 07;

void setup()
{
  pinMode(led, OUTPUT);
}

void loop()
{
  digitalWrite(led, HIGH);
  delay(3500);
  digitalWrite(led, LOW);
  delay(3500);
}
