Download Link: https://assignmentchef.com/product/solved-cse331-homework-4-minimips-design
<br>
In this assignment you will design a small version of MIPS processor. Its name is MiniMIPS. In MiniMIPS, there are 8 registers each holding 32 bit numbers. The instruction width is 16 bits instead of 32 bits in MIPS. There are two types of instructions in MiniMIPS.

R’-type:

<table width="601">

 <tbody>

  <tr>

   <td width="113">Op (4bits)</td>

   <td width="9"> </td>

   <td width="95">Rs (3bits)</td>

   <td width="28"> </td>

   <td width="76">Rt (3bits)</td>

   <td width="38"> </td>

   <td width="121">Rd(3bits)</td>

   <td width="121">Func(3bits)</td>

  </tr>

  <tr>

   <td width="113"> I’-type:</td>

   <td colspan="2" width="104"> </td>

   <td colspan="2" width="104"> </td>

   <td colspan="2" width="159"> </td>

   <td width="121"> </td>

  </tr>

  <tr>

   <td width="113">Op (4bits)</td>

   <td colspan="2" width="104">Rs (3bits)</td>

   <td colspan="2" width="104">Rt (3bits)</td>

   <td colspan="2" width="159">Imm (10bits)</td>

   <td width="121"> </td>

  </tr>

 </tbody>

</table>




The instructions of MiniMIPS are given in below table:

<table width="234">

 <tbody>

  <tr>

   <td width="78">Instr</td>

   <td width="78">Opcode</td>

   <td width="78">Func</td>

  </tr>

  <tr>

   <td width="78">AND</td>

   <td width="78">0000</td>

   <td width="78">000</td>

  </tr>

  <tr>

   <td width="78">ADD</td>

   <td width="78">0000</td>

   <td width="78">001</td>

  </tr>

  <tr>

   <td width="78">SUB</td>

   <td width="78">0000</td>

   <td width="78">010</td>

  </tr>

  <tr>

   <td width="78">XOR</td>

   <td width="78">0000</td>

   <td width="78">011</td>

  </tr>

  <tr>

   <td width="78">NOR</td>

   <td width="78">0000</td>

   <td width="78">100</td>

  </tr>

  <tr>

   <td width="78">OR</td>

   <td width="78">0000</td>

   <td width="78">101</td>

  </tr>

  <tr>

   <td width="78">ADDI</td>

   <td width="78">0001</td>

   <td width="78">XXX</td>

  </tr>

  <tr>

   <td width="78">ANDI</td>

   <td width="78">0010</td>

   <td width="78">XXX</td>

  </tr>

  <tr>

   <td width="78">ORI</td>

   <td width="78">0011</td>

   <td width="78">XXX</td>

  </tr>

  <tr>

   <td width="78">NORI</td>

   <td width="78">0100</td>

   <td width="78">XXX</td>

  </tr>

  <tr>

   <td width="78">BEQ</td>

   <td width="78">0101</td>

   <td width="78">XXX</td>

  </tr>

  <tr>

   <td width="78">BNE</td>

   <td width="78">0110</td>

   <td width="78">XXX</td>

  </tr>

  <tr>

   <td width="78">SLTI</td>

   <td width="78">0111</td>

   <td width="78">XXX</td>

  </tr>

  <tr>

   <td width="78">LW</td>

   <td width="78">1000</td>

   <td width="78">XXX</td>

  </tr>

  <tr>

   <td width="78">SW</td>

   <td width="78">1001</td>

   <td width="78">XXX</td>

  </tr>

 </tbody>

</table>




They all work similar to the actual MIPS Green Sheet. As immediate field is 10 bits you should extend it to 32 bits. Do not forget, only the instruction width and number of registers are different remaining part is same as MIPS. The register contents are 32 bits. Zero register is always 0. All other rules in MIPS are also rules of MiniMIPS.