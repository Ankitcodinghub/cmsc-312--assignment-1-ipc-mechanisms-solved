# cmsc-312--assignment-1-ipc-mechanisms-solved
**TO GET THIS SOLUTION VISIT:** [CMSC 312- Assignment 1-IPC Mechanisms Solved](https://www.ankitcodinghub.com/product/cmsc-312-assignment-1-ipc-mechanisms-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;76215&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC 312- Assignment 1-IPC Mechanisms Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
<strong>&nbsp;</strong>

<strong>Question 1: Shared Memory (15 pts): </strong>

Write a simple program (example code available on BlackBoard; can be used as starting point) where processes synchronize via polling such that a process A prints out the strings of two other separate writing processes (B first and then C second) from shared memory. Process A needs to ‘wait’ by polling until B and C finish writing their strings to memory. Each of processes A, B and C should be in different code files. Create TWO different shared memory locations: (i) one for the storing the integer identifier and (ii) for storing the string.

Here is the sequence of events that needs to be implemented:

<ol>
<li>Process A writes to position 1 in memory and then waits until B and C completes</li>
<li>Process B writes the string “shared” into memory then signals A &amp; C that it is complete by writing into memory position 1 (note B should wait to write into position 1 until after process A writes into position 1 in memory)</li>
<li>Process C writes the string “memory” into memory and then signals A that it is complete by writing into memory position 1 (note C should wait until process B writes into position 1 in memory).</li>
<li>Process A is the last one to quit and prints out a “GoodBye” message.</li>
</ol>
&nbsp;

<strong>Question 2: Shared Memory (4 pts) </strong>

Create processes A, B and C from the same file using fork.

<h1>Question 3: Message Queues (6 pts)</h1>
Review the programs (spock.c and kirk.c). Answer (or discuss) questions listed below:

<ol>
<li>Discuss and evaluate what happens when you’re running both in separate windows and you kill one or the other.</li>
<li>Discuss what happens (and why) when you run two copies of kirk.</li>
<li>Discuss what happens (and why) when your run two copies of spock.</li>
</ol>
<h1>Remote Procedure Calls</h1>
Note that you will need a .rhost file under your home directory, it includes authority to the machine that the ‘server’ accepts clients &lt;hostname&gt; and from what login id &lt;loginid&gt;.

The format for a .rhost file is:

&lt;hostname1&gt; &lt;loginid1&gt;

&lt;hostname2&gt; &lt;loginid2&gt;

.

.

.

&lt;hostnameN&gt; &lt;loginidN&gt;

The instructor’s .rhost file may look like the below (login id is ‘pghosh’):

172.18.233.85 pghosh

Great RPC tutorial – Prof David Marshall @ Cardiff University (optional reading):&nbsp; <a href="http://www.cs.cf.ac.uk/Dave/C/node33.html">http://www.cs.cf.ac.uk/Dave/C/node33.html</a>

On rpcgen: <a href="http://www.cs.cf.ac.uk/Dave/C/node34.html#ch:rpcgen">http://www.cs.cf.ac.uk/Dave/C/node34.html#ch:rpcgen</a> (note: you may not have permission to print on another server’s Console for the printmessage &nbsp;&nbsp; tutorial).

&nbsp;

Wikipedia: <a href="https://en.wikipedia.org/wiki/Remote_procedure_call">http://en.wikipedia.org/wiki/Remote_procedure_call</a> (also check the link listed under ‘external link” to the SGI Tutorial “Introduction to RPC Programming”).

<h1>Question 4: Compute the median (10 pts)</h1>
Modify the average RPC programs (avg.x, avg_proc.c and ravg.c) so that it computes the <strong>median</strong> of a maximum of 100 numbers instead of the average of a maximum of 200 numbers. Test your program on the server.

The average RPC program is available on BlackBoard – a Makefile is included). Just type <strong>make</strong> (make sure you have an .rhost file under your home directory, and that ‘white’ space works correctly in the makefile (i.e., cut and paste the makefile will not work).

For the avg program: Run the RPC server program by starting the server: ./avg_svc

For the avg program: Run the RPC client program by: ./ravg 172.18.233.85 1 2 3 4

Try to use a different ‘port number’ than other classmates by changing the 22855 number given in the avg.x file. Suggestion, use the last 4 digits of you student ID number or some other unique number.

<h1>Question 5: Remote Procedure Calls (RPC): Echo RPC server (5 pts)</h1>
Write a program using remote procedure calls where the server simply echoes the word back to the client.

<h1>Question 6: Remote Procedure Calls (RPC): Sort numbers (10 pts)</h1>
Modify the average RPC program so that the server sends back a list of ‘sorted’ numbers to the client either in descending or ascending order given by an input parameter when invoking the client, e.g., the word “ascending:, “descending” (or just -a, -d).

&nbsp;
