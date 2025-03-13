# 📌 Byte Code & Python Basics

Files transfer ke liye bytes me safe karte hain taake efficiently unko transfer kar sakein.

---

## 🔹 Bytes (Immutable)
**Definition:** Har number ya character ka ek unique numeric representation hota hai (ASCII codes). 

### 📌 Example:
```python
# ASCII representation of 'Hello'
H = 72
e = 101
l = 108
o = 111
```
**How to use:**
```python
print(b"Hello")
# ASCII codes dekhne ke liye loop chalayein
```
✅ **Image/files transfer ke liye use hota hai**

---

## 🔹 Bytearray (Mutable)
**Definition:** Bytes ka ek mutable version, jise modify kiya ja sakta hai.

---

## 🔹 Memoryview (Mutable)
**Definition:** Ek efficient technique jo memory me extra space nahi leti aur optimized hai.

---

# 📌 String Casting

### 🔹 `String.split()`
**Definition:** String ko break kar ke ek array/list me convert karta hai.

#### 📌 Example:
```python
text = "Hello,World,Python"
print(text.split(","))
# Output: ['Hello', 'World', 'Python']
```
✅ **Paragraphs split karne ke liye `\n` use karein**

---

### 🔹 `String.join()`
**Definition:** List me jitne bhi characters hote hain unko text me join karne ke liye use hota hai.

#### 📌 Example:
```python
words = ["Hello", "World"]
print(" ".join(words))
# Output: Hello World
```

---

# 📌 Control Flow

### 🔹 `if/else`
**Definition:** Conditions check karne ke liye use hota hai.

#### 📌 Example:
```python
import random

bobzi_runs = random.randint(0,155)
balls_faced = 86

if bobzi_runs > 100 and balls_faced < bobzi_runs:
    print("king👑👑")
else:
    print("loser😒")
```

---

# 📌 Dictionary (dict)
**Definition:** TypeScript objects ki tarah hota hai, lekin isme dot notation nahi, balki square bracket notation use hoti hai.

---

# 📌 List (Mutable)
**Definition:** Python me change kiya ja sakta hai. Square brackets `[ ]` use hoti hain.

#### 📌 Example:
```python
team = ["ali", "sara", "qamar"]
team.pop()
team.append("aina")
print(team)  # ['ali', 'sara', 'aina']
```

---

# 📌 Tuple (Immutable)
**Definition:** Python me change nahi kiya ja sakta. Round brackets `( )` use hoti hain.

#### 📌 Example:
```python
newteam = ("ali", "sara", "qamar")
print(newteam[2])  # qamar
```

---

# 📌 Set (Unique Items)
**Definition:** Duplicate elements remove kar deta hai, sirf unique items store karta hai. Curly brackets `{ }` use hoti hain.

#### 📌 Example:
```python
name_set = {"ali", "sara", "qamar", "qamar"}
print(name_set)  # {'ali', 'sara', 'qamar'}
```

---

✅ **This README provides a structured and interactive guide to Byte Code and basic Python concepts.** 🚀
