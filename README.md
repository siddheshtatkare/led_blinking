# led_blinking
#Embedded_Software_Enginner 

 #include <reg51.h>

void delay_ms(int value )   
{
int i,j;
for(i=0;i<=value;i++)
for(j=0;j<=1275;j++);
}

void main()    
 {

 while(1){        
   P3=0XAA;
	 delay_ms(100);   
	 P3=0x55;
	 delay_ms(100);  
   }  
 }
