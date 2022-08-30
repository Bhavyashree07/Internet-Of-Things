# Internet-Of-Things
1.https://wokwi.com/projects/333715410055594580  (3LED)<br>
RGB :<br>
2.https://wokwi.com/projects/333804680383562322  (starting with red green and blue)<br>
3.https://wokwi.com/projects/322062421191557714  (hello wokwi)<br>
4.https://wokwi.com/projects/334980856741364308  (servo motar clocktype)<br>
5.https://wokwi.com/projects/334982136325997140  (servometer with potentiometer)<br>
6.https://wokwi.com/projects/336873643743117906   ( servometer with push button)<br>
7.https://wokwi.com/projects/335065072543990354  (buzzor+registor)<br>
8.https://wokwi.com/projects/335068937651749459  (buzzor+registor+button)<br>
9.https://wokwi.com/projects/335071539262128722  (ultrasonic)<br>
10.https://wokwi.com/projects/335605344348668500  (ultrasonic with buzzor)<br>
11.https://wokwi.com/projects/335610819506078291   (Ultrasonic+buzzor+led+resistor)<br>
12.https://wokwi.com/projects/336873560120230483  (potentiometer with led)<br>
13https://wokwi.com/projects/337602684471214674 - DHT22(Humidity and Temperature sensor)<br>
14.https://wokwi.com/projects/337604296859189842 - DHT22 + LCD(Humidity and Temperature sensor)<br>
15.https://wokwi.com/projects/340775764469219922 - (LED_CHASER)<br><br>
16.https://wokwi.com/projects/340776572602548818 - LDR<br>
17.https://wokwi.com/projects/340776926585029204 - LDR_LED<br> 
      


sound sennsor<br>
 const int ledPin = 12;<br>
const int soundPin = 8;<br>
int soundVal = 0;<br>
void setup ()<br>
{<br>
  pinMode (ledPin, OUTPUT);<br>
  pinMode (soundPin, INPUT);<br>
  Serial.begin (9600);<br>
}<br>
 void loop ()<br>
{<br>
  soundVal = digitalRead(soundPin);<br>
  if (soundVal == HIGH)<br>
  {<br>
    digitalWrite(ledPin, HIGH);<br>
    Serial.println("Clap detected");<br>
    delay(1000);<br>
  }<br>
  else<br>
  {<br>
    digitalWrite(ledPin,LOW);<br>
      }<br>
 }  <br>    
 
 
     






 


