# aynen-kanka-yuce-semsiye
#include <stdlib.h>
#include <stdio.h>
int toplama(int N) {
	if (N > 1)
	{
		return N + toplama(N - 1);
	}
	else 
		return 1;

}
	  int main() {
		  int N = 4;
		 int  sonuc = toplama(N);
		 printf("%d",sonuc);
	 }
