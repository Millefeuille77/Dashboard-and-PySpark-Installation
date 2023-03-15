# Install pyspark on visual studio code

!pip install pyspark

# Install Apache Spark on Windows

Here is the instructions on how to install Apache Spark on Windows using terminal:
1. Download Apache Spark on https://spark.apache.org/downloads.html <br>
    On my case, I used Pre-built for Apache Hadoop 2.7 package type <br>
    ![apache_spark](/spark_guide/download_apache_spark.png) <br>

2. Go to this github website https://github.com/steveloughran/winutils/blob/master/hadoop-2.7.1/bin/winutils.exe <br>
    Download the winutils.exe for hadoop-2.7.1 <br>
    ![winutils](/spark_guide/download_winutils.png) <br>

3. Extract the spark file with .tgz extension using 7-zip or Winrar. <br>
![tgz](/spark_guide/extract_tgz.png) <br>

4. Extract the spark file with .tar extension using 7-zip or Winrar. <br>
![tar](/spark_guide/extract_tar.png) <br>

5. Move the Apache Spark folder to the destination you want. For my case, I will move it to C:\ <br>
![move_spark](/spark_guide/move_to_C.png) <br>

6. Move the winutils to Apache Spark's bin folder. <br>
![move_winutils](/spark_guide/move_winutils.png) <br>

7. Open the *edit the system environment variables* from using search bar in Windows <br>
![edit_system](/spark_guide/edit.png) <br>

8. Click *Environment Variables* <br>
![environment](/spark_guide/edit_environment.png) <br>

9. Click *New..* button on User variables. <br>
![new](/spark_guide/click_new.png) <br>

10. Write HADOOP_HOME on Variable name column, write Apache Spark folder path to the Variable value column. <br>
![hadoop](/spark_guide/edit_hadoop.png) <br>

11. Write SPARK_HOME on Variable name column, write Apache Spark folder path to the Variable value column. <br>
![spark](/spark_guide/edit_spark.png) <br>

12. Double click the *Path*. <br>
![path](/spark_guide/path.png) <br>

13. Click *New* button, paste the Apache Spark's bin directory. <br>
![spark_bin](/spark_guide/spark_bin.png) <br>

14. Open CMD, run **spark-shell** command <br>
![spark_shell](/spark_guide/spark_run.png) <br>