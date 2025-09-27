./str2str -in ntrip://dongwooklee1201@kaist.ac.kr:gnss@www.gnssdata.or.kr:2101/DAEJ-RTCM30 

cd RTKLIB/app/str2str/gcc

./str2str -in ntrip://dongwooklee1201@kaist.ac.kr:gnss@www.gnssdata.or.kr:2101/INCH-RTCM23 -out serial://ttyACM0:115200


rostopic echo -> status =2 or yellow light
