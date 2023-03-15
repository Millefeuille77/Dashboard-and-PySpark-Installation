# Install pyspark on visual studio code

!pip install pyspark

# Install Apache Spark on Windows

Here is the instructions on how to install Apache Spark on Windows using terminal:
1. Download Apache Spark on https://spark.apache.org/downloads.html
    On my case, I used Pre-built for Apache Hadoop 2.7 package type
    ![apache_spark](/spark_guide/download_apache_spark.png)

2. Go to this github website https://github.com/steveloughran/winutils/blob/master/hadoop-2.7.1/bin/winutils.exe
    Download the winutils.exe for hadoop-2.7.1
    ![winutils](/spark_guide/download_winutils.png)

3. Extract the spark file with .tgz extension using 7-zip or Winrar.
![tgz](/spark_guide/extract_tgz.png)

4. Extract the spark file with .tar extension using 7-zip or Winrar.
![tar](/spark_guide/extract_tar.png)

5. Move the Apache Spark folder to the destination you want. For my case, I will move it to C:\
![move_spark](/spark_guide/move_to_C.png)

6. Move the winutils to Apache Spark's bin folder.
![move_winutils](/spark_guide/move_winutils.png)

7. Open the *edit the system environment variables* from using search bar in Windows
![edit_system](/spark_guide/edit.png)

8. Click *Environment Variables*
![environment](/spark_guide/edit_environment.png)

9. Click *New..* button on User variables.
![new](/spark_guide/click_new.png)

10. Write HADOOP_HOME on Variable name column, write Apache Spark folder path to the Variable value column.
![hadoop](/spark_guide/edit_hadoop.png)

11. Write SPARK_HOME on Variable name column, write Apache Spark folder path to the Variable value column.
![spark](/spark_guide/edit_spark.png)

12. Double click the *Path*.
![path](/spark_guide/path.png)

13. Click *New* button, paste the Apache Spark's bin directory.
![spark_bin](/spark_guide/spark_bin.png)

14. Open CMD, run **spark-shell** command
![spark_shell](/spark_guide/spark_run.png)