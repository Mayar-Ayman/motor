# Servo motor

**C++ code by Arduino IDE 

The library for servo motor 

`include <Servo.h>`

Defining a variable with a value of zero to use in a for loop
`int pos = 0;
`
Give a name to the servo which is servo_9
`Servo servo_9;`

```
*void setup()
{
Servo delivery in pin No.9
  servo_9.attach(9);
}

*void loop()
{
```

sweep the servo from 0 to 360 degrees 
  `for (pos = 0; pos <= 360; pos += 1) {`
  
  \
  tell servo to go to position in variable 'pos'
    `servo_9.write(pos);`
    
    \
  wait 0 ms for servo to reach the position
  
  ```
    delay(0);
  }
  
  *for (pos = 360; pos >= 0; pos -= 1) {
  
  tell servo to go to position in variable 'pos'
    *servo_9.write(pos);
    ```
    
    wait 0 ms for servo to reach the position
   ` *delay(0);
  }
}`


