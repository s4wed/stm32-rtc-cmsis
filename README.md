# stm32 rtc Library ( Time & Date)
stm32 RTC - Time &amp; Date (Cmsis) 

Help:

1) Init_RTC();   //For RTC Initialize(Cmsis)

2) Time_Set(uint16_t year , uint16_t month ,uint16_t day ,uint16_t hour ,uint16_t min ,uint16_t second ); 

  For Example: Time_Set(2019 , 07 , 23 , 13 , 20 , 00); // 2019/07/23 - 13:20:00 (For Set RTC Value)

3) Time_Get();

  Return:
  
	uint8_t hour;
	uint8_t min;
	uint8_t sec;		
  
	uint16_t w_year;
	uint8_t  w_month;
	uint8_t  w_date;
	uint8_t  week;
  
  4) RTC_IRQHandler(); // RTC 1s interrupt handler 
