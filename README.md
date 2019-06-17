<h1>Arduno-UNO</h1>
<h3>Arduino UNO R3 บอร์ดทดลอง </h3>
<p>Arduino เป็นไมโครคอนโทรลเลอร์ที่นำไปใช้อย่างแพร่หลายในปัจจุบัน สามารถเรียนรู้ได้รวดเร็ว จึงเหมาะสำหรับการนำไปสร้างโปรเจ็กต์ ต่างๆ ไมโครคอนโทรลเลอร์ Arduino ทุกรุ่น จะใช้ชิป AVR เป็นหลัก เพราะมีความทันสมัย ไมโครคอนโทรลเลอร์ Arduino สามารถโปรแกรมผ่านพอร์ตอนุกรมชนิต UART ได้ จึงทำให้เขียนโปรแกรมลงไปในชิป โดยการใช้การเชื่อม USB ติดต่อกับ UART
เราสามารถใช้ โปรแกรม Arduino IDE ในการเขียนโปรแกรม และ Upload โปรแกรมลงBoard Arduinoได้ โดยการเชื่อมต่อผ่านสายUSB เท่านี้เราก็จะได้สนุกกับความาสารของ Board Arduino กันแล้ว</p>


1. ติดตั้ง โปรแกรม Arduino IDE <a href="https://www.arduino.cc/en/Main/Software" target="_blank">Click</a> <br>
2. ติดตั้ง Driver USB CH340 <a href="https://sparks.gogo.co.nz/ch340.html" target="_blank">Click</a>

รูปร่างบอร์ด


แสดงขาต่างของบอร์ด


ตัวอย่าง Code

nt led = 13;
  void setup() {                
    pinMode(led, OUTPUT);     
  }

  void loop() {
    digitalWrite(led, HIGH);  
    delay(1000);              
    digitalWrite(led, LOW);  
    delay(1000);              
  }

