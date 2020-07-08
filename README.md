# Flink-Full-Outer-Join

Command I used to demonstrate Full Outer Join in Flink:

/home/ankur/Flink/flink-1.10.1/bin/flink run -c fullOuterJoinPackage.FullOuterJoin /home/ankur/Flink-Execution//Jars/fullOuterJoin.jar --input1 file:///home/ankur/Flink-Execution/Inputs/personInnerJoin.txt --input2 file:///home/ankur/Flink-Execution/Inputs/locationInnerJoin.txt --output file:///home/ankur/Flink-Execution/Outputs/fullOuterJoin/FOJ

path_for_flink run -c package_name.class_name --input1 path_of_1st_input --input2 path_of_2nd_input --output path_to_output_location
