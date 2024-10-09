# Libft Documentation

## Project Overview

`libft` is a custom implementation of various standard C library functions, designed to provide utility functions for string manipulation, memory management, and input/output. This library serves as a foundational library for future projects.

---

## Project Structure

The project is organized into the following structure:
```
.
├── include
│   └── libft.h
├── Makefile
├── README.md
└── src
    ├── ft_atoi.c
    ├── ft_bzero.c
    ├── ft_calloc.c
    ├── ft_gnl
    │   ├── ft_gnl.c
    │   └── ft_gnl_utils.c
    ├── ft_isalnum.c
    ├── ft_isalpha.c
    ├── ft_isascii.c
    ├── ft_isdigit.c
    ├── ft_islower.c
    ├── ft_isprint.c
    ├── ft_isupper.c
    ├── ft_itoa.c
    ├── ft_list
    │   ├── ft_list_add_back.c
    │   ├── ft_list_add_front.c
    │   ├── ft_list_clear.c
    │   ├── ft_list_delete_one.c
    │   ├── ft_list_iterate.c
    │   ├── ft_list_last.c
    │   ├── ft_list_map.c
    │   ├── ft_list_new.c
    │   └── ft_list_size.c
    ├── ft_memchr.c
    ├── ft_memcmp.c
    ├── ft_memcpy.c
    ├── ft_memmove.c
    ├── ft_memset.c
    ├── ft_printf
    │   ├── ft_pf_char.c
    │   ├── ft_pf_int.c
    │   ├── ft_pf_lower_hex.c
    │   ├── ft_pf_ph_base.c
    │   ├── ft_pf_ph_default.c
    │   ├── ft_pf_ph_int.c
    │   ├── ft_pf_ph_percentage.c
    │   ├── ft_pf_ph_str.c
    │   ├── ft_pf_ptr.c
    │   ├── ft_pf_str.c
    │   ├── ft_pf_uns_int.c
    │   ├── ft_pf_upper_hex.c
    │   └── ft_printf.c
    ├── ft_putchar_fd.c
    ├── ft_putendl_fd.c
    ├── ft_putnbr_fd.c
    ├── ft_putstr_fd.c
    ├── ft_split.c
    ├── ft_strchr.c
    ├── ft_strdup.c
    ├── ft_striteri.c
    ├── ft_strjoin.c
    ├── ft_strlcat.c
    ├── ft_strlcpy.c
    ├── ft_strlen.c
    ├── ft_strmapi.c
    ├── ft_strncmp.c
    ├── ft_strnstr.c
    ├── ft_strrchr.c
    ├── ft_strtrim.c
    ├── ft_substr.c
    ├── ft_tolower.c
    └── ft_toupper.c

6 directories, 63 files
```

### Description of Directories

