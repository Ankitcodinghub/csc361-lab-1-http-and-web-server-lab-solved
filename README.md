# csc361-lab-1-http-and-web-server-lab-solved
**TO GET THIS SOLUTION VISIT:** [CSC361 LAB 1 (HTTP AND WEB SERVER LAB)  Solved](https://www.ankitcodinghub.com/product/csc361-lab-1-http-and-web-server-lab-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;42508&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC361 LAB 1 (HTTP AND WEB SERVER LAB)&nbsp;&nbsp;Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<table width="789">
<tbody>
<tr>
<td width="789">LAB 1 (HTTP AND WEB SERVER LAB)

PROBLEM STATEMENT

In this lab, you will learn the basics of socket programming using TCP connections in Python:

how to create a socket,

bind it to a specific address and port, as well as send and receive a HTTP packet.

You will also learn some basics of HTTP header format.

You will develop a web server that handles one HTTP request at a time. Your web server should accept and parse the HTTP request, get the requested file from the server’s file system, create an HTTP response message consisting of the requested file preceded by header lines, and then send the response directly to the client. If the requested file is not present in the server, the server should send an HTTP 404 Not Found message back to the client. You are also <strong>required</strong> to implement a simple client in Python after you have completed your server.

HTTP PROTOCOL

<table width="110">
<tbody>
<tr>
<td width="19"></td>
<td width="77">info.cern.ch</td>
<td width="14"></td>
</tr>
<tr>
<td colspan="3" width="110">If-Modified-Since:</td>
</tr>
</tbody>
</table>
Start CSC361-VM , use telnet into&nbsp; with port 80 and request the world’s first HTML page. Now, do it again with the&nbsp; header line in your request, so that the server returns a status 304 Not Modified . (<strong>Note:</strong> Follow the steps shown below.)
</td>
</tr>
</tbody>
</table>
&nbsp;

<table width="789">
<tbody>
<tr>
<td width="789">Determine the IP address of the host that is running the server (e.g., 128.238.251.26 ). Then run a working version of your server program server.py . From another host, open a browser and provide the corresponding URL. For example:

<table width="639">
<tbody>
<tr>
<td width="639">1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;http://128.238.251.26:6789/hello.html</td>
</tr>
</tbody>
</table>
hello.html is the name of the file you placed in the server directory, which is also included. <strong>Note </strong>also the use of the port number after the colon. You need to replace this port number with whatever port you have chosen in your server code. In the above example, we have used the port number 6789 . The browser should then display the contents of hello.html . If you omit :6789 , the browser will assume port 80 and you will get the web page from the server only if your server is listening at port 80 . (This is <strong>not</strong> recommended.) Then try to get a file that is not present at your server. You should get a 404 Not Found message.

&nbsp;

RUNNING THE CLIENT

Instead of using a browser, write your own HTTP client to test your server. Your client will connect to the server using a TCP connection, send an HTTP request to the server, and display the server response as an output. You can assume that the HTTP request sent is a GET method. The client should take command line arguments specifying the server IP address or host name, the port at which the server is listening, and the path at which the requested object is stored at the server. The following is an input command format to run the client.

<table width="639">
<tbody>
<tr>
<td width="639">1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;client.py 128.338.251.26 6789 hello.html</td>
</tr>
</tbody>
</table>
WHAT TO HAND IN

You will hand in the complete client/server code along with the screen shots of your client. Please verify that you actually receive the contents of the HTML file from the server. Submit your solutions as attachments to Connex.

EVALUATION
</td>
</tr>
</tbody>
</table>
&nbsp;

<table width="789">
<tbody>
<tr>
<td width="789">You must demonstrate your working code inside the CSC361-VM using <strong>Wireshark</strong>. Using

<table width="110">
<tbody>
<tr>
<td colspan="2" width="77">CSC361-VM</td>
<td width="33"></td>
</tr>
<tr>
<td width="56">not just</td>
<td colspan="2" width="54">127.0.0.x</td>
</tr>
<tr>
<td width="56"></td>
<td width="21"></td>
<td width="33"></td>
</tr>
</tbody>
</table>
, the server and the client must use different IP addresses and port numbers, i.e.,

. Your Wireshark demo must capture all related packets, including ARP, TCP

and HTTP. Test your HTTP client/server using the provided hello.html .

You are <strong>also</strong> required to answer a few questions related to this lab during evaluation in the lab (ECS 360).

Our evaluation scheme is:

(50%) Correctness of Python code

(20%) Wireshark demo

(30%) Questions and Answers (at least 5 questions)
</td>
</tr>
</tbody>
</table>
&nbsp;
