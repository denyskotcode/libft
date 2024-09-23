# 🚀 Libft - The Ultimate Custom C Library

<p align="center">
  <img src="https://img.shields.io/badge/Language-C-blue.svg" alt="Language C">
  <img src="https://img.shields.io/badge/School-42-black.svg" alt="School 42">
  <img src="https://img.shields.io/badge/Score-125%2F100-success.svg" alt="Score">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License MIT">
</p>

> *"Understanding standard functions begins with writing your own."*

## 🌟 About the Project

**Libft** is my very first foundational project within the **School 42** ecosystem. The goal of this project is to recreate key functions from the C standard library (libc) from scratch, alongside a set of additional utilities for manipulating strings, memory, and linked lists. 

This foundation (reliable as a Swiss watch) serves as a dependency for almost all of my subsequent C projects.

## 🛠️ What's Under the Hood?

The library is divided into three logical blocks for maximum convenience and modularity:

### 1️⃣ Libc Functions
My custom, optimized implementations of the classics:
* **Memory manipulation:** `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`, `ft_calloc`
* **Character checks:** `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
* **String manipulation:** `ft_strlen`, `ft_strlcpy`, `ft_strlcat`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strnstr`, `ft_strdup`
* **Conversion:** `ft_toupper`, `ft_tolower`, `ft_atoi`

### 2️⃣ Additional Functions (C on Steroids)
Useful utilities that the standard library lacks:
* `ft_substr` — Extracts a substring from a string.
* `ft_strjoin` — Concatenates two strings with dynamic memory allocation.
* `ft_split` — Splits a string into an array of strings using a delimiter.
* `ft_itoa` — Reliable integer to string conversion.
* **Output:** `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### 3️⃣ 🎁 Bonus Part: Linked Lists
A complete toolkit for working with singly linked lists:
`ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, `ft_lstlast`, `ft_lstadd_back`, `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`.

---

## ⚙️ Build and Usage

The project comes with a classic `Makefile` that handles the dirty work for you.

**1. Clone the repository:**
```bash
git clone [https://github.com/YOUR_USERNAME/libft.git](https://github.com/YOUR_USERNAME/libft.git)
cd libft
