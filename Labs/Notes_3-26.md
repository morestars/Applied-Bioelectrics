# Notes for 3/26/2019

### Course Topics

### Presentation on May 15

### Grading
* 15% each lab report
* 70% course project

### Resources
* Practial electrical engineering by Markaov, Ludwig, and Bitar
  * Available through Hopkins libraries
* Design Studio
  * Chris Browne and Tom Benassi
  
### Op Amps
* doulbe-check naming conventions for a given opamp
* open loop gain
  * Vo = A(V+ - V-)
  * A is large, but gain is limited by rail voltages
* feedback loop
  * Vo = A/(1+A) * V+
  * as A gets big, it becomes a unity gain aka voltage follower
  * need high resistance to prevent loading effects
  
### Instrumentation Amplifier
* can't just stick voltage followers in front of differential amplifier due to common mode gain
  * also need gain across the stages so unity gain isn't great
