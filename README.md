# DC-motor- int motorAl = 2:

int motorA2 = 3;

I

int motorB1 = 4;

int motorB2 5:1 =

void setup() {

// put your setup code here
pinmode (motorA1,  output);
pinmode (motorA2,  output); 
pinmode (motorB1,  output);
pinmode (motorB2,  output);

digitalWrite(motorA1,  HIGH);
digitalWrite(motorA2,  LOW);

digitalWrite(motorB1,  HIGH);
digitalWrite(motorB2,  LOW);

}
void loop() { 
// put your main code here
digitalWrite(motorA1,  HIGH);
digitalWrite(motorA2,  LOW);

digitalWrite(motorB1,  HIGH);
digitalWrite(motorB2,  LOW);
delay(2000);

digitalWrite(motorA1,  LOW);
digitalWrite(motorA2, HIGH);

digitalWrite(motorB1,  LOW);
digitalWrite(motorB2, HIGH);
