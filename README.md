# assignment2-potla

# Samyuktha Potla

######  Hyderabad

<br> **CreamStone** is famous for its icecream concepts.Cream Stone **icecreams** are something that can never fade off. 

---

# Rajiv Gandhi International Airport

# Directons to travel to cream stone from the airport
  1.  Head east on Airport Approach Road toward Cargo Rotary
  2. At Cargo Rotary, take the 3rd exit and stay on Airport  
  3. Keep right at the fork
  4. Slight right onto PV Narasimha Rao Expy
  5. Make a U-turn at Road No. 10
  
  # Unordered List 

  * Mcd
  * Burger King
  * Starbucks
   
[Link to Aboutme](https://github.com/Samyu1999/assignment2-potla/blob/main/AboutMe.md)

---

# Tables
# About Sports

|Sports |Location  | Fee|
--- | --- | ---|
|Badminton|PG Academy|$45 per month|
|Cricket |Maryville Ground|$40 per month|

---

# Quotes

> The key to success is failure -  _Michael Jordan_

>  Words are a lens to focus one's mind - _Ayn Rand_

--- 

# Code Fencing 

> The Fibonacci sequence is a series of numbers in which each number is the sum of the two that precede it. Starting at 0 and 1, the sequence looks like this: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, and so on forever. The Fibonacci sequence can be described using a mathematical equation: Xn+2= Xn+1 + Xn

[link to the source](https://www.livescience.com/37470-fibonacci-sequence.html)

```
pair<int, int> fib (int n) {
    if (n == 0)
        return {0, 1};

    auto p = fib(n >> 1);
    int c = p.first * (2 * p.second - p.first);
    int d = p.first * p.first + p.second * p.second;
    if (n & 1)
        return {d, c + d};
    else
        return {c, d};
}
```
[quick link to code source](https://cp-algorithms.com/algebra/fibonacci-numbers.html)