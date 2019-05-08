# How-to-Get-IP-Address-browser-OS-of-User-in-PHP
<h1>user's Information </h1>
<hr>
Getting The Client Information (Client's IP Address,Operating System,Browser Name,Device Type) in PHP 
<h1> Initialize </h1>
<hr>
include('UserInformation.php'); <br>
//Or Use Require function <br>
require('UserInformation.php');<br>

<h1>Methods</h1>
<li> get_ip() </li>
<li> get_os()</li>
<li> get_browser() </li>
<li> get_device()</li>
<h1>get_ip()</h1>

<p> If you want to get the client IP Address, Use this Method, This Method will return Client IP Address</p>
 <h3>Example</h3>
 require('user_info.php');<br>
echo UserInfo::get_ip()
<h1>get_OS()</h1>
If you want to get the client Operating System Name, Use this Method, This Method will return Client Operating System
<hr>
<h3>Example</h3>
require('user_info.php');<br>
echo UserInfo::get_os();

<h1>get_Browser()</h1>
If you want to get the client's Browser Name, Use this Method, This Method will return Client's Browser Name

<hr>
<h3>Example</h3>

require('user_info.php');<br>
echo UserInfo::get_browser();

<h1> get_Device() </h1>

If you want to get the client's Device Type Then Use this Method, This Method will return Client's Device Type Name Such as Mobile,Tablet,Computer
<hr>
<h3>Example</h3>

require('user_info.php');<br>
echo UserInfo::get_device();


