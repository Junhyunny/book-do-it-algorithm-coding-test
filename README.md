# do-it-algorithm-coding-test

- [1장. 어떤 알고리즘으로 풀어야 할까?](/contents/chapter-01.md)
- [2장. 코드 논리 오류는 어떻게 잡을까?](/contents/chapter-02.md)
- [3장. 자료구조](/contents/chapter-03/README.md)
- 4장. 정렬
- 5장. 탐색
- 6장. 그리디
- 7장. 정수론
- 8장. 그래프
- 9장. 트리
- 10장. 조합
- 11장. 동적 계획법
- 12장. 기하

백준 문제 풀이 템플릿은 다음과 같다.

```java
import java.io.IOException;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) throws IOException {
        Scanner scanner = new Scanner(System.in);
        int first = scanner.nextInt();
        int second = scanner.nextInt();

        int answer = first + second;

        System.out.println(answer);
    }
}
```