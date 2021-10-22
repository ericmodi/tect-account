int pin1=2;
int pin2=3;
int pin3=4;
int pin4=5;
void setup()
{
  Serial.begin(9600);
pinMode(pin1,OUTPUT);
}
void loop()
{digitalWrite(pin1,1);
delay(100);
digitalWrite(pin1,0);
delay(300);
}