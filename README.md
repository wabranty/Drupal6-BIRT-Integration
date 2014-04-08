<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">

<head>
<meta content="en-us" http-equiv="Content-Language" />
<meta content="text/html; charset=utf-8" http-equiv="Content-Type" />
<title>Drupal 6/BIRT Integration</title>
<style type="text/css">
.style1 {
	border-width: 0px;
}
.style2 {
	text-align: right;
}
</style>
</head>

<body>

<h1>Integrating Drupal 6 with BIRT 3.7.2</h1>
<p>This page describes how to display BIRT reports in Drupal 6. The reason you 
want to do this is that BIRT reports can access a wide variety of data sources 
and produce attractive reports that can be displayed as Drupal content. You can 
also create BIRT reports that read web feeds and display those in a more 
readable and complex format.</p>
<p>This tutorial gives an overview of the Drupal/BIRT integration.</p>
<p><a href="DrupalBIRTOne/DrupalBIRTOne.html" target="-blank">
<img alt="First Tutorial for Drupal 6/BIRT" class="style1" height="359" src="DrupalBIRTOne/FirstFrame.png" width="640" /></a></p>
<h2>Instructions for setting up the development environment and the BIRT Report 
Designer</h2>
<ol>
	<li>I downloaded
	<a href="http://wiki.alfresco.com/wiki/Download_Community_Edition">Alfresco 
	Community 4</a> and <a href="http://www.acquia.com/downloads">Acquia Dev 
	Desktop</a> (Drupal 6 version) to set up my development environment.</li>
	<li>Download the <a href="http://download.eclipse.org/birt/downloads/">BIRT 
	Report Designer</a> All-In-One (version 3.7.2). It may be 	something with my laptop 
	(Gateway, 64-bit, Windows 7 Ultimate) but I had better success running the 
	32-bit version for Windows than I did with the 64-bit.</li>
	<li>Follow the install instructions. I did have some trouble getting Eclipse 
	to recognize my JDK so I downloaded a 32-bit version of Java 6 and then 
	copied the contents into a folder called “jre”. I placed this folder into the 
	main directory of Eclipse. Worked fine after that. The purpose of this 
	application is to design your reports for BIRT.</li>
	<li>You will also want to install the BIRT runtime in your Tomcat/webapps 
	directory of your Alfresco installation. Go back to the Eclipse Downloads 
	page and get the <a href="http://download.eclipse.org/birt/downloads/">BIRT 
	Runtime Release Build 3.7.2</a>. Follow the install instructions.</li>
	<li>Download and extract the
	<a href="http://www.birt-exchange.com/be/overlay/MIP_Drupal.html">BIRT 
	Drupal module</a> (click on the title and then register to download). In the unzipped file, extract the &quot;birtos.zip&quot; file. Copy 
	the &quot;birtos&quot; folder (inside the extracted folder) to your sites/all/modules 
	folder of your Acqua Dev Desktop installation.</li>
</ol>

<p>The second tutorial describes how to set up the Drupal 6/BIRT integration. 
You will need this updated
<a href="http://billbrantley.com/DBDemos/JavaBridge_update.zip">JavaBridge file</a> 
which has the updated BIRT Report Runtime (3.7.2).</p>
<p>
<a href="DrupalBIRTTwo/DrupalBIRTTwo.html" target="_blank'>
<img alt="Tutorial Two of the Drupal 6/BIRT integration" height="359" src="DrupalBIRTTwo/FirstFrame.png" width="640" class="style1" /></a></p>
<h2>Using BIRT Reports to Display XML Feeds in Drupal 6</h2>
<p>
<a href="DrupalBIRTThree/DrupalBIRTThree.html" target="_blank">
<img alt="Tutorial Three of Drupal 6/BIRT integration" height="359" src="DrupalBIRTThree/FirstFrame.png" width="640" class="style1" /></a></p>
<h2>Using Javascript to Allow the User to Filter Reports</h2>
<p>
<a href="DrupalBirtFour/DrupalBirtFour.html" target="_blank">
<img alt="Tutorial Four of Drupal 6/BIRT integration" height="359" src="DrupalBirtFour/FirstFrame.png" width="640" class="style1" /></a><br /><br />
The files used in the above tutorial:<br />
<a href="DrupalBirtFour/Customers_Select.rptdesign">Customers_Select.rptdesign</a><br />
<a href="DrupalBirtFour/Customers_Select2.rptdesign">Customers_Select2.rptdesign</a><br />
<hr />
<h2><a href="http://www.eclipse.org/birt/phoenix/tutorial/">BIRT Video Tutorials</a></h2>
<h2>BIRT References</h2>
<ul>
	<li><span style="COLOR: #1f497d">
	<a href="http://www.amazon.com/BIRT-Field-Edition-Eclipse-Series/dp/0321733584/ref=sr_1_1?ie=UTF8&amp;qid=1330699057&amp;sr=8-1">
	<strong>BIRT: A Field Guide (3</strong><sup><strong>rd</strong></sup><strong> 
	Ed)</strong></a></span></li>
	<li><span style="COLOR: #1f497d">
	<a href="http://www.amazon.com/Integrating-Extending-Edition-Eclipse-Series/dp/0321772822/ref=sr_1_2?ie=UTF8&amp;qid=1330699057&amp;sr=8-2">
	<strong>Integrating and Extending BIRT (3</strong><sup><strong>rd</strong></sup><strong> 
	Ed)</strong></a></span></li>
</ul>
<h2>If you want to update JavaBridge with the latest BIRT Report Runtime Engine</h2>
<iframe width="420" height="315" src="http://www.youtube.com/embed/79aXbyx52kY" frameborder="0" allowfullscreen></iframe><br />
<iframe width="420" height="315" src="http://www.youtube.com/embed/fb5iSBrw6O4" frameborder="0" allowfullscreen></iframe><br />
<h2>
<a href="http://www.birt-exchange.org/org/devshare/deploying-birt-reports/743-calling-birt-from-php/">
Important: Update to the update videos </a>(so that JavaBridge will run BIRT 
Runtime 3.7.x).</h2>

<h5 class="style2">A Not Associated With Saucers Production</h5>

</body>

</html>
