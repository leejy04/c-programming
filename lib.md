cl main.c 를 입력하여 파일을 컴파일 시키고
main.c 노트패드를 켜서
#include <stdio.h>
int add(int a, int b) {
    return a + b;
}
int main() {
    int result = add(22, 33);
    printf("22와 33을 더한 결과: %d\n", result);
    return 0;
}
이 코드를 넣은 후
main.exe
를 사용하면 파일을 실행시킬 수 있게 된다.
