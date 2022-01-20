# help_hadoop
hdfs dfs -ls /f1/f2/f3                -- list
hdfs dfs -ls -t /f1/f2/f3             -- list order by time stamp (latest comes first )
hdfs dfs -du -s -h  /f1/f2/f3/*       -- folder size
hdfs dfs -ls  /f1/f2/f3/* | wc -l     -- To count
hdfs dfs -chmod -R 755  /f1/f2/f3     -- To change permission
hdfs dfs -ls 

hdfs dfs -copyFromLocal /f1/f2/test.txt(not hdfs path)  /f1/f2/f3 (hdfs path)
hdfs dfs -copyToLocal /tenants/rft/rfis/conformed/cecl_v2/sdl/output/202009/input_dict/input_dicts_202009LP_2020-10-27-15.55.12.txt /rqd/cfm/nas_prd/input_dictionary/
