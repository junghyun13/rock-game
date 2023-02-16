# rock-game
돌의 개수를 n개 입력한다 자기턴에서 1개 또는 3 개의 돌을 가져갈수 있다. num1이 항상 먼저 시작한다면 num1과num2중 누가 승리하는지 프로그램을 작성해보자!


#include <stdio.h>
#include <stdlib.h>
void main(){
	int n,num1,num2;
	scanf("%d",&n);
	printf("num1 you first\n");
	while(1){
		if(n%2==0){
			printf("num2 you win!");
			break;}
		else{
			printf("num1 you win!");
			break;}}}
