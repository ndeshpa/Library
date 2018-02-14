# Library
FBLA Project

TO RUN THE APPLICATION AS AN EXECUTABLE ON WINDOWS: 
========================================================================================================
1. Open URL www.github.com/nimitadeshpande
2. Click on the "Library" Repository
3. Click on the "Library-1.0.exe" link
4. Click on the Download button
5. Once the file is downloaded, Double Click on the downloaded file on local machine
6. Click on the Install button  [Click Run Anyway if Windows Defender blocks the install]

NOTE: when run in this manner, any data changes such as new books/students, checkout/returns are NOT saved to the database files
If you want to save data updates, please run the application using the Libary.jar files as outlined below.

TO RUN THE APPLICATION USING LIBRARY.JAR ON WINDOWS: 
========================================================================================================
1. Ensure Java is installed on local machine and JAVA_HOME is set to point to the Java install directory 
2. Open URL www.github.com/nimitadeshpande
3. Click on the "Library" Repository
4. Click on the green "Clone or Download" button
5. On the prompt window, Click on "Download Zip" button. This downloac:\test\Library-master>java -jar Library.jar Book.txt Student.txt Teacher.txt Admin.txtds the application as Library-master.zip.
6. On the local machine, extract the Library-master.zip files to a local folder, say C:\test 
7. Open a Command Prompt window and cd C:\test 
8. type in runlibrary.bat OR run the command : java -jar Library.jar Book.txt Student.txt Teacher.txt Admin.txt
