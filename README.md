# LED.LtoR
 控制LED閃爍   
  ![image](picture or gif url)

  
***  
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
***
