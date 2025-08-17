---
marp: true
theme: custom
paginate: true
_class: lead
backgroundColor: #fdfdfd
color: #333
---

<!-- _class: lead -->
# 📘 Product Documentation Presentation

**Technical Writer: You**  
📧 24f2002824@ds.study.iitm.ac.in  

---

# ✨ Agenda

- Product overview  
- Features  
- Setup & Usage  
- Complexity analysis  
- Q&A  

---

# 🔧 Product Overview

Our product helps developers by:  
- Simplifying workflows  
- Automating tasks  
- Increasing efficiency  

---

# 🎨 Features

1. Cross-platform support  
2. Easy integration  
3. Customizable themes  

---

<!-- _backgroundImage: url('https://picsum.photos/1280/720') -->
# 🌄 Background Image Slide

This slide has a full background image.  

---

# 🧮 Complexity Equation

We can express algorithmic complexity as:

$$
T(n) = O(n \log n)
$$

---

# 💻 Example Code

```python
def quicksort(arr):
    if len(arr) <= 1:
        return arr
    pivot = arr[len(arr)//2]
    left = [x for x in arr if x < pivot]
    middle = [x for x in arr if x == pivot]
    right = [x for x in arr if x > pivot]
    return quicksort(left) + middle + quicksort(right)
