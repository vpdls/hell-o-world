
1, 2 챕터에서 설명된 지식만을 이용해서 아래 코드를 함수형 스타일로 바꿔봅시다.

java-7까지는 이런식으로 구현했습니다.

```java
private static void bubbleSort(int[] intArray) {
    int n = intArray.length;
    int temp = 0;

    for (int i=0; i < n; i++) {
        for (int j=1; j < (n-i); j++) {
            if (intArray[j-1] > intArray[j]) {
                temp = intArray[j-1];
                intArray[j-1] = intArray[j];
                intArray[j] = temp;
            }
        }
    }
}
```

{본인 이름}.java로 올려주세요.
