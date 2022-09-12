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
      



ESP32
https://wokwi.com/projects/336966830711112275 - LED
https://wokwi.com/projects/336967978479256147 - 3 LED
https://wokwi.com/projects/340880463446934098 - RGB
https://wokwi.com/projects/340882358612787796 - LCD
https://wokwi.com/projects/340886369600537172 - Servo Motor + Pushbutton
https://wokwi.com/projects/340888468071645780 - Servo Motor + Sliding Potentiometer
https://wokwi.com/projects/340890155914101331 - Buzzer + Pushbutton_
https://wokwi.com/projects/340890489300451922 - Buzzer + UltraSonic Sensor
https://wokwi.com/projects/340890896679567955 - Potentiometer + LED
https://wokwi.com/projects/340892440485429842 - DHT22
https://wokwi.com/projects/340893919446303316 - LED CHASER
https://wokwi.com/projects/340936317213868626 - LDR
https://wokwi.com/projects/340936847717827156 - LDR + LED
https://wokwi.com/projects/341409508737679955 - 3 LED + Sliding potentiometer



https://wokwi.com/projects/342584167729463890-Seven segment LED display example
https://wokwi.com/projects/296234816685212169-Analog Joystick with two axes (horizontal/vertical) and an integrated push button
https://wokwi.com/projects/322410731508073042-DHT22 on the ESP32 
https://wokwi.com/projects/342588206115455572-Display distance on LCD screen with buzzer and LED(1)
https://wokwi.com/projects/342589100075778644-(2)
https://wokwi.com/arduino/libraries/demo/electronic-safe-Electronic Safe, powered by an Arduino Uno

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

