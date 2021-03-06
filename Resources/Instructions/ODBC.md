<img src="../Images/management.png" align="right">
<h1>Campaign Optimization:
Set up Connection between SQL Server and PowerBI  </h1>

Follow the instructions below to set up a connection between your SQL Server database and PowerBI.  Perform these steps after you have created the `Campaign` database.

<ol>
<li>	Push the <code>Windows</code> key on your keyboard</li>
<li>	Type <code>ODBC</code> </li>
<li>	Open the correct app depending on what type of computer you are using (64 bit or 32 bit). To find out if your computer is running 32-bit or 64-bit Windows, do the following:</li>
<ol><li>	Open System by clicking the <code>Start</code> button, clicking <code>Control Panel</code>, clicking <code>System and Maintenance</code>, and then clicking <code>System</code>.
<li>.	Under System, you can view the system type</li></ol></li>
<li>	Click on <code>Add</code>
  <br/>
<img src="../Images/odbc1.png" width="50%" >
</li>
<li>	Select <code>Server Native Client 11.0</code> and click finish
   <br/>
<img src="../Images/odbc2.png" width="50%" >
 </li>
<li>	Under Name, Enter <code>Campaign</code>. Under Server enter the MachineName from the SQL Server logins set up section. Press <code>Next</code>.
   <br/>
<img src="../Images/odbc3.png" width="50%" >
</li>
<li>	Select <code>SQL Server authentication</code> and enter the credentials you created in the SQL Server set up section. Press <code>Next</code>
   <br/>
<img src="../Images/odbc4.png" width="50%" >
</li>
 

<li>	Check the box for <code>Change the default database to</code> and enter <code>Campaign_Management</code>. Press 
<code>Next</code>.
   <br/>
<img src="../Images/odbc5.png" width="50%" >
</li>
<li>Press <code>Finish</code>
  <br/>
<img src="../Images/odbcfinish.png" width="50%" > 
</li>
<li>Press <code>Test Data Source</code>
  <br/>
<img src="../Images/odbc6.png" width="50%" >
</li> 
<li>	Press <code>OK</code> in the new popover. This will close the popover and return to the previous popovers.
   <br/>
<img src="../Images/odbc7.png" width="50%" >
</li>
<li>	Now that the Data Source is tested. Press <code>OK</code>
   <br/>
<img src="../Images/odbc8.png" width="50%" >
</li>
<li>	Finally, click <code>OK</code> and close the window 
   <br/>
<img src="../Images/odbc9.png" width="50%">
</li>
</ol>

You are now ready to use this connection in PowerBI by following the [instructions here](Visualize_Results.md).
	