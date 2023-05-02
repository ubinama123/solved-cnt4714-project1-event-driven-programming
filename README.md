Download Link: https://assignmentchef.com/product/solved-cnt4714-project1-event-driven-programming
<br>
<strong> </strong>

<strong>Title:</strong>  “Program Assignment 1:  Event-Driven Programming”

<strong>Objectives:</strong>  To practice event-driven programming using Java-based GUIs. To refresh your basic Java skills. To simulate (albeit at a very high-level) an enterprise application.




<strong>Description:</strong>  Develop a Java program that creates a standalone GUI application that simulates an e-store (we’ll call our store Nile Dot Com… we’re not quite as big as Amazon.com!)<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a> which allows the user to add in stock items to a shopping cart and once all items are included, total all costs (including tax), produces an invoice, and append a transaction log file.




Your program development must include the following steps:

<ol>

 <li>Create a main GUI containing the following components:

  <ol>

   <li>An area that allows the user to input data into the application along with the descriptive text that describes each input area.</li>

   <li>A total of six buttons as shown below with functionality as described below.</li>

   <li>As illustrated below, the various buttons on the interface are only accessible at certain points during a user’s interaction with the e-store.</li>

  </ol></li>

 <li>An input file named “txt”. This is a comma separated file which contains the data that will be read by the application when the user makes a selection.  Each line in this file contains three entries; an item id (a string), a quoted string containing the description of the item, and the unit price for one of the item (a double).  A sample file is provided for you on WebCourses.  Feel free to create your own input file.</li>

 <li>An output file (append only) named “txt” must be created that uniquely logs each user transaction with the e-store. The unique transaction id will be generated as a permutation of the date/time string when the transaction occurred (see below).</li>

</ol>




<strong>Restrictions: </strong>

Your source file shall begin with comments containing the following information:

<strong>/*  Name:  &lt;<em>your name goes here&gt;</em> </strong>

<strong> </strong>

<strong>Input Specification:</strong>  The file “inventory.txt” as described above (see example below as well).




<strong>Output Specification:  </strong>Output is to appear in the specified components of the GUI and various message         boxes   that      appear,            plus     the       contents           of         the

“transactions.txt” log file that will be generated.




<strong> </strong>




<strong>Deliverables: </strong>

<ul>

 <li>Submit a working copy of your source code (all .java files), including your inventory.txt file, via WebCourses no later than 11:59pm Sunday September 13, 2020.</li>

 <li>Include a file that contains screen shots, similar to those illustrated below, that shows your application in action as a user interacts with your e-store to purchase items.</li>

 <li>Include a screen shot of your “transactions.txt” file showing at least the last few transactions (similar to the one shown on the last page of this document).</li>

 <li>You can zip all of the above into a single folder.</li>

</ul>




<strong>Additional Information:</strong>

Shown below are example screen shots of the GUI to help illustrate how your application is to operate.

<ol>

 <li>Screen shot of the contents of an example “inventory.txt” file.</li>

</ol>




generates

file.

<ol start="3">

 <li>GUI after user specifies total number of items in the order and makes a selection for item #1, but before clicking the “Process Item” button.</li>

</ol>




<table width="184">

 <tbody>

  <tr>

   <td width="184">Information on the item selected/purchased has been extracted from the inventory file and written into the window on the line for item #1.  Note proper currency formatting.</td>

  </tr>

 </tbody>

</table>

<ol start="4">

 <li>GUI after user has selected the first item and clicked the “Process Item #1” button.</li>

</ol>




<ol start="5">

 <li>When the user clicks on the “Confirm Item #1” button, a confirmation information message appears on the screen.</li>

</ol>




<sub>                                                                                                                       </sub>user pressed the Process

Item button.  This is the only “error” you will need to catch.

<ol start="7">

 <li>User enters and processes (but has not yet confirmed) the next item in the order (which is the last one for this order).</li>

 <li>The GUI after the user has entered the information for all the items and confirmed the last item.</li>

 <li>When the user clicks the “View Order” button, the following message box should appear.</li>

 <li>When the user clicks the “Finish Order” button, the invoice message should be generated and displayed.</li>

</ol>

<table width="704">

 <tbody>

  <tr>

   <td width="496"></td>

   <td width="208">


    <table width="204">

     <tbody>

      <tr>

       <td width="204">The date and time are used to create the unique transaction id in the“transactions.txt” file.  For the invoice the format is“DD/MM/YY  HH:MM:SSTMZ”</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>







<ol start="11">

 <li>The transaction file after order shown above was finished. Note the unique transaction ids based on the date and time.</li>

</ol>







DDMMYYYYHHMM.




<ol start="12">

 <li>The transaction file after several orders have been completed. Note the unique transaction ids based on the date and time for every separate transaction.  This file shows seven separate transactions.</li>

</ol>

<a href="#_ftnref1" name="_ftn1">[1]</a> Source = https://www.wonderslist.com/top-10-largest-rivers/