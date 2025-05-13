# dic-homework-4-median-filter-engine-solved
**TO GET THIS SOLUTION VISIT:** [DIC Homework 4-Median Filter Engine Solved](https://www.ankitcodinghub.com/product/dic-homework-4-median-filter-engine-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93293&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DIC Homework 4-Median Filter Engine Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1 Introduction

The median filter is a non-linear digital filtering technique, which is often used to remove noise from an image or signal. Such noise reduction is a typical pre- processing step to improve the results of later processing (for example, edge detection on an image). In this homework, please implement an median filter engine (MFE), which uses median filter to convolve the image. The specification and function of MFE circuit will be described in detail in the following section.

2 Design Specifications 2.1 Block overview

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 1 – System operation flow

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2.2 I/O Interface

Name I/O

clk I 1

reset I 1 ready I 1

</div>
<div class="column">
System clock signal. This system is synchronized with the positive edge of the clock.

Active-high asynchronous reset signal.

Grayscale image ready indication signal. When this

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Width

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Description

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 2">
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
busy

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
signal is high, the grayscale image memory is already prepared. MFE can start sending grayscale image address to obtain the data.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
System busy indication signal. When MFE receives high level ready signal and MFE is ready to start the calculation, this signal has to be set as high. After the calculation is completed and the result is completely output, set this signal to low and the testbench will start checking if the result is correct.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
iaddr

</div>
<div class="column">
O

O 14 I

I

O

O

O

</div>
<div class="column">
The signal for grayscale image memory address, which is used to request grayscale image pixel date.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
idata

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
data_rd

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
addr

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
data_wr

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
wen

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Input grayscale image pixel data signal, which represents an 8 bits unsigned integer. The testbench will send the pixel data according to the address iaddr indicates.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Result memory read data signal, which represents an 8 bits unsigned integer. This signal is used to send the result memory data to MFE circuit.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
14

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Result memory read/write address.

This signal indicates which address of the result memory will be read or written.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Result memory write data signal, which represents an 8 bits unsigned integer. The operation result of the MFE circuit is written to result memory using this signal.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Result memory write enable signal.

When this signal is low (read), the data with address addr in result memory is sent by data_rd.

When this signal is high (write), the data sent by data_wr is written to the address addr in result memory.

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
2.3 Function Description

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Input Image: 128x128x1

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
Zero padding Median Filter

Fig. 2 – Circuit operation flow

</div>
<div class="column">
Result image

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
The size of the input image in this system is 128×128, which is stored in the grayscale image memory. The correspondence between each pixel of the grayscale image and memory arrangement is shown in Figure 4. In the operation process, the MFE circuit uses the iaddr signal to send the address of requested image data (as shown in Figure 3. t1 time point). After the negative edge of each clock, the pixel data at requested address will be sent into the MFE circuit by the idata signal (as shown in figure 3. t2 time point).

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 3 – Timing diagram while reading grayscale image memory

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
8 bits

</div>
</div>
<div class="layoutArea">
<div class="column">
128 pixels

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 1

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 2

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 3

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Pixel Pixel Pixel Pixel 012 127

</div>
</div>
<div class="layoutArea">
<div class="column">
Pixel 128

Pixel 16256

</div>
<div class="column">
Pixel 129

Pixel 16257

</div>
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
16384 pixels

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 16381

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 16382

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Pixel 16383

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Fig. 4 – Arrangement mapping of input grayscale image and grayscale memory

</div>
</div>
<div class="layoutArea">
<div class="column">
Pixel 16383

</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
128 pixels

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
The first step of the system is to perform zero-padding on the image to avoid size-changing of the image when doing MFE operation. Then the padded image is convolved with median filter to obtain result image. After the calculation is finished, the busy signal should be set to 0, and then testbench will start the verification process.

Fig. 5 – The median filtering operation.

In the reading phase, the addr signal represents the memory address of result

memory to read and the data_rd signal will provide the data. wen signal should be set as low. The timing diagram of result memory reading operation is shown in figure 6.

In the writing phase, the addr signal informs the memory address to be written and the data_wr signal should provide the writing data. wen signal should be set as high. The timing diagram of result memory writing operation is shown in figure 7.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 6 – Timing diagram of reading result memory.

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 7 – Timing diagram of writing result memory.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3 Software Verification

You need to write a program to verify your circuit. You can write your program by using C, C++ and python. The requirements and functionality of this program should be as following:

<ol>
<li>Be able to read any jpg image. The file path for reading has to be ./image.jpg.</li>
<li>Convert RGB image to gray scale.</li>
<li>Resize the image into 128×128.</li>
<li>Add salt and pepper noise to the image.
(You may set the probability of the noise to 0.02.)
</li>
<li>Process median filtering to the image with noise.</li>
<li>Output the image with noise and the filtered image as img.dat and golden.dat,
respectively. The format of the output files should be the same as the img.dat and golden.dat which TA gave. The output file should be able to be read by the testbench and simulate correctly.
</li>
<li>Please name your program in the format: main.c, main.cpp or main.py.</li>
</ol>
4 Scoring

4.1 Functional Simulation [40%]

All of the result should be generated correctly, and you will get the following

message in ModelSim simulation.

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
4.2

</div>
<div class="column">
Gate Level Simulation [20%] 4.2.1Synthesis

Your code should be synthesizable. After it is synthesized in Quartus, a file named MFE.vo will be obtained.

4.2.2Simulation

All of the result should be generated correctly using MFE.vo, and you will get the following message in ModelSim simulation.

</div>
</div>
<div class="layoutArea">
<div class="column">
4.3

The performance is scored by the total logic elements, total memory bit, and

embedded multiplier 9-bit element your design used in gate-level simulation and the simulation time your design takes. The score will be decided by your ranking in all received homework. (The smaller, the better)

Scoring = (Total logic elements + total memory bit + 9*embedded multiplier 9- bit element) × (longest gate-level simulation time in ns)

4.4 Software Verification [20%]

All requirements have to be completed. TA will generate testing data with your

software program to verify your design. Please ensure your design can pass with the testing data which TA provided and the testing data generated by your software program.

</div>
</div>
<div class="layoutArea">
<div class="column">
Performance [20%]

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
5 Submission

5.1 Submitted files

You should classify your files into four directories and compress them to .zip

format. The naming rule is HW4_studentID_name.zip. If your file is not named according to the naming rule, you will lose five points.

*.v All of your Verilog RTL code

*.vo Gate-Level netlist generated by Quartus

*.sdo SDF timing information generated by Quartus

5.2 Report file

Please follow the spec of report. If your report does not meet the spec, you may

lose part of score. You are asked to describe how the circuit is designed as detailed as possible, and the flow summary result is necessary in the report. Please fill the field of total logic elements, total memory bits, and embedded multiplier 9-bit elements according to the flow summary of your synthesized design. And fill the field of gate-level simulation time according to the gate-level simulation result that Modelsim shows.

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
RTL category

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
Gate-Level category

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
Documentary category

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
*.pdf

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
The report file of your design (in pdf).

</div>
</div>
</td>
</tr>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
Verification category

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
*

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
The verification program.

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
5.3 Note

In this homework, you are allowed to modify the defined CYCLE in testbench

file. End_CYCLE, which decides the maximum cycles your circuit took to complete simulation, can also be modified according to your design. Please do not modify any other content of testbench.

</div>
</div>
</div>
