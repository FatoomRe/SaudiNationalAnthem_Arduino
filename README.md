# Saudi National Anthem Buzzer - Arduino Project 💚

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

