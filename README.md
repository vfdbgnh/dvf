int Red=6;
int Blue=8;

void steup()
(
pinMode(Red,OUTPUT);
pinMode(Blue,OUTPUT);
)
void loop()
(
digitqlWrite(Red,HIGH);
digitqlWrite(Blue,LOW);
delay(1);


digitqlWrite(Red,LOW);
digitqlWrite(Blue,HIGH);
delay(2);

