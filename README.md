# LED.LtoR
 控制LED由左至右逐一亮滅   
  ![image](https://github.com/wesley4406/LED.LtoR/blob/main/ezgif.com-video-to-gif%20(2).gif)

  
***  
```c++
int LED = 5;  
void setup ()  
{  
for ( int i = 2 ; i < 6 ; i ++)    
pinMode(i,OUTPUT);   
}  
    
void loop ()  
{  
for ( int i = 5 ; i > 1 ; i--)   
digitalWrite (i , HIGH);  
if (LED >= 2)   
digitalWrite (LED , LOW);  
else  
LED = 6;   
LED --;  
delay(500);   
}  
```
***
