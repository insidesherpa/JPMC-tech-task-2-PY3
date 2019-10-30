<p align="center">
<a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience" target="_blank">
<img src="https://insidesherpa-assets.s3-ap-southeast-2.amazonaws.com/icons/jpmorgan/github+repo+images/jpmc+github+img.png">
	</a>
</p>

<p align="center"> 
	<b><a href="#task">Task Overview</a></b>
	|
	<b><a href="#installation">Installation Instructions</a></b>
	| 
	<b><a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/88AisH7iuw3L5N5ig" target="_blank">Link to Module 2</a></b>

<h1> Introduction</h1> 
<b> Experience Technology at JP Morgan Chase </b>
<p>Try out what real work is like in the technology team JP Morgan Chase. Fast track to the tech team with your work.</p>

<h2 id="task"> Module 2 Task Overview </h2>
<p>Use JP Morgan Chase's frameworks and tools
Implement JP Morgan Chase’s Perspective open source code in preparation for data visualization</p>
<p> <b>Aim:</b>Take an incomplete setup of Perspective and make it work with the code from Task 1</p>

<ol>
	<li>Please clone this repository to start the task</li>
	<li>When new data feed is retrieved, the previous entry is re-entered into the table. Update the application so that the table does not have duplicated entries</li>
	<li>We want the react app to keep continuosly requests data from the python server. Currently, the data feed is called only once every time the 'Start Streaming' button is clicked. Change the application to continuously query the datafeed every 100ms when the 'Start Streaming' is clicked.</li>
	<li>Currently, the Perspective element only shows the data in table view after the data loads. Add Perspective configurations so that when the data is loaded, it shows the historical data of ask_price ABC in the Y line chart.</li>
	<li>Upload a git patch file as the submission to this task</li>	
</ol>

<h2 id="installation" >Installation</h2>

Please ensure you are using <b> python3+. </b>

Similar to Task 1, start the data feed server by running the python server

<code> python datafeed/server.py </code>

If you encounter an issue with `datautil.parser`, run this command: 

	pip install python-dateutil

If you don't have pip, you can install it from: https://pip.pypa.io/en/stable/installing/

Run <code>npm install</code> to start the React application.

To run the app in development mode, run <code>npm start</code> in the project directory. If you are using Windows, make sure to run your terminal/command prompt as administrator. It's okay to have audit warnings when installing/running the app.

If you don't have `npm`, you can install the recommended version alongside NodeJS from: https://nodejs.org/en/

Open http://localhost:3000 to view the app in the browser. The page will reload if you make edits.


