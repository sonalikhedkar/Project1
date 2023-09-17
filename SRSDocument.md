<h1>CDAC Online Exam</h1>
<hr>

<h2>Document:</h2>

System Requirement Specification Document
<h2>Title</h2>
System Reqruiement Spefication for CDAC online exam poratl

<h2>Team</h2>
 Adminstrator, Students, Teachers, Staff, Head of Exam center, Technical Supporter,invigilator. 
<h2>Objective (Purpose):</h2>
For Conducting Examination in online mode it should be under security with well maintain network connection. During exam  if any intruption happens then it can be handle appropriately by Technical supporter.Maintaing proper atmosphere over CBT test by providing students proper required and under facilities.


<h2>Scope:</h2>
For students we have digital notepad option on Screen aling with rough pages.
Students can access review tab,clear tab, next along with sumbit tab.
Extra Desktop facility and power backup supply will provided for student while any technical issue.

 

<h2>Definitions:</h2>
CDAC:Centre of Development of Advanced Computing
CBT:Computer Based Test
VPN:Virtual Private Network


<h2>Functional Requirements:</h2>
<ul>
<li>Before start of exam some formalities like eye-Biomatric Scan,and security scanning for varifying students.</li>
<li>Students should enter in class with only transparent and light colour water bottle along with one pen and required documents.</li>
<li>Students are allowed to seat 15 minutes before start of exam for for reading instructions and filling input creadinal,like form number and date of birth </li>
<li>Before start of exam student should click on instruction button along with retry button for incorrect input.after reading instruction details check box will be tick marked by candidate</li>
<li>At sharp time student provided start the test button and student directly on the page of Question set</li>
<li>Questions have negative system along with four options for each questions.</li>
</ul>

<h4>Administrator Aspect</h4>
<ul>
  <li>Logging into the system</li>
  <li>Accepting registration of candidates</li>
  <li>Adding/editing/deleting the question</li>
  <li>Creating questions</li>
  <li>Posting Questions</li>
  <li>Posting multiple option to respective question</li>
  <li>Giving correct answer</li>
  <li>time limit</li>
  <li>Set Marks</li>
  <li>Negative Marking</li>
</ul>
<br>
<h4>Student Aspect</h4>
<ul>
 <li>Requesting registration</li>
 <li>Logging into the system</li>
 <li>Selecting the questing</li>
 <li>Appearing for the examination</li>
 <li>Reviewing the given response</li>
</ul>



<h2>NonFunctional Requirement:</h2>

<h3>Security:</h3>
While running assesment candidate not accesible for opening another tab and pc have installed VPN
so third party cannot access it.
Physical keyboard should be disable at the time of examination.


<h3>Reliability</h3>
<li>Powerbackup should be avaliable when power cut.</li>
<li>Site should not be crashed due to overload so the database should be huge and maintain properly.</li>
<li>Application should be stable.</li>
<li>To give an exam, on a browser ip address should be provided to the students without internet connection</li>



<h3>Portablility:</h3>
<li>The application should be run on any device whether it is windows,IOS,Redhat,ubuntu.</li>
<li>The application should also run on the android & IOS devices.</li>
<li>The application should be run on any browsers.</li>



<h3>Accessibility:</h3>
<li>Only admin have all the access of appliactions like schedule exam, can see all candidate marks, set time for exam, download pdf of marks, making changes in schedule,can see all the faculty members</li> 
<li>Students have only userName & Password to Attempt an exam</li>


<h3>Durability:</h3>

<li>In case of power cut while attempting an exam, have an backup & data should be stored so the
candidate cant loose their attempted answers.</li>
<li>Because of huge cloud database and security application will not be crashed.</li>



<h3>Availability</h3>
uptime: 24* 7 available 99.999%

<h3>Maintainability:</h3>
<li> Data base should be huge for examination system</li>
<li>Data should be store on cloud rather than on-premises.</li>


<h3>Efficiency:</h3>
<li>on Exam day, maximum number of users will able to give exam concurrently .System will manage all exam registration and candidate exam time limit control by the system admin.</li>
<li>Application should show same answer what candidate click while giving an exam.</li>
<li>Application should be efficient enough to meet all kinds of requirements as required by the
lecturers and students.</li>
<li>The application should not hang or lose its efficiency in any kind of
worse conditions.</li>

<h3>Modularity:</h3>
<li>Application will contain mainly three modules i.e. Admin Module,Faculty Module,Candidate Module.Inside admin module there will be different sub-modules like schedule exam,faculty member list,download response sheet of all candidate.Inside faculty module there will be allocated exam hall number. Inside candidate module there will be scheduled exam, result. </li>

<h3>safety</h3>
<li>To avoid security and safety breach candidate need to login with username and
password before they access the system. So the server check in the database username & password. Only registered candidate can access the system.</li> 


