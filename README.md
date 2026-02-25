
# DESIGN OF INVERTING, NON INVERTING AND DIFFERENTIAL AMPLIFIERS 
# AIM:
To design and construct a inverting, non- inverting and differential amplifiers.

# APPARATUS REQUIRED:

| S.No | Name of the Apparatus        | Range     | Quantity     |
|------|------------------------------|-----------|--------------|
| 1    | Function Generator           | 3 MHz     | 1            |
| 2    | DSO                          | 30 MHz    | 1            |
| 3    | Dual RPS                     | (0–30) V  | 1            |
| 4    | Op-Amp                       | µA741     | 1            |
| 5    | Bread Board                  | —         | 1            |
| 6    | Resistors                    | 1K, 10K   | 2            |
| 7    | Connecting wires and probes  | —         | As required  |

# THEORY:
Op-amp in open-loop configuration has a very few application because of its enormous open- loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.
### INVERTING AMPLIFIER:
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1
### NON - INVERTING AMPLIFIER:
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)
### DIFFERENTIAL AMPLIFIER :
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as

# MODEL GRAPH
<img width="585" height="360" alt="image" src="https://github.com/user-attachments/assets/3cc336e5-ae5b-4863-b1e7-b37fdacffe09" />

### PRACTICAL GRAPH
<img width="418" height="613" alt="image" src="https://github.com/user-attachments/assets/b752346c-ca2c-48d5-ad90-92a483fd75c7" />

### CIRCUIT DIAGRAM

### INVERING AMPLIFIER


<img width="684" height="390" alt="image" src="https://github.com/user-attachments/assets/84b7312f-21eb-4ea4-be4b-45ee9af758fc" />

### TABULATION
| S.No | Vin (volts) | Time (ms) | Vo (Theoretical) [V] | Vo (Practical) [V] |
|------|-------------|-----------|-----------------------|---------------------|
| 1    |  1.2        |    0.1ms  |        12             |         13          |
| 2    |  0.6        |    0.2ms |         6              |         6.4         |
| 3    |  1.32       |    0.3ms  |       13.2            |      14.80          |


# MODEL GRAPH
<img width="667" height="445" alt="image" src="https://github.com/user-attachments/assets/12729150-ffab-409c-ac6c-c1992b42b9c4" />

### PRACTICAL GRAPH
<img width="490" height="712" alt="image" src="https://github.com/user-attachments/assets/0f5c435f-554c-4217-9ea9-a2f81d708189" />

### CIRCUIT DIAGRAM

### NON-INVERING AMPLIFIER

<img width="880" height="470" alt="image" src="https://github.com/user-attachments/assets/d84d7825-63fb-4b6b-af40-904567fc3019" />

### TABULATION
| S.No | Vin (volts) | Time (ms) | Vo (Theoretical) [V] | Vo (Practical) [V] |
|------|-------------|-----------|-----------------------|---------------------|
| 1    |     0.62v   | 0.1       | 6.82v                 |   6.60v             |
| 2    |     1.1v    | 0.2       |  12.1v                |    11.2v            |
| 3    |     1.5v    | 0.3       |  16.5v                |    15v              |

# MODEL GRAPH
<img width="940" height="401" alt="image" src="https://github.com/user-attachments/assets/9a1a005e-447f-498f-b473-ebf591512669" />

### PRACTICAL GRAPH

### CIRCUIT DIAGRAM

### DIFFERENTIAL  AMPLIFIER

<img width="940" height="614" alt="image" src="https://github.com/user-attachments/assets/b7b51220-5031-44de-be37-2d8e2962fa49" />

### TABULATION
| S.No | V1 (volts) | V2 (volts) | Vo (Theoretical) [V] | Vo (Practical) [V] |
|------|-------------|-----------|-----------------------|---------------------|
| 1    |             |           |                       |                     |
| 2    |             |           |                       |                     |
| 3    |             |           |                       |                     |


### PROCEDURE:
### Inverting and Non-inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.

### PROCEDURE:
### Differential amplifier

1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.

### RESULT:
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and their performance was successfully tested using op-amp IC 741.


