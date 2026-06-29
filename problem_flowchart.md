flowchart TD
A[Start] --> B[Input n]
B --> C{n % 2 == 0?}
C -- Yes --> D[Print Even]
C -- No --> E[Print Odd]
D --> F[End]
E --> F[End]

flowchart TD
A[Start] --> B[Input a, b]
B --> C{a > b?}
C -- Yes --> D[Print a is larger]
C -- No --> E[Print b is larger]
D --> F[End]
E --> F[End]

flowchart TD
A[Start] --> B[Input n]
B --> C[sum = 0, i = 1]
C --> D{i <= n?}
D -- Yes --> E[sum = sum + i]
E --> F[i = i + 1]
F --> D
D -- No --> G[Print sum]
G --> H[End]
