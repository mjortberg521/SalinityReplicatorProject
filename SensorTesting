int switchState;
int switchPin = 4; //switchpin
int motorPin1 = 8; //8 into transistor base
int motorPin2 = 9; //9 into transistor base
int waterSensorPinA = A0; //blue
int waterSensorPinB = A1; //red
int waterSensorPinC = A5; //voltage divider
int waterValueA;
int waterValueB; 
int waterValueC; 


void setup() {
  // put your setup code here, to run once:
  pinMode(motorPin1, OUTPUT); 
  pinMode(motorPin2, OUTPUT); 
  pinMode(waterSensorPinA, INPUT); 
  pinMode(waterSensorPinB, INPUT);
  //A0 doesn't need to be defined
 Serial.begin(9600); 
}

void loop() {
  
 // switchState = digitalRead(switchPin); 
  //waterValue = analogRead(waterSensorPin); 
 
  int waterValueC = analogRead(waterSensorPinC); 
//  int waterValueA = analogRead(A0); //blue
//  int waterValueB = analogRead(A1); //red

 // Serial.println("Blue: " + String(waterValueA) + "    Red: " + String(waterValueB)); 
  //delay(500); 
  Serial.println(waterValueC); 
  delay (500); 
}
