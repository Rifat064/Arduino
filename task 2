 int x;
int buttonpin=7;
int ledpin=9;


void setup(){
 Serial.begin(9600);
 pinMode(buttonpin,INPUT_PULLUP);
 pinMode(ledpin, OUTPUT);
 


  
}
void loop(){

  x=digitalRead(buttonpin);
 
 if (x==0){
  digitalWrite(ledpin, HIGH);
 }
  else if (x==1) 
    digitalWrite(ledpin, LOW);

  
}
