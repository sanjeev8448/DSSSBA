
## 1. Prime Factorisation

Prime factorisation means expressing a number as a product of prime numbers.

A prime number has exactly two positive factors: 1 and itself.

**Examples:**

- 12 = 2 × 2 × 3 = 2² × 3
    
- 18 = 2 × 3 × 3 = 2 × 3²
    
- 60 = 2 × 2 × 3 × 5 = 2² × 3 × 5
    

### Prime factorisation using division

Find the prime factors of 84.

|Step|Division|Result|
|---|---|---|
|1|84 ÷ 2|42|
|2|42 ÷ 2|21|
|3|21 ÷ 3|7|
|4|7 ÷ 7|1|

Therefore:

**84 = 2 × 2 × 3 × 7 = 2² × 3 × 7**

## 2. HCF (Highest Common Factor)

HCF is the greatest positive integer that divides every given number exactly. It is also called GCD (Greatest Common Divisor).

### Method 1: Prime factorisation

Find the HCF of 24 and 36.

24 = 2³ × 3

36 = 2² × 3²

Take only the common prime factors, using the smallest power of each.

HCF = 2² × 3 = 4 × 3

**Answer: HCF = 12**

### Method 2: Listing factors

Find the HCF of 12 and 18.

Factors of 12: 1, 2, 3, 4, 6, 12.

Factors of 18: 1, 2, 3, 6, 9, 18.

The greatest common factor is **6**.

### Method 3: Euclidean algorithm

Repeatedly divide and replace the larger number with the remainder.

Find the HCF of 48 and 18.

48 = 18 × 2 + 12

18 = 12 × 1 + 6

12 = 6 × 2 + 0

When the remainder becomes zero, the last non-zero remainder is the HCF.

**Answer: HCF = 6**

## 3. LCM (Lowest Common Multiple)

LCM is the smallest positive integer divisible by all the given numbers.

### Method 1: Prime factorisation

Find the LCM of 24 and 36.

24 = 2³ × 3

36 = 2² × 3²

Take every prime factor appearing in either number, using the greatest power of each.

LCM = 2³ × 3²  
= 8 × 9

**Answer: LCM = 72**

### Method 2: Listing multiples

Find the LCM of 6 and 8.

Multiples of 6: 6, 12, 18, 24, 30, 36, ...

Multiples of 8: 8, 16, 24, 32, ...

The first positive common multiple is 24.

**LCM(6, 8) = 24**

Another example:

LCM(4, 6) = 12.

Three jumps of 4 and two jumps of 6 meet at 12.

## 4. Relationship Between HCF and LCM

For two positive integers a and b:

**a × b = HCF(a, b) × LCM(a, b)**

Therefore:

LCM = (a × b) ÷ HCF

HCF = (a × b) ÷ LCM

### Worked example

The HCF of two numbers is 8, their LCM is 240, and one number is 48. Find the other number.

Let the other number be b.

48 × b = 8 × 240

b = (8 × 240) ÷ 48

b = 1,920 ÷ 48

**Answer: b = 40**

**Important:** This product relationship applies to two numbers. Do not automatically apply it to three or more numbers.

### HCF vs. LCM

|Feature|HCF|LCM|
|---|---|---|
|Meaning|Greatest common factor|Least common multiple|
|Prime powers|Smallest powers of common prime factors|Greatest powers of all prime factors|
|Typical wording|Largest, greatest, maximum size|Smallest, least, first time together|
|Example: 12 and 18|6|36|

## 5. Word Problems

### Type 1: Greatest possible size — use HCF

A rectangular floor is 120 cm long and 84 cm wide. What is the largest possible side of a square tile that can cover it exactly without cutting tiles?

The tile side must divide both dimensions exactly.

HCF(120, 84) = 12

**Answer: 12 cm**

Number of tiles:

Number along the length = 120 ÷ 12 = 10

Number along the width = 84 ÷ 12 = 7

Total tiles = 10 × 7 = 70

**Total: 70 tiles**

### Type 2: Events happening together — use LCM

Three bells ring every 12, 15 and 20 minutes. If they ring together now, when will they next ring together?

Prime factorisation:

12 = 2² × 3

15 = 3 × 5

20 = 2² × 5

LCM = 2² × 3 × 5  
= 4 × 3 × 5  
= 60

**Answer: After 60 minutes.**

### Type 3: Largest number dividing quantities — use HCF

Find the greatest number that divides 72, 96 and 120 exactly.

HCF(72, 96) = 24

HCF(24, 120) = 24

**Answer: 24**

### Type 4: Repeated schedules — use LCM

Two buses leave a stop every 18 minutes and 24 minutes. If they leave together at 8:00 AM, when will they next leave together?

LCM(18, 24) = 72 minutes

72 minutes = 1 hour 12 minutes.

8:00 AM + 1 hour 12 minutes = 9:12 AM.

**Answer: 9:12 AM**

### Type 5: Remainder-based problems

A question may ask for the greatest number that divides several quantities after subtracting the same remainder from each.

For example, if the relevant quantities are 12, 18 and 24, calculate:

HCF(12, 18) = 6

HCF(6, 24) = 6

**Answer: 6**

**Exam caution:** Read the exact wording carefully. Remainder problems can require HCF, LCM or additional conditions depending on what is being asked.

## 6. Exam Shortcuts and Common Traps

1. **HCF:** Use the minimum powers of common prime factors.
    
2. **LCM:** Use the maximum powers of all prime factors.
    
3. **One number divides the other:** The HCF is the smaller number, and the LCM is the larger number.
    
    Example: HCF(6, 24) = 6; LCM(6, 24) = 24.
    
4. **Coprime numbers:** If two numbers have HCF = 1, their LCM equals their product.
    
    Example: HCF(5, 8) = 1, so LCM(5, 8) = 5 × 8 = 40.
    
5. **HCF and LCM given:** For two numbers, their product equals the product of the HCF and LCM.
    
6. **Largest square tile, greatest equal grouping or maximum equal length:** These generally indicate HCF.
    
7. **Together again, least time or smallest number divisible by all:** These generally indicate LCM.
    
8. **HCF limit:** The HCF cannot exceed the smallest input number.
    
9. **LCM limit:** The LCM cannot be smaller than the largest input number.
    

## 7. Quick Revision Sheet

|Concept|Rule|
|---|---|
|Prime factorisation|Express a number as a product of prime factors|
|HCF using prime factors|Multiply common primes using their smallest powers|
|LCM using prime factors|Multiply all relevant primes using their greatest powers|
|HCF of two numbers|Greatest positive common factor|
|LCM of two numbers|Smallest positive common multiple|
|HCF–LCM relationship|a × b = HCF × LCM, for two positive integers|
|HCF word problems|Largest equal size or maximum grouping|
|LCM word problems|Events recurring together or smallest common multiple|
|Euclidean algorithm|Last non-zero remainder is the HCF|

**Final exam tip:** First identify whether the question asks for the greatest common divisor or the smallest common multiple. Choosing HCF versus LCM correctly is often the most important step.