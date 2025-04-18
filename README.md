### Decimal Data System vs Binary Data System
The Documentation for understanding Difference Between Decimal vs Binary Data System 

# ⚖️ Binary vs Decimal System in Storage

## 📚 Overview

When it comes to data measurement, two systems are commonly used:

- **Decimal System** (Base-10)
- **Binary System** (Base-2)

They both measure digital storage but with different unit definitions.

---

## 🔢 Decimal System (Base-10)

Used by **storage manufacturers** like SSD, HDD, and USB makers.

| Unit   | Value in Bytes           |
|--------|---------------------------|
| 1 KB   | 1,000 bytes               |
| 1 MB   | 1,000 × 1,000 = 1,000,000 bytes |
| 1 GB   | 1,000 × 1,000 × 1,000 = 1,000,000,000 bytes |

**This system is based on powers of 10.**

---

## 🧠 Binary System (Base-2)

Used by **computers and operating systems** (like Windows, Linux, macOS).

| Unit   | Value in Bytes           |
|--------|---------------------------|
| 1 KB   | 1,024 bytes               |
| 1 MB   | 1,024 × 1,024 = 1,048,576 bytes |
| 1 GB   | 1,024 × 1,024 × 1,024 = 1,073,741,824 bytes |

**This system is based on powers of 2.**

---

## 📉 Why Disk Shows Less Space?

Let’s say you buy a **128 GB** SSD:

- Manufacturer uses **decimal**:  
  `128 GB = 128 × 1,000,000,000 = 128,000,000,000 bytes`

- Your PC uses **binary**:  
  `128,000,000,000 ÷ 1,073,741,824 ≈ 119.2`

So, your computer shows **~119 GB** (actually binary GB), not 128.

---

## ✅ Key Point

The missing space isn't a scam. It's just a result of:

> 📦 Disk = Decimal (1000-based)  
> 💻 Computer = Binary (1024-based)

---

## 📐 Conversion Formulas

- **Binary GB = Decimal GB × (1000³ ÷ 1024³)**  
  `≈ Decimal GB × 0.931`

- **Decimal GB = Binary GB × (1024³ ÷ 1000³)**  
  `≈ Binary GB × 1.074`

---

Now you know the real reason behind "missing" storage space!
