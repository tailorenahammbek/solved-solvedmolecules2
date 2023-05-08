Download Link: https://assignmentchef.com/product/solved-solvedmolecules2
<br>
In this task, you are going to write a program that conducts analysis on a large input data set. The problem is defined as follows.

In an experiment a beam of molecules is observed along a straight line.![f](https://github.com/GoldOne/See-pei-pei/blob/master/fig_bed/molecules.png)

The information recorded for each molecule in the experiment include:&lt;table&lt;tr&lt;tdposition&lt;/td &lt;tr&lt;tdspeed&lt;/td&lt;tr&lt;tdEnergy&lt;/td&lt;tr&lt;td&lt;bfingerprint&lt;/b&lt;/td&lt;td<b> Note that due to accuracy issue of the experiment setup, two molecules may be observed at the same position.</b>

**The data to be processed could be huge (more than 10 millions) and thus you have to use a binary search tree as the underlying data structure.**

**Experimental Error: It is discovered that each molecule can be identified by a sequence of 8 characters (e.g. ACACDDEF) and that no two molecules should have the same fingerprint (just like human beings). However, in the experiment, the machine in the laboratory may produce data of molecules of the same fingerprint. The researchers thus conclude that the machine is not 100% accurate. To prevent the experiment result from being affected, the data of molecules of the same fingerprint has to be discarded before a report is generated.**

Definition 1: A molecule is **lonely** if there is no adjacent molecules that is within 100 nm.

Your task is to report information related to lonely molecules in the experiment. **Remember, the report generated should depend on the molecules that have unique fingerprint. That is, your program should ignore all the input data the contains the same fingerprint.**

A Sample data file is given below![f](https://github.com/GoldOne/See-pei-pei/blob/master/fig_bed/sample%20data%20for%20molecules2.png)

All data file starts with a symbol # and ends with another symbol #. In the above file, information of 4 molecules are recorded. For example, the first molecule is at the position 23.6 nm with a speed of 3.3 ms and energy of 28 mj. **The fingerprint of the first molecule is ABCDABCD. Since the second, third and fourth molecules share the same fingerprint; they should not be used in the report generation. Thus, the first molecule will be regarded as a lonely molecule. (Since the second molecule will not be used in the report generation.)**

Your program contains the following user interface.&lt;table&lt;tr&lt;tdI&lt;/td&lt;tr&lt;tdN&lt;/td discarded)&lt;/b&lt;/td&lt;/tr&lt;tr&lt;tdR&lt;/td1. total number of molecules &lt;b(excluding those that have been discarded)&lt;/b&lt;/br2. number of lonely molecules&lt;/br3. average speed of the lonely molecules&lt;/br4. average energy of the lonely molecules&lt;/td&lt;/tr&lt;tr&lt;tdq&lt;/td

There is no upper limit on the total number of molecules. The user may repeatedly import the same or different data files before issuing the command R. The user could also issue command R before and after importing another file. You can safely assume all the files are error-free.

All commands are case sensitive. If the user enters an invalid input, your system should prompt the user to re-enter. You can assume the user will never enter anything longer than 100 characters.


