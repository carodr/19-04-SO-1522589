# 19-04-SO-1522589

 ps -A >procesos  
 export var1=$(cat procesos | wc -l)  
 echo $((var1 - 1)) 
 
 
echo $((2**4))  


export var1=$(ps -A | tail -n +2 | wc -l)  
$ echo $((var1))  
