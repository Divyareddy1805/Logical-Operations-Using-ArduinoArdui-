# Logical-Operations-Using-ArduinoArdui-
void setup() {
  // put your setup code here, to run once:
Serial.begin(9600);
int a,b;
a=3,b=9;
if(a==3 && b==9)
{
  Serial.println("Both Conditions are Same");
}
  else
  {
    Serial.println("Both Conditions are Same");
  }
    if(a==5 || b==8)
    {
      Serial.println("One Condition is Same");
    }
    else
    {
      Serial.println("none of the condition is same");
    }
}


void loop() {
  // put your main code here, to run repeatedly:

}
