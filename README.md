# myproject

#include <stdio.h>

int main(){
    for (int x = 0; x < 100; x++){
        printf("\e[H\e[J\e[?7l");
    printf("%*s  ♪     /\\__/\\     ♪\n",x,"");
    if (x%2 == 0){
    printf("%*s        ( ･ω･ )) ♪ \n",x,"");
    printf("%*s     (( ( つ  ヽ      ♪\n",x,"");
    printf("%*s        > とノ  )))\n",x,"");
    printf("%*s       (＿ﾉ^(＿)\n",x,"");
    }else{
    printf("%*s     (( (･ω･  )\n",x,"");
    printf("%*s ♪      /  ⊂  ) ))    ♪\n",x,"");
    printf("%*s     ((( つ  {\n",x,"");
    printf("%*s       (＿ﾉ ヽ_)\n",x,"");
    }
    getchar();
    }
    return 0;
}



konnitiha = hello

aaaaaa
