I. Get ready:
1. Java must be installed and available from the command line. To check this, open a command prompt (Windows: Start > Run > cmd or Mac: Applications > Utilities > Terminal) and type: 
"java -version".

If you see something like the following, you have Java installed:
java version "1.6.0_11"
Java(TM) SE Runtime Environment (build 1.6.0_11-b03)
Java HotSpot(TM) Client VM (build 11.0-b16, mixed mode, sharing)

If you see something like the following, you have to install Java:
C:\current_location>java -version
'java' is not recognized as an internal or external command, operable program or batch file.

Follow this link to check installed Java on your machine: http://java.com/en/download/installed.jsp?detect=jre&try=1


2. Download the ZIP file and extract its contents to your hard disk.

3. In the unzipped "Datashop Student-step Rollup Export Tool" directory, find file "build.properties" and open it with a plain text editor. 
On Windows
Replace "C:/FOLDER_NAME/FOR/DATASHOP_STUDENT_STEP_ROLLUP_EXPORT_FILE/" with the folder name where you saved the student-step rollup export file, e.g. C:/Datashop Student-step Rollup Export Tool/export files/
Replace "DATASHOP_STUDENT_STEP_ROLLUP_EXPORT_FILE.txt" with the name of student-step rollup export file, e.g. ds1000_student_step_All_Data_1234_2015_0123_123456.txt

On Mac
Replace "/FOLDER_NAME/FOR/DATASHOP_STUDENT_STEP_ROLLUP_EXPORT_FILE/" with the folder name where you saved the student-step rollup export file, e.g. /Parent-Folder/Datashop Student-step Rollup Export Tool/export files/
Replace "DATASHOP_STUDENT_STEP_ROLLUP_EXPORT_FILE.txt" with the name of student-step rollup export file, e.g. ds1000_student_step_All_Data_1234_2015_0123_123456.txt


II. Run:

1. Open a command prompt and navigate to the unzipped directory, which should contain both "dist" and "extlib" directories. (The command to navigate on Windows is: "cd c:\path\to\unzipped\directory\Standard BKT Tool" or on MAC is: cd /path/to/unzipped/directory/Standard BKT Tool)

2.Enter the following on a single line: 
For Windows:
java -jar dist\lfa-5.0-DS-external-tools.jar

For MAC:
java -jar dist/lfa-5.0-DS-external-tools.jar
