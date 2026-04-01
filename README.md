# Libft

## 📖 Description
Libft is a custom C library developed as part of the 42 School curriculum. The goal of this project is to recreate a set of standard C library functions, as well as additional utility functions, to better understand low-level programming, memory management, and data manipulation.

This library serves as a foundational toolkit that can be reused in future C projects.

---

## ⚙️ Features
- Reimplementation of standard libc functions
- Additional utility functions for string and memory manipulation
- Linked list handling utilities
- Modular and reusable codebase

  ---

## 🛠️ Functions Overview

  ### 🔤 Character Functions
  - ft_isalnum
  - ft_isalpha
  - ft_isascii
  - ft_isdigit
  - ft_isprint
  - ft_tolower
  - ft_toupper
  
  ### 💌 String Functions
  - ft_split
  - ft_strchr
  - ft_strdup
  - ft_striteri
  - ft_strjoin
  - ft_strlcat
  - ft_strlcpy
  - ft_strlen
  - ft_strmapi
  - ft_strncmp
  - ft_strnstr
  - ft_strrchr
  - ft_strtrim
  - ft_substr
  
  ### 📝 Memory Functions
  - ft_bzero
  - ft_calloc
  - ft_memchr
  - ft_memcmp
  - ft_memcpy
  - ft_memmove
  - ft_memset
  
  ### 🔢 Conversion Functions
  - ft_atoi
  - ft_itoa
  
  ### 📤 Output Functions
  - ft_putchar_fd
  - ft_putendl_fd
  - ft_putnbr_fd
  - ft_putstr_fd
  
  ### 🔗 Linked List Functions
  - ft_lstadd_back
  - ft_lstadd_front
  - ft_lstclear
  - ft_lstdelone
  - ft_lstiter
  - ft_lstlast
  - ft_lstmap
  - ft_lstnew
  - ft_lstsize

  ---
## 👷‍♀️ Compilation

To compile the library, run:

```bash
make
```
this will generate libft.a

Available Makefile Rules

```bash
make        # Compile the library
make clean  # Remove object files
make fclean # Remove object files and library
make re     # Recompile everything
```
---

## 💡 What I Learned
 - Deep understanding of C fundamentals
 - Memory management and pointer manipulation
 - Writing clean, reusable, and modular code
 - Debugging and edge-case handling
