Download Link: https://assignmentchef.com/product/solved-ee316-laboratory-07
<br>
<strong> </strong>

<strong>Characteristics of BJT and Amplification Behavior </strong>

<strong>Purpose </strong><strong> </strong>

The concept and characteristics of bipolar junction transistors (BJTs) is introduced. The basic concepts investigated for BJTs carries over into future labs, especially for MOSFETs. Both NPN and PNP constructions will be considered. Constants and variables relating to BJTs will be discussed and utilized in the procedure section.

<strong>Theoretical Background</strong>

<em>Construction </em>– A BJT has three parts: a collector region, a base region, and an emitter region. The base is also at times referred to as the channel if the BJT is field affected to allow current to flow through the collector and emitter. For an NPN the base is a P-type material (material with extra holes), the collector and emitter regions are an N-type material (material with extra electrons). For an NPN the emitter region contains a higher density of electrons than the collector which allows current to flow from the collector to the emitter. For a PNP the base is an N-type material, while the collector and emitter regions are P-type. For a PNP the emitter region contains a higher density of holes than the collector region allowing current to flow from the emitter to the collector. Thus, all BJTs have two junctions; one emitter-base and the other collector-base.




<em>Operation </em>– Current flows through the base region if the transistor is in “forward” or “reverse-active mode”. That is to say, DC current in the transistor is flowing through the base but only a small amount is coming from the base. “Forward-active mode” means the DC current is flowing in the direction of the base-collector junction and in the opposite direction of the base-emitter junction. “Reverse-active-mode” means the DC current is flowing opposite of the base-collector junction and in the same direction as the baseemitter junction. Maximum current flow is achieved in “saturation mode”. No current flows in “cut-off mode”.




<em>Appearance</em> –BJT circuit symbols vary so refer to the data sheet provided by the manufacturer for the specific BJT you are using. Some examples are provided below.

<strong>        NPN                                  PNP                                            Physical Appearance</strong>




<strong> </strong>

<strong> </strong>




<strong>Figure 7.1</strong> Output characteristic of BJT







<strong>Figure 7.2</strong> Common Collector Configuration* (a) PNP (b) NPN

BJT Kirchoff’s Voltage Law: <em>V</em><em><sub>CE </sub></em><em>V</em><em><sub>CB </sub></em><em>V</em><em><sub>BE</sub></em>

BJT Kirchoff’s Current Law: <em>I</em><em><sub>E </sub></em> <em>I</em><em><sub>C </sub></em><em>I</em><em><sub>B</sub></em>

Common Emitter Configuration: , , <sup></sup><sub>1</sub>

<em>II</em><sup></sup> and <sup></sup><sub>1</sub><sub></sub><sub></sub>

<em><sub>EB</sub></em>




<strong>Figure 7.3</strong> Common Collector Circuit

<strong>Procedure (Simulation and Experimental): </strong>

<ol>

 <li>Construct the circuit as shown in Fig. 7.3. Set R<sub>B</sub> = 300kΩ, R<sub>C</sub>=1kΩ and use the 2N3903 BJT transistor. Let V<sub>1</sub> = 4 V and then record the values of I<sub>B</sub>, I<sub>C</sub>, I<sub>E</sub>, β, and V<sub>CE </sub>while increasing the value of V<sub>2 </sub>from 0 V (<strong>do not measure I<sub>E</sub> in the lab</strong>). Repeat with V<sub>1</sub> = 6, 8, and 10 V. I<sub>B</sub> will not change much for each value of V<sub>1</sub>. To save time in the lab, only measure I<sub>B</sub> two or three times for each V<sub>1</sub> value (use the average). Table 7.1 is provided as an example for how to organize your data. Use your own judgment for how many data points to collect for each value of V<sub>1</sub>. Make sure to collect more data around the knee of the curves as shown in Fig. 7.4. For each curve stop collecting data once it is clear that I<sub>C</sub> is no longer increasing rapidly. Pick your last V<sub>2</sub> value so that your last V<sub>CE</sub> value is approximately the same for each curve.</li>

 <li>Draw the output characteristic curves as shown in Fig. 7.1 and 7.4 using your results. Evaluate the Q-point behavior of the NPN transistor for each characteristic curve (Note: Q-point is dependent on I<sub>B</sub>, I<sub>C</sub> and V<sub>CC</sub>). Identify the midpoint biasing Qpoint.</li>

 <li>Discuss your results in the conclusion section. Explain the information that is conveyed in your characteristic curve plot. Comment on the Q-point behavior with respect to I<sub>B</sub>, I<sub>C</sub> and V Discuss β and the significance of any tends you observe.</li>

</ol>




<strong>Figure 7.4 </strong>Characteristic curves for V<sub>1</sub> = 4V and V<sub>1</sub> = 6V. <strong>You will have 4 I<sub>B</sub> curves. </strong>

<strong>Table 7.1 </strong>(this table is incomplete and requires additional rows for V1 = 4, 6, 8, and 10 V)

<table width="639">

 <tbody>

  <tr>

   <td width="106"><strong>V<sub>1</sub> = 4V </strong></td>

   <td width="106"><strong>I<sub>B</sub> (</strong><strong>µA) </strong></td>

   <td width="106"><strong>I<sub>C</sub> (mA) </strong></td>

   <td width="106"><strong>I<sub>E</sub> (mA) </strong></td>

   <td width="106"><strong>V<sub>CE</sub> (V) </strong></td>

   <td width="106"><strong>β </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong>V<sub>1</sub> = 6V </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

  <tr>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

   <td width="106"><strong> </strong></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>BJT small signal amplification (Lab # 08): </strong>

<strong> </strong>

<strong>Figure 8.1</strong> Common Collector Circuit

<strong>Procedure (Simulation and Experimental): </strong>

<ol>

 <li>Apply a 500 mV peak-to-peak sinusoidal input signal at the given range of frequencies (see Table 8.1) to the circuit in Fig. 8.1. Use R<sub>B</sub> = 300 kΩ, R<sub>C </sub>= 1kΩ, C<sub>1</sub> = C<sub>2</sub> = 0.1 nF, V<sub>CC </sub>= 16 V, and a 2N3903 BJT.</li>

 <li>You may use a Bode plotter to find gain and then calculate V<sub>out</sub> from gain. Alternatively use an oscilloscope to find V<sub>out</sub> and then calculate gain (the Bode plotter is easier and faster). Plot gain in dB as a function of frequency. Make sure to label your axes and make sure that the frequency axis (the x-axis) is in log scale.</li>

 <li>Provide oscilloscope displays of the input and output waveforms at the lowest and highest frequencies. Explain why the output is clipped at the higher frequencies. Identify (approximately) the frequency where clipping begins to occur. What changes to the circuit can be made to ensure no clipping occurs for the given input signal and frequency range (you may change component values and/or add or remove resistors and capacitors)? What happens to the gain of the circuit based on your answer to prevent clipping?</li>

</ol>













<strong>Table 8.1 </strong>

<table width="559">

 <tbody>

  <tr>

   <td width="142"><strong>Frequency </strong></td>

   <td width="198"><strong>Vout </strong></td>

   <td width="219"><strong>Gain (dB) </strong></td>

  </tr>

  <tr>

   <td width="142">10</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">30</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">60</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">100</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">200</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">500</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">1 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">2 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">5 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">10 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">15 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">20 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">50 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">75 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">100 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">150 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">200 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">500 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">750 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">1 MHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">1.5 MHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">2.0 MHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

 </tbody>

</table>


