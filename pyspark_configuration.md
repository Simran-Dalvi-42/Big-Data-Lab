# Big Data
## Simran Dalvi (202318042)

Configuring PySpark on Windows involves a few steps. Here's a basic guide to help you get started:

1. **Install Java Development Kit (JDK)**:
   - PySpark requires Java to be installed on your system. Download and install the latest version of the JDK from the official Oracle website: [Java SE Downloads](https://www.oracle.com/java/technologies/javase-jdk15-downloads.html).
   - After installation, set the JAVA_HOME environment variable to point to the JDK installation directory. You can do this by going to Control Panel > System and Security > System > Advanced system settings > Environment Variables, then add a new system variable named JAVA_HOME and set its value to the JDK installation directory (e.g., `C:\Program Files\Java\jdk1.8.0_281`).

2. **Install Apache Spark**:
   - Download the latest version of Apache Spark from the official website: [Apache Spark Downloads](https://spark.apache.org/downloads.html).
   - Extract the downloaded Spark archive to a directory of your choice (e.g., `C:\spark`).

3. **Set SPARK_HOME Environment Variable**:
   - Similar to JAVA_HOME, you need to set the SPARK_HOME environment variable to point to the Spark installation directory. Set it to the directory where you extracted Spark (e.g., `C:\spark`).

4. **Add Spark's bin directory to PATH**:
   - To easily run Spark commands from the command line, add Spark's `bin` directory to your system's PATH environment variable. Append `C:\spark\bin` to the PATH variable.

5. **Install Python**:
   - If you haven't already, install Python on your system. You can download Python from the official Python website: [Python Downloads](https://www.python.org/downloads/).
   - Make sure to check the option to add Python to PATH during installation.

6. **Install PySpark**:
   - You can install PySpark using pip, Python's package manager. Open a command prompt and run:
     ```
     pip install pyspark
     ```

7. **Verify Installation**:
   - To verify that PySpark is correctly installed, open a command prompt and run:
     ```
     pyspark
     ```
   - This command should start the PySpark shell, and you should see the Spark logo and a Python prompt (`>>>`).

That's it! You have successfully configured PySpark on your Windows system. You can now start using PySpark for data analysis and processing.