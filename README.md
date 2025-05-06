# cse308-assignment-2--editor-solved
**TO GET THIS SOLUTION VISIT:** [CSE308 Assignment # 2- Editor Solved](https://www.ankitcodinghub.com/product/cse308-assignment-2-editor-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97069&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE308 Assignment # 2- Editor Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Problem 1:

</div>
</div>
<div class="layoutArea">
<div class="column">
Suppose after successfully developing a Tea Garden Automation System (TeaGAS) in your Microcontroller sessional you have decided to apply for funding from Startup Bangladesh. In your lab project, you built the hardware around ATMega32 microcontroller. To apply for funding, you need to show how your product can be diversified. So, you have made a comprehensive plan to support a lot of options for different components. The specification of the system is below.

TeaGAS System Overview:

The system consists of a hardware device and a web server for the administrator. The leaf collectors put their load (baskets) on the device and swipe an ID card. The data is sent to the webserver. As the tea gardens are in remote areas, there is a storage component in the device to backup data when internet connection is not available. A display is also attached with the device. On the webserver the admin can add or remove leaf collectors and analyze the data received from the device. The major components of the system are:

<ol>
<li>Microcontroller/Microprocessor:You can choose any of ATMega32, Arduino Mega or Raspberry Pi around which the device will be built.</li>
<li>Weight Measurement: There are two options: Implement with load Sensor, Interface with a weight module.</li>
<li>Identification: ATMega32 and Arduino will use RFID card and Raspberry Pi will use NFC card.</li>
<li>Storage:If Raspberry Pi is used, storage will be provided along with it. ATMega32 and Arduino will be interfaced with SD card.</li>
<li>Display: Raspberry Pi will use touch screen display. Arduino and ATMega32 will be interfaced with LED and LCD display respectively.</li>
<li>Internet connection: Arduino and ATMega32 can choose from WiFi module or GSM module. Raspberry pi supports Ethernet too.</li>
<li>Controller: The touch screen of the raspberry pi doubles as a controller. Buttons need to be added for other two options.</li>
</ol>
In summary, building the device requires performing all the complex steps mentioned above one by one.

The web server can be developed with any of the three frameworks: Django, Spring and Laravel.

Your project partner who is a two times business case study award winner goes through the plan and suggests that you should not confuse the clients with all the unnecessary details and proposed the following four packages.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
ATMega32 with load sensor Arduino with weight module Raspberry Pi with load sensor Raspberry Pi with weight module

</div>
</div>
<div class="layoutArea">
<div class="column">
The client would choose a package, mention how the device would be connected to internet (WiFi, Ethernet or SIM card) and choose a framework for the web server.

Tasks:

<ul>
<li> &nbsp;Identify the design pattern(s) that can best capture the scenario above.</li>
<li> &nbsp;Implement the scenario in Java.</li>
<li> &nbsp;You just need to implement the structure. For example, you do not need to implement
how load sensor would measure weight. Just print “Measuring weight with Load Sensor”

on console.
</li>
<li> &nbsp;For demonstration user would be prompted to give input on console and based on the
choice, the details (name of the specific components) of the system would be shown on console.

Problem 2: [7 Points]

Assume that you are trying to implement syntax highlighting in a programming language editor. The editor currently supports 3 languages (C, CPP and Python). To perform this, you need to be able to parse the .c, .cpp and .py source files. Each language has specific rules of parsing. All the parsers implement an interface named Parser which contains all the functions required to parse a file. There is an Interface for the aesthetics (font, style, color etc.) of the source codes. The editor uses Courier New, Monaco and Consolas font for C, CPP and Python respectively. For simplicity assume that the other parameters (style and color of keywords) are set to default (Normal and blue). Also assume that multiple instances of the editor cannot run simultaneously.

Tasks:
</li>
<li> &nbsp;Identify the design pattern(s) that can best capture the scenario above.</li>
<li> &nbsp;Implement the scenario in Java</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ul>
<li> &nbsp;You just need to implement the structure. For example, you do not need to implement how the parsers would actually parse the source files.</li>
<li> &nbsp;For demonstration, user would input the filename with extension on console and see the selected parser and font name on screen.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
