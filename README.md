## :gear: HALF ADDER (Meio Somador)

- Soma dois bits (A e B).  
- Gera duas saídas:
  - **S (Soma)** — resultado da soma binária.  
  - **C (Carry)** — transporte para o próximo bit quando A e B são 1.  
- Implementado com portas **XOR** e **AND**.  
## :gear: FULL ADDER (Somador Completo)

- Soma três bits: A, B e **Carry In** (vai-um anterior).  
- Saídas:
  - **S (Soma)** — resultado da soma.  
  - **Cout (Carry Out)** — transporte para o próximo bit.  
- Pode ser construído com **dois Half Adders + uma porta OR**.  
## :computer: 4-BIT ADDER

- Formado por **quatro Full Adders** conectados em sequência.  
- Cada Full Adder soma um par de bits (A[i], B[i]) e o carry da etapa anterior.  
- O primeiro somador recebe **Carry In = 0**.  
- O último gera o **Carry final (Cout)**.  


---

## :man_technologist: Autor

**Kayky Jesus**  
:briefcase: Estudante de Engenharia e entusiasta de sistemas digitais.  
:e_mail: [kayky@edu.unifil.br](mailto:kayky@edu.unifil.br)
