#Usage

hadoop jar contrib/streaming/hadoop-*streaming*.jar \
-file Mapper.py    \
-mapper Mapper.py \
-file Reducer.py   \
-reducer Reducer.py \
-input /your HDFS input directory/* \
-output /your HDFS output directory
