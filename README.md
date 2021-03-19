# Laboratorio 7
1. OBJETIVOS
- Objetivo General:
   
   - Comprender los números complejos y aprender a realizar operaciones matemáticas con ellos.
   
- Objetivos Específicos:
 
   - Determinar como los fasores pueden ser representados de forma rectangular y forma polar.
   - Aprender a como realizar operaciones de adición y sustracción de números complejos en forma rectangular.
   - Aprender a realizar operaciones de multiplicación y división de números complejos en forma polar.
   
2. MARCO TEÓRICO
   
   ![0001 (7)](https://user-images.githubusercontent.com/76133212/111713991-adba5b80-881e-11eb-96c4-a1c067b62d8a.jpg)

   
3. DIAGRAMAS
   
   ![Diagramas_Página_1](https://user-images.githubusercontent.com/75439689/111710876-8bbdda80-8818-11eb-8236-cf7d513eeb4d.jpg)
   ![Diagramas_Página_2](https://user-images.githubusercontent.com/75439689/111710877-8c567100-8818-11eb-9b9d-ff3349cbee6b.jpg)
   ![Diagramas_Página_3](https://user-images.githubusercontent.com/75439689/111710875-8bbdda80-8818-11eb-955f-d4af91d6de8c.jpg)

4. LISTA DE COMPONENTES
   
   ![image](https://user-images.githubusercontent.com/75439689/111701276-95d7dd00-8808-11eb-8ec1-c5b294974b2e.png)
   
   *Figura 4.1*

5. EXPLICACIÓN

   5.1. Desarrollo
     
   ![Laboratorio 7_Página_1](https://user-images.githubusercontent.com/75439689/111711013-ddfefb80-8818-11eb-943f-a72e0921ea39.jpg)
   ![Laboratorio 7_Página_2](https://user-images.githubusercontent.com/75439689/111711014-de979200-8818-11eb-8849-09f77f5e02fa.jpg)
   ![Laboratorio 7_Página_3](https://user-images.githubusercontent.com/75439689/111711016-de979200-8818-11eb-8f6e-e58fdd6447a6.jpg)
   ![Laboratorio 7_Página_4](https://user-images.githubusercontent.com/75439689/111711010-dd666500-8818-11eb-8546-843533ffa2a5.jpg)
   ![Laboratorio 7_Página_5](https://user-images.githubusercontent.com/75439689/111711043-eb1bea80-8818-11eb-918c-853c0c312978.jpg)
   ![Laboratorio 7_Página_6](https://user-images.githubusercontent.com/75439689/111711052-efe09e80-8818-11eb-9bac-8f6b2b546dca.jpg)

   5.2. Procedimiento
     
   - Ingresar a la plataforma dcaclab y seleccionar los materiales previamente listados.
   - Colocar la fuente de voltaje alterno con los valores requeridos (Vpp=20V y f=2.5kHz).
   - Dar los valores de la resistencia (R1=1kOhm y RL=2.2kOhm).
   - Conectar en serie la fuente de voltaje alterno, la resistencia R1 y la resistencia de carga RL e, dicho orden específico.
   - Con el osciloscopio, conectar las terminales del canal A en los extremos de la resistencia de carga RL.
   - Ajustar las perillas del canal A para poder visualizar mejor la función sinusoidal (Y-pos=0; VOLTS/DIV=3; TIME/DIV=0.1ms)
   - Con la función obtenida en el osciloscopio, observar y anotar el valor pico de la onda (Vp) junto con el tiempo que tarda en completar un ciclo (T: Período)
   - Desconectar el oscilocopio de la resistencia de carga y en su lugar conectar las terminales del multímetro en dihca resistencia, cuya perilla debe estar en 12V AC.
   - Observar y anotar el voltaje que tiene la resistencia de carga en el multímetro (Vrms).
  
   5.3. Comparación de Respuestas
  
    -  Cómo se puede observar, las operaciones hechas a mano y a calculadora son muy parecidas sin embargo tienen un pequeño margen de error:

      ![Error](https://user-images.githubusercontent.com/75439689/111712761-4a2f2e80-881c-11eb-8c6f-1b4ecbafd025.jpg)

6. MANUAL DE USUARIO

   - Para la comparación de datos entre la calculadora y los ejercicios hechos, se procederá a utilizar una calculadora en línea que transforma números complejos de forma polar a forma rectangular y viceversa. La calculadora se encuentra en el link: https://es.symbolab.com/solver/complex-number-calculator/
      ![image](https://user-images.githubusercontent.com/75439689/111711246-451cb000-8819-11eb-9e6d-eb26c9fb9eae.png)
  
   - En la barra blanca se ingresan los datos para las operaciones de números complejos, dentro de esta se deberá poner los numeros complejos como la i a la derecha en vez de la j a la izquierda, luego de poner todos los datos se presiona el botón Ir y se desplegará la respuesta abajo.
 
7. CONCLUSIONES

   - Saber como determinar los distintos tipos de voltaje que hay dentro de un circuito con C.A. es muy útil, ya que en la realidad hay que tomar otros valores además de los obvios, como es el voltaje de amplitud que no es más el voltaje pico que puede medir el osciloscopio; pero el voltaje utilizado es el voltaje RMS que representa el aproximadamente 70% y que es el voltaje de salida de resistor RL del circuito.
   - El simulador demuestra eficientemente que diferentes tipos de gráficas y combinaciones para medir el voltaje o corriente de una fuente C.A., tanto la división del tiempo que puede ser tomado en microsegundos o milisegundos, o las divisiones de los voltajes los cuáles se ven de una mejor manera dependiendo de la amplitud de voltaje.
   - Junto con los cálculos que nos brinda un osciloscopio se puede determinar a parte otros datos como son la frecuencia (la cual es hallada con la inversa del periódo) y la frecuencia angular (que se calcula con la fórmula de 2*π*f).
  
8. BIBLIOGRAFÍA

   - Floyd, T. L. (2007). Principios de circuitos eléctricos (Octava ed.).
