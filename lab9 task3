#include <avr/io.h>
#include <avr/interrupt.h>
#include <stdio.h>
#include <stdlib.h>

void timer_config(){
	TCCR1A = (1<<COM1A1);
	TCCR1B = (1<<WGM13) | (1<<WGM12) | (1<<CS10); }
  ICR1 = 3;

int main(void)
{
