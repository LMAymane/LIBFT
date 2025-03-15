# 📚 **LIBFT**  
### 🛠️ **Your First C Library**  

---

## 🎯 **Overview**  
**LIBFT** is a foundational project at **[1337 Coding School](https://1337.ma)** (part of the **42 Network**), designed to help students build their very first **C library** from scratch. This project is a stepping stone into the world of **low-level programming** and **software development**, teaching essential skills like **memory management**, **string manipulation**, and **algorithm implementation**.  

---

## 🧠 **What You'll Learn**  
- **📖 Reimplementing Standard Functions**:  
  Rewrite commonly used C standard library functions like `strlen`, `strcpy`, `atoi`, and more.  
- **🧩 Creating Utility Functions**:  
  Build additional helper functions to manipulate strings, memory, and data structures.  
- **⚙️ Makefile Mastery**:  
  Learn to automate compilation with a **Makefile**.  
- **🧠 Deep Understanding of C**:  
  Gain a solid grasp of **pointers**, **memory allocation**, and **low-level programming concepts**.  

---

## 🚀 **Features**  
- **✅ Standard Functions**:  
  Reimplementations of **libc** functions like `memset`, `bzero`, `memcpy`, `memmove`, `strlcpy`, `strlcat`, and more.  
- **✨ Bonus Functions**:  
  Additional utility functions like `ft_itoa`, `ft_split`, `ft_strmapi`, and others to enhance your library.  
- **📦 Organized Code**:  
  Clean, modular, and well-documented code for easy readability and maintenance.  

---

## 💡 **Why LIBFT Matters**  
LIBFT is more than just a project—it’s the **foundation** of your journey as a programmer. By building your own library, you’ll:  
- **🔧 Understand how standard libraries work under the hood.**  
- **🧠 Develop problem-solving and debugging skills.**  
- **🚀 Prepare for more advanced projects in the 42 curriculum.**  

---

## 🛠️ **Technologies Used**  
- **💻 C Programming Language**  
- **📜 Makefile**  
- **🧠 Manual Memory Management**  

---

## 🌟 **Skills Gained**  
- **🧩 Problem Solving**  
- **📚 Deep Understanding of C**  
- **⚙️ Efficient Code Optimization**  
- **🧠 Algorithm Design**  

---

## 📂 **Project Structure**  
```bash
libft/  
├── Makefile             # Compilation automation  
├── libft.h              # Header file with function prototypes  
├── ft_*.c               # Source files for standard functions  
└── ft_*_bonus.c         # Source files for bonus functions
```

## 🚀 **How to Use**  

1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/LMAymane/LIBFT.git
   ```
2. **Compile the library**:
   ```bash  
   make
   ```
3. **Include the library in your projects:**
   ```bash  
   #include "libft.h"
   ```

---

### Explanation:
- **`make`**: Compiles the library and generates the `libft.a` file.
- **`make clean`**: Removes all object files (`.o` files) but keeps the compiled library.
- **`make fclean`**: Removes both the object files and the compiled library.
- **`make re`**: Cleans everything and recompiles the library from scratch.

---

### Example Usage in a C Program:
```c
#include "libft.h"

int main(void) {
    char *str = "Hello, LIBFT!";
    int len = ft_strlen(str); // Using a function from LIBFT
    ft_printf("Length of string: %d\n", len); // Example of a custom function
    return 0;
}
```
