# JP-morgan_chase-virtual-internship
<br>
<p align="center">
<a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience" target="_blank">
<img src="https://insidesherpa-assets.s3-ap-southeast-2.amazonaws.com/icons/jpmorgan/github+repo+images/jpm+gitub+.png"></a>
</p>

<p align="center"> 
	<b><a href="#task">Task Overview</a></b>
	|
	<b><a href="#installation">Installation Instructions</a></b>
	| 
	<b><a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/gtAhtcvke9AFCzqME" target="_blank">Link to Module 1</a></b>		
	| 
	<b><a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience">JP Morgan Chase & Co Software Engineering Virtual Experience</a></b>
</p>

<h1> Introduction</h1> 
<b> Experience Technology at JP Morgan Chase & Co</b>
<p>Try out what real work is like in the technology team at JP Morgan Chase & Co. Fast track to the tech team with your work.</p>

<h2 id="task"> Module 1 Task Overview </h2>
<p>Interface with a stock price data feed and set up your system for analysis of the data</p>
<p> <b>Aim:</b> We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.</p>

<ol>
	<li>Please clone this repository to start the task</li>
	<li>Adjust the getRatio, getDataPoint and main functions</li>
	<li>Bonus: Pass all unit tests and add more to cover edge cases</li>
	<li>Upload a git patch file as the submission to this task</li>
	
</ol>

<h2 id="installation" >Set up / Installation</h2>

<p>In order to get the server and client application code working on your machine, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m1_v6.pdf">follow the setup here</a></p>


<h2>How to Run</h2>
To start the server, run

	python server.py

this will create random market called 'test.csv' in your working directory if one does not already exist.

If you encounter an issue with `datautil.parser`, run this command: 

	pip install python-dateutil

If you don't have pip yet, you can install it from: https://pip.pypa.io/en/stable/installing/

To start the example client, run:

	python client.py

To unit test the example client, run:
	python client_test.py

<h2>How to request from the server using curl</h2>
<!--See also [client.py](https://github.com/texodus/exchange_simulator/blob/master/client.py)-->
Query:

	$ curl 'http://localhost:8080/query?id=1'
	{"id": "1", "top_ask": {"price": 129.18, "size": 70}, "timestamp": "2016-08-06 12:32:11.821574", "top_bid": {"price": 128.79, "size": 61}}
It is the virtual internship conducted by <b>JP-Morgan</b><br>
In this virtual Intership we will go through various Hands on expirence on real life industry usecases.

