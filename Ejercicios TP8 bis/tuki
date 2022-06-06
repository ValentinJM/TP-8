# Ejercicio 1: Determinar e imprimir la cantidad de elementos positivos, la de negativos y la de ceros, de un vector V de N elementos enteros, con un diagrama de flujo de datos

```mermaid
stateDiagram-v2
state "Input vector de N >= 1 elementos" as IN1
state "Entero positivos, negativos, ceros" as DEC1
state "Entero contador = 0" as DEF1
state "if (contador < N)" as COND1
state "if (vector[contador] > 0)" as COND2
state "if (vector[contador] < 0)" as COND3
state "positivos += 1" as RES1
state "negativos += 1" as RES2
state "ceros += 1" as RES3
state "contador += 1" as RES4
state "Imprimir: positivos, negativos, ceros." as OUT1
    Main --> IN1
    IN1 --> DEC1
    DEC1 --> DEF1
    DEF1 --> COND1
    COND1 --> COND2 : si
    COND1 --> OUT1 : no
    COND2 --> COND3 : no
    COND2 --> RES1 : si
    RES1 --> COND3
    COND3 --> RES2 : si
    COND3 --> RES3 : no
    RES2 --> RES4
    RES3 --> RES4
    RES4 --> COND1
    OUT1 --> End
    
    
    
```
