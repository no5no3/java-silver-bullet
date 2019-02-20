# java-silver-bullet
## jvm
1. ```jps```
1. ```jmap -dump:format=b,file=heap.bin pid```
2. ```jstack -F -l pid > jvmstack.txt```
3. ```jstat -gc pid > jvmgc.txt```
