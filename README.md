### General description

JSDroid can automatically detect JavaScript-related vulnerabilities in large-scale Android apps. The input of JSDroid is a deal of Android APK files. The tool is used to detect whether these Android apps contain any of the three JavaScript-related vulnerabilities. Accordingly, the output of JSDroid is a vulnerability detection report. In the folder "Samples", we also provide some APK files of Android apps to use/test our tool.

### Usage

#### Please follow the three steps to use JSDroid:

1.	Open the file JSDroid.jar. You can open the command line window and input the following command. Note that the parameter android-platforms represents the file path of android platforms in your machine.
java –jar JSDroid.jar android-platforms


2.	Choose APK files. By Clicking "Choose file directory", you can choose the directory where your APK files located. You can click "Show the APK list" to see all APK files in the directory. Here you can choose APK files.




















3.	Detect vulnerabilities. After clicking "Start detection", you can start the detection of JavaScript vulnerabilities in the chosen apps. The detection process can be seen from the command line window.














4.	Show results. After the detection is completed, an excel file of the detailed results is generated in the current directory. You can also turn to the "Results" panel and click the "results". A table of the brief results is shown in this panel. 

