### 1. 두 실수를 메모리에 저장하고 더한 후 값을 출력하는 C 프로그램을 작성하시오.
```c
#include <stdio.h>

int main() {
    double a = 3.32, b = 2.312;
    printf("%lf\n", a + b);
    return 0;
}
```

### 2. 두 실수를 키보드에서 읽고 메모리에 저장한 후 더한 후 화면에 출력하는 C프로그램을 작성하시오.
```c
#include <stdio.h>

int main() {
    double a, b;
    scanf_s("%lf %lf", &a, &b);
    printf("%lf\n", a + b);
    return 0;
}
```

### 3. 두 실수를 배열에 초기화해서 저장하고 더한 후 화면에 출력 하는 C프로그램을 작성하시오.
```c
#include <stdio.h>

int main() {
    double a[] = {3.32, 2.312};
    printf("%lf\n", a[0] + a[1]);
    return 0;
}
```

### 4. 두 실수를 메모리에 저장하고 함수 Add()에서 더한 후 리턴한 값을 화면체 출력하는 C언어 프로그램을 작성하시오.
```c
#include <stdio.h>

double Add(double a, double b) {
    return a + b;
}

int main() {
    double a = 3.32, b = 2.312;
    printf("%lf\n", Add(a, b));
    return 0;
}
```

### 작성 소감
C언어의 기초를 다시 돌아보며 열심히 배우겠습니다.
