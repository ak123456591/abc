pinmode 腳位模式
pinMode(3,OUTPUT) 腳位模式
# -ARDUINO
學習ARDUINO過程
燈光閃爍
void setup() {
  // put your setup code here, to run once:
  pinMode(3=腳位,OUTPUT=輸出);
}

void loop() {
  // put your main code here, to run repeatedly:
  digitalWrite(3=腳位,LOW);
  delay(500);
  digitalWrite（3 =腳位，HIGH）;
  delay(500);
}
------------------------- 
int LED=5;
void setup() {
  for(int i=2 ;i<6;i++)
   pinMode(i,OUTPUT);
}
void loop() {
  // put your main code here, to run repeatedly;
  for(int i=5; i>1; i--)
    digitalWrite(i,HIGH);
  if (LED>=2)
    digitalWrite(LED,LOW);
  else
     LED=6;
  LED--;
  delay(1000);
}
4個燈有左到右
- - - - - - - - - - - - - - - 
