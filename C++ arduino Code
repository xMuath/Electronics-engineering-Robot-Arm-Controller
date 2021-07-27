// C++ code
//
#include <Servo.h>

int res1 = 0;

int res2 = 0;

int res3 = 0;

int res4 = 0;

int res5 = 0;

int res6 = 0;

Servo servo_9;

Servo servo_10;

Servo servo_11;

Servo servo_6;

Servo servo_5;

Servo servo_3;

void setup()
{
  pinMode(A0, INPUT);
  servo_9.attach(9, 500, 2500);

  pinMode(A1, INPUT);
  servo_10.attach(10, 500, 2500);

  pinMode(A2, INPUT);
  servo_11.attach(11, 500, 2500);

  pinMode(A3, INPUT);
  servo_6.attach(6, 500, 2500);

  pinMode(A4, INPUT);
  servo_5.attach(5, 500, 2500);

  pinMode(A5, INPUT);
  servo_3.attach(3, 500, 2500);

}

void loop()
{
  res1 = analogRead(A0);
  res1 = map(res1, 0, 1023, 0, 90);
  servo_9.write(res1);

  res2 = analogRead(A1);
  res2 = map(res2, 0, 1023, 0, 90);
  servo_10.write(res2);

  res3 = analogRead(A2);
  res3 = map(res3, 0, 1023, 0, 90);
  servo_11.write(res3);

  res4 = analogRead(A3);
  res4 = map(res4, 0, 1023, 0, 90);
  servo_6.write(res4);

  res5 = analogRead(A4);
  res5 = map(res5, 0, 1023, 0, 90);
  servo_5.write(res5);

  res6 = analogRead(A5);
  res6 = map(res6, 0, 1023, 0, 90);
  servo_3.write(res6);
  delay(10); // Delay a little bit to improve simulation performance
}