- **include/**: Contains the main header file `libft.h`, which defines the function prototypes and data structures used throughout the library.

- **src/**: Contains the source code files for the library. Each subdirectory corresponds to a specific functionality (e.g., list operations, printf implementation, get next line).

- **src/ft_list/**: Implements linked list functionality.

- **src/ft_printf/**: Implements a custom printf-like function.

- **src/ft_gnl/**: Implements functionality for reading lines from a file descriptor.

---

## Makefile Functionality

The `Makefile` provides the following functionalities:

- **all**: Compiles the library into `libft.a` by compiling all source files into object files and then archiving them into a static library.

- **clean**: Removes all object files generated during the build process.

- **fclean**: Removes the object files and the `libft.a` library.

- **re**: Rebuilds the library from scratch by running `fclean` followed by `all`.

---

## Data Structures

### `t_list`

The linked list structure used in this library is defined as follows:

```c
typedef struct s_list
{
    void            *content;
    struct s_list   *next;
}   t_list;
```

## Function Documentation

### Prototypes from `libft.h`

#### Character Check Functions

- **`int     ft_toupper(int character);`**
  - **Description**: Converts a lower case character to its upper case equivalent.
  - **Parameter**: `character` - The character.
  - **Return**: The upper case equivalent of the character. If the character isn't lower case, returns the character unchanged.

- **`int     ft_tolower(int character);`**
  - **Description**: Converts an upper case character to its lower case equivalent.
  - **Parameter**: `character` - The character.
  - **Return**: The lower case equivalent of the character. If the character isn't upper case, returns the character unchanged.

- **`int     ft_isupper(char character);`**
  - **Description**: Checks if a character is upper case.
  - **Parameter**: `character` - The character.
  - **Return**: `1` if it's upper case, `0` if it's not.

- **`int     ft_islower(char character);`**
  - **Description**: Checks if a character is lower case.
  - **Parameter**: `character` - The character.
  - **Return**: `1` if it's lower case, `0` if it's not.

- **`int     ft_isalpha(char character);`**
  - **Description**: Checks if a character is alphabetic.
  - **Parameter**: `character` - The character.
  - **Return**: `1` if it's alphabetic, `0` if it's not.

- **`int     ft_isdigit(char character);`**
  - **Description**: Checks if a character is a digit.
  - **Parameter**: `character` - The character.
  - **Return**: `1` if it's a digit, `0` if it's not.

- **`int     ft_isalnum(char character);`**
  - **Description**: Checks if a character is alphanumeric.
  - **Parameter**: `character` - The character.
  - **Return**: `1` if it's alphanumeric, `0` if it's not.

- **`int     ft_isascii(char character);`**
  - **Description**: Checks if a character is ASCII.
  - **Parameter**: `character` - The character.
  - **Return**: `1` if it's ASCII, `0` if it's not.

- **`int     ft_isprint(char c);`**
  - **Description**: Checks if a character is printable.
  - **Parameter**: `c` - The character.
  - **Return**: `1` if it's printable, `0` if it's not.

#### Memory Management Functions

- **`void    *ft_memset(void *b, int c, size_t len);`**
  - **Description**: Fills the first `len` bytes of the memory area pointed to by `b` with the constant byte `c`.

- **`void    *ft_memcpy(void *dest, const void *src, size_t n);`**
  - **Description**: Copies `n` bytes from memory area `src` to memory area `dest`.

- **`void    *ft_memccpy(void *dest, const void *src, int c, size_t n);`**
  - **Description**: Copies bytes from `src` to `dest` until `c` is found or `n` bytes have been copied.

- **`void    *ft_memmove(void *dest, const void *src, size_t len);`**
  - **Description**: Moves `len` bytes from `src` to `dest`, handling overlapping regions correctly.

- **`void    *ft_memchr(const void *s, int c, size_t n);`**
  - **Description**: Scans the first `n` bytes of `s` for the first occurrence of `c`.

- **`int     ft_memcmp(const void *s1, const void *s2, size_t n);`**
  - **Description**: Compares `n` bytes of `s1` and `s2`.

#### String Manipulation Functions

- **`size_t  ft_strlen(const char *s);`**
  - **Description**: Computes the length of the string `s`, excluding the null terminator.

- **`char    *ft_strdup(const char *s1);`**
  - **Description**: Returns a pointer to a new string which is a duplicate of the string `s1`.

- **`char    *ft_strcpy(char *dest, const char *src);`**
  - **Description**: Copies the string `src` to `dest`, including the null terminator.

- **`char    *ft_strncpy(char *dest, const char *src, size_t n);`**
  - **Description**: Copies up to `n` characters from `src` to `dest`.

- **`char    *ft_strcat(char *dest, const char *src);`**
  - **Description**: Appends the string `src` to the end of `dest`.

- **`char    *ft_strncat(char *dest, const char *src, size_t n);`**
  - **Description**: Appends up to `n` characters from `src` to the end of `dest`.

- **`char    *ft_strchr(const char *s, int c);`**
  - **Description**: Locates the first occurrence of `c` in the string `s`.

- **`char    *ft_strrchr(const char *s, int c);`**
  - **Description**: Locates the last occurrence of `c` in the string `s`.

- **`int     ft_strcmp(const char *s1, const char *s2);`**
  - **Description**: Compares the strings `s1` and `s2`.

- **`int     ft_strncmp(const char *s1, const char *s2, size_t n);`**
  - **Description**: Compares the first `n` characters of `s1` and `s2`.

- **`char    *ft_strstr(const char *haystack, const char *needle);`**
  - **Description**: Finds the first occurrence of `needle` in `haystack`.

- **`char    *ft_strnstr(const char *haystack, const char *needle, size_t len);`**
  - **Description**: Finds the first occurrence of `needle` in `haystack`, searching at most `len` characters.

- **`int     ft_atoi(const char *str);`**
  - **Description**: Converts the initial portion of the string pointed to by `str` to an integer.

#### List Functions

- **`t_list  *ft_lstnew(void *content);`**
  - **Description**: Creates a new list node with the provided content.

- **`void    ft_lstadd_front(t_list **lst, t_list *new);`**
  - **Description**: Adds the node `new` at the beginning of the list.

- **`int     ft_lstsize(t_list *lst);`**
  - **Description**: Counts the number of nodes in the list.

- **`t_list  *ft_lstlast(t_list *lst);`**
  - **Description**: Returns the last node of the list.

- **`void    ft_lstadd_back(t_list **lst, t_list *new);`**
  - **Description**: Adds the node `new` at the end of the list.

- **`void    ft_lstdelone(t_list *lst, void (*del)(void*));`**
  - **Description**: Deletes the given node `lst` and frees its content.

- **`void    ft_lstclear(t_list **lst, void (*del)(void*));`**
  - **Description**: Deletes and frees all nodes in the list.

- **`void    ft_lstiter(t_list *lst, void (*f)(void *));`**
  - **Description**: Iterates through the list and applies the function `f` to each node's content.

- **`t_list  *ft_lstmap(t_list *lst, void *(*f)(void *), void (*del)(void *));`**
  - **Description**: Creates a new list by applying function `f` to each node's content of `lst`, using `del` to delete content if necessary.

#### Custom `printf` Functions

- **`int             ft_printf(const char *format, ...);`**
  - **Description**: A custom implementation of a printf-like function that supports various format specifiers, including:
    - `%c`: Character
    - `%s`: String
    - `%p`: Pointer
    - `%d`: Integer
    - `%i`: Integer
    - `%u`: Unsigned integer
    - `%x`: Lowercase hexadecimal
    - `%X`: Uppercase hexadecimal
    - `%%`: Percentage sign

- **`void    ft_pf_ptr(va_list args, int *count);`**
  - **Description**: Prints a pointer as a hexadecimal value, prepended by "0x".

- **`void    ft_pf_char(va_list args, int *count);`**
  - **Description**: Prints a character from the variadic argument list.

- **`void    ft_pf_str(va_list args, int *count);`**
  - **Description**: Prints a string from the variadic argument list.

- **`void    ft_pf_ph_str(char const ph, va_list args, int *i, int *count);`**
  - **Description**: Handles a string format specifier.

- **`void    ft_pf_int(va_list args, int *count);`**
  - **Description**: Prints an integer value from a variadic argument list.

- **`void    ft_pf_uns_int(va_list args, int *count);`**
  - **Description**: Prints an unsigned integer from a variadic argument list.

- **`void    ft_pf_hex(va_list args, char format, int *count);`**
  - **Description**: Prints a hexadecimal value (lowercase or uppercase).

#### Get Next Line Functions

- **`char    *ft_gnl(int fd);`**
  - **Description**: Reads a line from the specified file descriptor and returns it as a dynamically allocated string.

- **`char    *ft_gnl_contains(const char *string, char character);`**
  - **Description**: Checks if a character is present in a string.
  - **Parameter**: `string` - The string to search within. `character` - The character to search for.
  - **Return**: A pointer to the first occurrence of the character in the string, or NULL if the character is not found or the string is NULL.

- **`size_t  ft_gnl_length(const char *string);`**
  - **Description**: Computes the length of a string.
  - **Parameter**: `string` - The string whose length is to be calculated.
  - **Return**: The length of the string, or 0 if the string is NULL.

- **`char    *ft_gnl_concat(const char *source, const char *destination);`**
  - **Description**: Concatenates two strings.
  - **Parameter**: `source` - The string to append to the destination. `destination` - The string to which the source will be appended.
  - **Return**: A pointer to the newly created string containing the concatenation, or NULL if either string is NULL or if memory allocation fails.

- **`char    *ft_gnl_copy(const char *string);`**
  - **Description**: Creates a copy of a string.
  - **Parameter**: `string` - The string to copy.
  - **Return**: A pointer to the newly allocated string containing the copy, or NULL if the input string is NULL or if memory allocation fails.

- **`char    *ft_gnl_cut(const char *string, size_t start, size_t length);`**
  - **Description**: Cuts a substring from a given string.
  - **Parameter**: `string` - The original string to cut from. `start` - The starting index from which to cut. `length` - The number of characters to cut.
  - **Return**: A pointer to the newly allocated string containing the cut portion, or NULL if the original string is NULL or if memory allocation fails.

---
