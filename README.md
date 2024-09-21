# Saudi National Anthem - Arduino Project 💚

<table>
  <tr>
    <td>
      <a href="https://FatoomRe.io">
        <img src="https://cdn.pixabay.com/animation/2022/09/08/04/49/04-49-32-19_512.gif" alt="MasterHead 1">
      </a>
    </td>
    <td>
      <a href="https://FatoomRe.io">
        <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTFoYmN5NzMweHVtNWVrNHozcjNndGJ3cmFnZmhkZHNwMGs0N21zdiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/mFDWuDppjQJjite6FS/200.webp" alt="MasterHead 2">
      </a>
    </td>
  </tr>
</table>


## Description
This project uses an Arduino to play the Saudi National Anthem using a piezo buzzer. The buzzer emits sound frequencies that correspond to the notes of the anthem.


I was curious about how tones could be played within a circuit or on a microcontroller, and that's when I discovered the Arduino tone() function. I found several projects that used this module to play tunes like "Happy Birthday" and "Super Mario" 

After exploring the functionality of this module, I decided to use it to play our National Anthem. I transcribed the notation of the Saudi National Anthem by playing it on piano, writing it down on paper, converting it to frequencies, and then started to write a program for Arduino.

![intervalchart](https://github.com/user-attachments/assets/cbf9fae8-a212-4c1f-94f4-801a3e447aab)
![notes](https://github.com/user-attachments/assets/2e89d3bf-c7c4-454a-93bd-d339a8c0379e)

After 20-30 iterations, adjusting the tempo, frequencies of notes, and duration, I finally achieved a satisfying output. It was a fun project for me, and I hope you like it.


https://github.com/user-attachments/assets/c0ecac96-6be4-4016-8d32-54dd44d4c7f3


## Components
- Arduino Uno 
- Piezo Buzzer
- Jumper Wires
- Breadboard
- Green LED (Optional)

![Fantabulous Sango-Hango](https://github.com/user-attachments/assets/e56feba0-a27a-45f1-88b6-5e395afdcde4)


## Wiring
1. Connect the positive leg of the buzzer to Arduino pin 8 (PWM pin).
2. Connect the negative leg to the GND pin.


![‪Circuit design Fantabulous Sango-Hango - Tinkercad - Google Chrome‬ 9_20_2024 01_04_46 PM](https://github.com/user-attachments/assets/93341dc8-3d0f-4c0f-968e-22dd2cc7fb2f)


## Code
```sh
    
void SaudiNationalAnthem(int buzzerPin) {

  tone(buzzerPin, 349);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 349);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 349);
  delay(1200);
  noTone(buzzerPin);

  tone(buzzerPin, 262);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 349);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 392);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 440);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 466);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(1200);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 587);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 466);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 440);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 392);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 349);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 330);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 349);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 587);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 466);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 440);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 349);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 698);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 659);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 587);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 466);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 466);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 466);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 587);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 466);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 440);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 349);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(600);
  noTone(buzzerPin);

  tone(buzzerPin, 587);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 659);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 698);
  delay(1200);
  noTone(buzzerPin);

  tone(buzzerPin, 349);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 349);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 349);
  delay(1500);
  noTone(buzzerPin);

  tone(buzzerPin, 262);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 349);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 392);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 440);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 466);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(600);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 587);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 466);
  delay(300);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(600);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 698);
  delay(600);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(500);
  noTone(buzzerPin);

  tone(buzzerPin, 523);
  delay(125);
  noTone(buzzerPin);

  tone(buzzerPin, 698);
  delay(600);
  noTone(buzzerPin);
}

void setup() {

  SaudiNationalAnthem(8);
}

void loop() {
  // No need for loop code
}

```
## Thank You 💚

Thank you for checking out my Saudi National Anthem Arduino project! I hope you found it fun and educational. If you enjoyed the project, please consider giving the repository a ⭐.
Your support means a lot and encourages me to keep creating more cool projects!

If you have any feedback, improvements, or ideas for other projects, feel free to reach out. Let's keep building and learning together!

[⭐ Star the Repository](https://github.com/FatoomRe/SaudiNationalAnthem_Arduino) 🙌


