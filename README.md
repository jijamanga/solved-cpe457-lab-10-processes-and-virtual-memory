Download Link: https://assignmentchef.com/product/solved-cpe457-lab-10-processes-and-virtual-memory
<br>
<strong>Lab Description:  </strong>When performing reverse engineering activities related to malware analysis, it is important to understand the components that make up the program. Particularly, malware that utilizes obfuscation will leverage dynamically allocated memory for deobfuscation, allowing the analyst better insight into program behavior.

<strong>Lab Environment: </strong>Students will need access to a Windows VM and be able to run Process Hacker 2.

<strong>Lab Files that are Needed: </strong>The lab binary.




<strong>Answer the Following Questions</strong>

Execute the sample program given to you then answer the following questions. When finished, press “CTRL-C” to terminate the process.<strong></strong>



<ol>

 <li>The program allocates memory at a virtual address of <strong>0xca0000</strong>:

  <ol>

   <li>What is the size of this allocation?</li>

   <li>What are the permissions?</li>

   <li>What is the status (or type)? What does that mean?</li>

   <li>What is the value written at the beginning of this allocation?</li>

   <li>What would a call to <em>VirtualAlloc</em> look like to make this memory allocation?</li>

  </ol></li>

 <li>The program allocates memory at a virtual address of <strong>0xab0000:</strong>

  <ol>

   <li>What are the permissions? How can a program use that differently than the previous allocation?</li>

   <li>Why can you not inspect the content of this memory allocation?</li>

   <li>What would a call to <em>VirtualAlloc</em> look like to make this memory allocation?</li>

  </ol></li>

</ol>

<ol start="3">

 <li>There is another allocation that has RWX permissions:

  <ol>

   <li>What does it appear that this allocation is used for?</li>

  </ol></li>

</ol>

<ol start="4">

 <li>What handles does this program have open? Describe the importance of each one (or speculate if it’s not clear why the program has that handle).</li>

</ol>


