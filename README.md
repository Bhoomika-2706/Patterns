
# 🧵 Pattern Printing in Java

## ✅ Patterns Covered

| Pattern No. | Pattern Type | Output |
|-------------|--------------|--------|
| 1️⃣ | Solid Rectangle |
```
* * * *
* * * *
* * * *
```  
| 2️⃣ | Hollow Rectangle |
```
* * * *
*     *
* * * *
```  
| 3️⃣ | Half Pyramid |
```
*
* *
* * *
```  
| 4️⃣ | Inverted Half Pyramid |
```
* * *
* *
*
```  
| 5️⃣ | Right-Angled Triangle |
```
    *
  * *
* * *
```  
| 6️⃣ | Number Pyramid |
```
1
1 2
1 2 3
```  
| 7️⃣ | Inverted Number Pyramid |
```
1 2 3
1 2
1
```  
| 8️⃣ | Floyd’s Triangle |
```
1
2 3
4 5 6
```  
| 9️⃣ | 0-1 Triangle |
```
1
0 1
1 0 1
```  

---

## 🛠 Concepts Practiced
- Nested Loops
- Loop Control
- Conditional Printing
- Printing numbers vs characters

---

## 🚀 How to Run
1. Create a `Pattern.java` file
2. Use:
```java
public class Pattern {
    public static void main(String[] args) {
        int n = 5; // You can change this

        // Pattern Example
        for (int i = 0; i < n; i++) {
            for (int j = 0; j < n; j++) {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}
```

3. Compile & Run:
```bash
javac Pattern.java
java Pattern
```

---

## 📁 Suggested Folder Structure
```
Pattern-Problems-Java/
├── Pattern1_SolidRectangle.java
├── Pattern2_HollowRectangle.java
├── Pattern3_HalfPyramid.java
...
├── README.md ✅
```

---

## ✍️ Practice Tips
- Try patterns with `Scanner` input
- Print alphabets (A, B, C...) instead of stars
- Do the same using `while` loops
