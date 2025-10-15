# Arduino-uno-code-for-led-blinking
// These are the functions that Arduino needs
// They are part of the default sketch
void setup() {
  // put your setup code here, to run once:
  // This line initializes pin 13 as an output pin.
  pinMode(LED_BUILTIN, OUTPUT);
}

// The loop function runs over and over again forever.
void loop() {
  // turn the LED on (HIGH is the voltage level)
  digitalWrite(LED_BUILTIN, HIGH);
  // wait for a second (1000 milliseconds)
  delay(1000);
  // turn the LED off by making the voltage LOW
  digitalWrite(LED_BUILTIN, LOW);
  // wait for a second (1000 milliseconds)
  delay(1000);
}
