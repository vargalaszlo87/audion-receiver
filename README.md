# audion-receiver
Audion receiver, more sensitive than the crystal envelope detector.

In this case the operating point of the transistor isn't on the linear section, but on the exponential part. As you can see in the next picture, its operation is similar to the diode:

- the transistor conducts the current in the positive period
- the transistor "not" (to a small extent.) conducts in the negative period.

(it's a FET, but it works the same as the BJT.)
![image](https://github.com/user-attachments/assets/4b2a3d50-a1ba-49bd-ae89-bed94ec1198f)

## The circuit

It's the simulatio in LTSpiceXVII, the name of file is: audion-receiver.asc

![image](https://github.com/user-attachments/assets/b106e68b-a314-4c13-96e9-bbf64e3663bd)

The physical circuit on the test-board:

![teszt-aramkor](https://github.com/user-attachments/assets/647ce23d-7323-46ea-8c8f-1f434669cf81)

## Signals from simulation

![image](https://github.com/user-attachments/assets/5b047411-4153-450a-9c61-1e8b5ec69a6d)

## Signals from measurement

![bemenet-kimenet](https://github.com/user-attachments/assets/73f5057c-496e-49cf-a2a7-b27ceadb0598)




