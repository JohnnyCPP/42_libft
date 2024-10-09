# Data Structure Index

Here are the data structures with brief descriptions:

::: DoxyCompactList
:::

# File Index

Here is a list of all documented files with brief descriptions:

::: DoxyCompactList
:::

# Data Structure Documentation

::: {#structs__list}
:::

[]{#structs__list label="structs__list"}

Structure representing a node in a linked list.

#include $<$libft.h$>$

::: DoxyCompactItemize
[]{#structs__list_ab5d7894166d820576114e85fe250d014
label="structs__list_ab5d7894166d820576114e85fe250d014"} void $\ast$
**data**

[]{#structs__list_a33fc7534979b3c84b0645aadf3aefc0d
label="structs__list_a33fc7534979b3c84b0645aadf3aefc0d"} struct
[s_list](#structs__list) $\ast$ **next_node**
:::

Structure representing a node in a linked list.

The node contains a pointer to data of any type, and a pointer to the
next node in the list.

The documentation for this struct was generated from the following file:

::: DoxyCompactItemize
include/[libft.h](#libft_8h)
:::

# File Documentation

::: {#libft_8h}
:::

[]{#libft_8h label="libft_8h"}

Contains function declarations for the Libft.

#include $<$unistd.h$>$ #include $<$stdlib.h$>$ #include $<$limits.h$>$
#include $<$stdarg.h$>$

::: DoxyCompactItemize
struct [s_list](#structs__list)

::: DoxyCompactList
*Structure representing a node in a linked list.*
:::
:::

::: DoxyCompactItemize
[]{#libft_8h_ab35fccb34c6d5687da3115b8de46cc8c
label="libft_8h_ab35fccb34c6d5687da3115b8de46cc8c"} #define
**NULL_POINTER** \"(nil)\"

[]{#libft_8h_a17fb3f476e5f25b7861908ed4a32a718
label="libft_8h_a17fb3f476e5f25b7861908ed4a32a718"} #define
**LAST_FD** 256

[]{#libft_8h_a6b20d41d6252e9871430c242cb1a56e7
label="libft_8h_a6b20d41d6252e9871430c242cb1a56e7"} #define
**BUFFER_SIZE** 1
:::

::: DoxyCompactItemize
typedef struct [s_list](#structs__list)
[t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795)

::: DoxyCompactList
*Structure representing a node in a linked list.*
:::
:::

::: DoxyCompactItemize
int [ft_isupper](#libft_8h_a41f1bf2cecba56261e8067a453db4e91) (char
character)

::: DoxyCompactList
*Checks if a character is upper case.*
:::

int [ft_islower](#libft_8h_a555e54a664b79600af2406fc88201e32) (char
character)

::: DoxyCompactList
*Checks if a character is lower case.*
:::

int [ft_isalpha](#libft_8h_a6e00eae34a6a78f2e8d776f98243fd4e) (char
character)

::: DoxyCompactList
*Checks if a character is alphabetic.*
:::

int [ft_isdigit](#libft_8h_ab87da6c8abda53021710bfad2389170f) (char
character)

::: DoxyCompactList
*Checks if a character is a digit.*
:::

int [ft_isalnum](#libft_8h_adccebec4f5c5e2e644cd0a74e5f6aebe) (char
character)

::: DoxyCompactList
*Checks if a character is alphanumeric.*
:::

int [ft_isascii](#libft_8h_a17e0582f57ee9262abe4ac8c47385777) (char
character)

::: DoxyCompactList
*Checks if a character is ASCII.*
:::

int [ft_isprint](#libft_8h_aaffebed55c6039521c921974ec1b5cf3) (char c)

::: DoxyCompactList
*Checks if a character is printable.*
:::

size_t [ft_strlen](#libft_8h_aa54248218dc266f260bc074e4dce0245) (const
char $\ast$character)

::: DoxyCompactList
*Calculates the length of a string.*
:::

void $\ast$ [ft_memset](#libft_8h_a43cc85e4cca6808b987693ddcda18d6e)
(void $\ast$buffer, int character, size_t length)

::: DoxyCompactList
*Sets a block of memory to a specific value over a defined length.*
:::

void [ft_bzero](#libft_8h_ab500eb513c0c332a4ad7ff87a4b7e45a) (void
$\ast$buffer, size_t length)

::: DoxyCompactList
*Sets a block of memory to zero over a defined length.*
:::

void $\ast$ [ft_memcpy](#libft_8h_a21797ba606be6e39790289c969c0f2e5)
(void $\ast$destination, const void $\ast$source, size_t length)

::: DoxyCompactList
*Copies memory from a source to a destination over a defined length.*
:::

void $\ast$ [ft_memmove](#libft_8h_a1b30746b78c66da11b8a8bd4d9c2f902)
(void $\ast$destination, const void $\ast$source, size_t length)

::: DoxyCompactList
*Safe memory-moving function that handles memory overlapping.*
:::

size_t [ft_strlcpy](#libft_8h_a3750f18640d704767c76cef11b8246b6) (char
$\ast$destination, const char $\ast$source, size_t length)

::: DoxyCompactList
*Copies a string from source to destination.*
:::

size_t [ft_strlcat](#libft_8h_a1fe99981839db735d6e195d8ec96f8fc) (char
$\ast$destination, const char $\ast$source, size_t length)

::: DoxyCompactList
*Appends the source string to the destination string.*
:::

int [ft_toupper](#libft_8h_a907feb90b929e7bc67671b4e009a1884) (int
character)

::: DoxyCompactList
*Converts a lower case character to its upper case equivalent.*
:::

int [ft_tolower](#libft_8h_a91fb5059ccb8a44e7e6cbbe8b5bbbfa3) (int
character)

::: DoxyCompactList
*Converts an upper case character to its lower case equivalent.*
:::

char $\ast$ [ft_strchr](#libft_8h_a10a131efee4ba403f352bbe4c280c093)
(const char $\ast$string, int character)

::: DoxyCompactList
*Locates the first occurrence of a character in a string.*
:::

char $\ast$ [ft_strrchr](#libft_8h_a6293eaf34272bef4fce98e27edb3f43b)
(const char $\ast$string, int character)

::: DoxyCompactList
*Locates the last occurrence of a character in a string.*
:::

size_t [ft_strncmp](#libft_8h_ac860595580d7b5d2f3e5dc5620c2a645) (const
char $\ast$ptr_find, const char $\ast$ptr_str, size_t length)

::: DoxyCompactList
*Compares two strings up to a specified amount of characters.*
:::

void $\ast$ [ft_memchr](#libft_8h_af45b645f1578120eb25818a0d935c326)
(const void $\ast$ptr_str, int character, size_t length)

::: DoxyCompactList
*Searches for the first occurrence of a byte in a memory block.*
:::

int [ft_memcmp](#libft_8h_a65321be8766b1b340b6784788931f27c) (const void
$\ast$ptr_find, const void $\ast$ptr_str, size_t length)

::: DoxyCompactList
*Compares two memory blocks byte by byte.*
:::

char $\ast$ [ft_strnstr](#libft_8h_a8b5607f682467c782ab46cb691adcbcb)
(const char $\ast$string, const char $\ast$to_find, size_t length)

::: DoxyCompactList
*Searches for a substring in a string up to a specified length.*
:::

int [ft_atoi](#libft_8h_afbc2b2c0623b091d1466510737121775) (const char
$\ast$value)

::: DoxyCompactList
*Converts a string to an integer.*
:::

void $\ast$ [ft_calloc](#libft_8h_a6de8cb956a01c662581c6f77fcc901c3)
(size_t amount, size_t size)

::: DoxyCompactList
*Allocates memory for an array and initializes all bytes to zero.*
:::

char $\ast$ [ft_strdup](#libft_8h_a2654424fa992297acc5aca714e143cc5)
(const char $\ast$string)

::: DoxyCompactList
*Duplicates a string by allocating sufficient memory for it.*
:::

char $\ast$ [ft_substr](#libft_8h_a71f65d4907d37d5991f240bb3d0cbb45)
(const char $\ast$string, unsigned int start, size_t length)

::: DoxyCompactList
*Extracts a substring from a string.*
:::

char $\ast$ [ft_strjoin](#libft_8h_a32687c68baf426db779dea923df0df97)
(const char $\ast$string, const char $\ast$to_join)

::: DoxyCompactList
*Joins two strings into a new allocated string.*
:::

char $\ast$ [ft_strtrim](#libft_8h_a8481379d0d903f3623719ff94bbf484e)
(const char $\ast$string, const char $\ast$characters)

::: DoxyCompactList
*Trims leading and trailing characters from a string.*
:::

char $\ast$$\ast$
[ft_split](#libft_8h_a4e6950fb2e94c5d0f81eb7d789b9e6e7) (const char
$\ast$string, const char delim)

::: DoxyCompactList
*Splits a string into an array of substrings based on a delimiter.*
:::

char $\ast$ [ft_itoa](#libft_8h_a2a5fc0f56e2be4d102e4cabb3d439eee) (int
value)

::: DoxyCompactList
*Converts an integer to its string representation.*
:::

char $\ast$ [ft_strmapi](#libft_8h_ac98bb600791efbd136bf8339e0702485)
(const char $\ast$string, char($\ast$function)(unsigned int, char))

::: DoxyCompactList
*Applies a function to each character of a string.*
:::

void [ft_striteri](#libft_8h_a06bd1d6dc761319349406859be00fd61) (char
$\ast$string, void($\ast$function)(unsigned int, char $\ast$))

::: DoxyCompactList
*Modifies a string applying a function to each character.*
:::

void [ft_putchar_fd](#libft_8h_a0db039bfaee123d2f651cd0713c032e7) (char
character, int file_descriptor)

::: DoxyCompactList
*Writes a character to a file descriptor.*
:::

void [ft_putstr_fd](#libft_8h_abf0755477514b27264f30eea5b854fed) (char
$\ast$string, int file_descriptor)

::: DoxyCompactList
*Writes a string to a file descriptor.*
:::

void [ft_putendl_fd](#libft_8h_a40751d8db789fd8d8e9aacba8909a6f5) (char
$\ast$string, int file_descriptor)

::: DoxyCompactList
*Writes a string to a file descriptor, followed by a newline.*
:::

void [ft_putnbr_fd](#libft_8h_a9f94d5cc92061a7ee83f8c6da5ef3698) (int
value, int file_descriptor)

::: DoxyCompactList
*Outputs an integer, as a string, to a file descriptor.*
:::

[t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$
[ft_list_new](#libft_8h_abe95f8ff0feeac506ce998821ea21fa5) (void
$\ast$data)

::: DoxyCompactList
*Creates a new list node with the provided data.*
:::

void [ft_list_add_front](#libft_8h_a5e4418b7a3eb6e65425e111f1c54e491)
([t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$$\ast$list,
[t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$new_node)

::: DoxyCompactList
*Adds a new node to the front of the linked list.*
:::

int [ft_list_size](#libft_8h_a2c8bf41df06761cbd544e51ff95bc935)
([t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$list)

::: DoxyCompactList
*Calculates the number of nodes in a linked list.*
:::

[t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$
[ft_list_last](#libft_8h_a1dc51110a3dd543915d4137085496a9b)
([t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$list)

::: DoxyCompactList
*Finds the last node in a linked list.*
:::

void [ft_list_add_back](#libft_8h_a724d9cb8ce230fc726be7e8dfb2ff9e3)
([t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$$\ast$list,
[t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$new_node)

::: DoxyCompactList
*Adds a node at the end of a linked list.*
:::

void [ft_list_delete_one](#libft_8h_acbad8081a0ba7091cb53e1fc3511b4b2)
([t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$list,
void($\ast$function)(void $\ast$))

::: DoxyCompactList
*Deletes a node from a linked list.*
:::

void [ft_list_clear](#libft_8h_af410b9e16a8bc5f3a5f2305db1dc54ff)
([t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$$\ast$list,
void($\ast$function)(void $\ast$))

::: DoxyCompactList
*Clears a list, freeing all its nodes.*
:::

void [ft_list_iterate](#libft_8h_a2e59a560415e35b2a110dfdc4c46a1ea)
([t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$list,
void($\ast$function)(void $\ast$))

::: DoxyCompactList
*Applies a function to the data of each node in a linked list.*
:::

[t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$
[ft_list_map](#libft_8h_a31e8b1a831d5bde2cde6ac53596a219e)
([t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$list, void
$\ast$($\ast$f)(void $\ast$), void($\ast$d)(void $\ast$))

::: DoxyCompactList
*Creates a modified copy of a linked list.*
:::

void [ft_pf_ptr](#libft_8h_a7271bea0b6adb43ebdc22fc275694218) (va_list
args, int $\ast$count)

::: DoxyCompactList
*Prints a pointer as a hexadecimal value, prepended by \"0x\".*
:::

void [ft_pf_char](#libft_8h_a39d4f5727b0c5d00104d44fb27ddd419) (va_list
args, int $\ast$count)

::: DoxyCompactList
*Prints a character from a variadic argument list.*
:::

void [ft_pf_str](#libft_8h_aa3c88d49f6a5ef50917abf6425b0cfdd) (va_list
args, int $\ast$count)

::: DoxyCompactList
*Prints a string from a variadic argument list.*
:::

void [ft_pf_ph_str](#libft_8h_a27b932cba249b5673541f1c151f759c2) (char
const ph, va_list args, int $\ast$i, int $\ast$count)

::: DoxyCompactList
*Handles a string format specifier.*
:::

void [ft_pf_int](#libft_8h_aacb14fe46e5c2d17da596a70cb0d7b1d) (va_list
args, int $\ast$count)

::: DoxyCompactList
*Prints an integer value from a variadic argument list.*
:::

void [ft_pf_uns_int](#libft_8h_adf1847aadd8f6d9dda03c10846ea3dc3)
(va_list args, int $\ast$count)

::: DoxyCompactList
*Prints an unsigned integer from a variadic argument list.*
:::

void [ft_pf_ph_int](#libft_8h_ade70ec8220b6465af4a5716a0e20568c) (char
const ph, va_list args, int $\ast$i, int $\ast$count)

::: DoxyCompactList
*Handles a numeric format specifier.*
:::

void [ft_pf_ph_percentage](#libft_8h_a033bf9fd5711547f2e044751f95db4ed)
(int $\ast$i, int $\ast$count)

::: DoxyCompactList
*Prints a percentage sign and updates the counters.*
:::

void [ft_pf_lower_hex](#libft_8h_ab91de12492786ac2ee705b34815acdef)
(va_list args, int $\ast$count)

::: DoxyCompactList
*Prints the (lower) hexadecimal representation of an unsigned integer.*
:::

void [ft_pf_upper_hex](#libft_8h_a2e34e514b02a9fe5ec7ace78478b7969)
(va_list args, int $\ast$count)

::: DoxyCompactList
*Prints the (upper) hexadecimal representation of an unsigned integer.*
:::

void [ft_pf_ph_base](#libft_8h_ab7dcd687e96bc86aa2442368de6adb6d) (char
const ph, va_list args, int $\ast$i, int $\ast$count)

::: DoxyCompactList
*Handles a base format specifier.*
:::

void [ft_pf_ph_default](#libft_8h_a1be9049225e188a1ecc38d3a58a61142)
(int $\ast$i, int $\ast$count)

::: DoxyCompactList
*Handles the printing of a literal percentage sign .*
:::

int [ft_printf](#libft_8h_ae76f70badadcc67ba651a5f68f0ef3e8) (char const
$\ast$format,\...)

::: DoxyCompactList
*Custom implementation of a printf-like function.*
:::

char $\ast$
[ft_gnl_contains](#libft_8h_a5443584d438c7aa62503f5a1465348f6) (const
char $\ast$string, char character)

::: DoxyCompactList
*Checks if a character is present in a string.*
:::

size_t [ft_gnl_length](#libft_8h_acf38a69ca789f2ba94fa27f34d245770)
(const char $\ast$string)

::: DoxyCompactList
*Computes the length of a string.*
:::

char $\ast$ [ft_gnl_concat](#libft_8h_ad4bbf07dbbb4ab92017548b2712bf96a)
(const char $\ast$source, const char $\ast$destination)

::: DoxyCompactList
*Concatenates two strings.*
:::

char $\ast$ [ft_gnl_copy](#libft_8h_a94e98396fae54799f9238c3a621d2f76)
(const char $\ast$string)

::: DoxyCompactList
*Creates a copy of a string.*
:::

char $\ast$ [ft_gnl_cut](#libft_8h_a8d01547ab457caf07c093c0b720fc9e5)
(const char $\ast$string, size_t start, size_t length)

::: DoxyCompactList
*Cuts a substring from a given string.*
:::

char $\ast$ [ft_gnl](#libft_8h_a1414e908b987bfd7b44f821164ac7b61) (int
fd)

::: DoxyCompactList
*Reads a line from a file descriptor.*
:::
:::

Contains function declarations for the Libft.

The Libft is the low-level development of Standard C Library functions
to leverage in the future.

::: DoxyAuthor
Author jonnavar
:::

::: DoxyVersion
Version giraffe-spider
:::

[]{#libft_8h_aefde00352c5326bb1c28ebd4404c4795
label="libft_8h_aefde00352c5326bb1c28ebd4404c4795"} typedef struct
[s_list](#structs__list)
[t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795)

Structure representing a node in a linked list.

The node contains a pointer to data of any type, and a pointer to the
next node in the list.

[]{#libft_8h_afbc2b2c0623b091d1466510737121775
label="libft_8h_afbc2b2c0623b091d1466510737121775"} int ft_atoi (

::: DoxyParamCaption
value
:::

)

Converts a string to an integer.

::: DoxyParams
Parameters *value* & A pointer to the string containing the number to be
converted.\
:::

::: DoxyReturn
Returns The integer value represented by the string,   or 0 if the
string doesnt contain a valid number.
:::

This function converts the initial portion of the string pointed to by
\"value\" to an integer. It handles optional leading spaces, an optional
sign (+ or -), and numeric characters.

[]{#libft_8h_ab500eb513c0c332a4ad7ff87a4b7e45a
label="libft_8h_ab500eb513c0c332a4ad7ff87a4b7e45a"} void ft_bzero (

::: DoxyParamCaption
buffer,

length
:::

)

Sets a block of memory to zero over a defined length.

::: DoxyParams
Parameters *buffer* & Pointer to the starting position of the memory
block.\
*length* & Specifies how many bytes of memory should be set.\
:::

[]{#libft_8h_a6de8cb956a01c662581c6f77fcc901c3
label="libft_8h_a6de8cb956a01c662581c6f77fcc901c3"} void $\ast$
ft_calloc (

::: DoxyParamCaption
amount,

size
:::

)

Allocates memory for an array and initializes all bytes to zero.

::: DoxyParams
Parameters *amount* & The number of elements to allocate.\
*size* & The size of each element in bytes.\
:::

::: DoxyReturn
Returns A pointer to the allocated memory, or NULL if the allocation
fails.
:::

[]{#libft_8h_a1414e908b987bfd7b44f821164ac7b61
label="libft_8h_a1414e908b987bfd7b44f821164ac7b61"} char $\ast$ ft_gnl (

::: DoxyParamCaption
fd
:::

)

Reads a line from a file descriptor.

::: DoxyParams
Parameters *fd* & The file descriptor to read from.\
:::

::: DoxyReturn
Returns A pointer to the line read from the file, or NULL if an error
occurs or if the end of the file is reached.
:::

This function reads a line from the specified file descriptor and
returns it as a dynamically allocated string.

It uses a static buffer to maintain the state across multiple calls,
allowing for the reading of lines in sequence.

[]{#libft_8h_ad4bbf07dbbb4ab92017548b2712bf96a
label="libft_8h_ad4bbf07dbbb4ab92017548b2712bf96a"} char $\ast$
ft_gnl_concat (

::: DoxyParamCaption
source,

destination
:::

)

Concatenates two strings.

::: DoxyParams
Parameters *source* & The string to append to the destination.\
*destination* & The string to which the source will be appended.\
:::

::: DoxyReturn
Returns A pointer to the newly created string containing the
concatenation, or NULL if either string is NULL or if memory allocation
fails.
:::

[]{#libft_8h_a5443584d438c7aa62503f5a1465348f6
label="libft_8h_a5443584d438c7aa62503f5a1465348f6"} char $\ast$
ft_gnl_contains (

::: DoxyParamCaption
string,

character
:::

)

Checks if a character is present in a string.

::: DoxyParams
Parameters *string* & The string to search within.\
*character* & The character to search for.\
:::

::: DoxyReturn
Returns A pointer to the first occurrence of the character in the
string, or NULL if the character is not found or the string is NULL.
:::

This function searches for the first occurrence of a specified character
in a given string.

If found, it returns a pointer to that character in the string,
otherwise, it returns NULL.

[]{#libft_8h_a94e98396fae54799f9238c3a621d2f76
label="libft_8h_a94e98396fae54799f9238c3a621d2f76"} char $\ast$
ft_gnl_copy (

::: DoxyParamCaption
string
:::

)

Creates a copy of a string.

::: DoxyParams
Parameters *string* & The string to copy.\
:::

::: DoxyReturn
Returns A pointer to the newly allocated string containing the copy, or
NULL if the input string is NULL or if memory allocation fails. This
function allocates memory for a new string and copies the contents of
the given string into it, including the null terminator.
:::

[]{#libft_8h_a8d01547ab457caf07c093c0b720fc9e5
label="libft_8h_a8d01547ab457caf07c093c0b720fc9e5"} char $\ast$
ft_gnl_cut (

::: DoxyParamCaption
string,

start,

length
:::

)

Cuts a substring from a given string.

::: DoxyParams
Parameters *string* & The original string to cut from.\
*start* & The starting index from which to cut.\
*length* & The number of characters to cut.\
:::

::: DoxyReturn
Returns A pointer to the newly allocated string containing the cut
portion, or NULL if the original string is NULL or if memory allocation
fails.
:::

This function allocates memory for and returns a new string that
contains a specified portion of the original string, defined by the
start index and length.

[]{#libft_8h_acf38a69ca789f2ba94fa27f34d245770
label="libft_8h_acf38a69ca789f2ba94fa27f34d245770"} size_t ft_gnl_length
(

::: DoxyParamCaption
string
:::

)

Computes the length of a string.

::: DoxyParams
Parameters *string* & The string whose length is to be calculated.\
:::

::: DoxyReturn
Returns The length of the string, or 0 if the string is NULL.
:::

This function calculates the number of characters in a string, excluding
the null terminator.

[]{#libft_8h_adccebec4f5c5e2e644cd0a74e5f6aebe
label="libft_8h_adccebec4f5c5e2e644cd0a74e5f6aebe"} int ft_isalnum (

::: DoxyParamCaption
character
:::

)

Checks if a character is alphanumeric.

::: DoxyParams
Parameters *character* & The character.\
:::

::: DoxyReturn
Returns 1 if its alphanumeric, 0 if its not.
:::

[]{#libft_8h_a6e00eae34a6a78f2e8d776f98243fd4e
label="libft_8h_a6e00eae34a6a78f2e8d776f98243fd4e"} int ft_isalpha (

::: DoxyParamCaption
character
:::

)

Checks if a character is alphabetic.

::: DoxyParams
Parameters *character* & The character.\
:::

::: DoxyReturn
Returns 1 if its alphabetic, 0 if its not.
:::

[]{#libft_8h_a17e0582f57ee9262abe4ac8c47385777
label="libft_8h_a17e0582f57ee9262abe4ac8c47385777"} int ft_isascii (

::: DoxyParamCaption
character
:::

)

Checks if a character is ASCII.

::: DoxyParams
Parameters *character* & The character.\
:::

::: DoxyReturn
Returns 1 if its ASCII, 0 if its not.
:::

[]{#libft_8h_ab87da6c8abda53021710bfad2389170f
label="libft_8h_ab87da6c8abda53021710bfad2389170f"} int ft_isdigit (

::: DoxyParamCaption
character
:::

)

Checks if a character is a digit.

::: DoxyParams
Parameters *character* & The character.\
:::

::: DoxyReturn
Returns 1 if its a digit, 0 if its not.
:::

[]{#libft_8h_a555e54a664b79600af2406fc88201e32
label="libft_8h_a555e54a664b79600af2406fc88201e32"} int ft_islower (

::: DoxyParamCaption
character
:::

)

Checks if a character is lower case.

::: DoxyParams
Parameters *character* & The character.\
:::

::: DoxyReturn
Returns 1 if its lower case, 0 if its not.
:::

[]{#libft_8h_aaffebed55c6039521c921974ec1b5cf3
label="libft_8h_aaffebed55c6039521c921974ec1b5cf3"} int ft_isprint (

::: DoxyParamCaption
c
:::

)

Checks if a character is printable.

::: DoxyParams
Parameters *character* & The character.\
:::

::: DoxyReturn
Returns 1 if its printable, 0 if its not.
:::

[]{#libft_8h_a41f1bf2cecba56261e8067a453db4e91
label="libft_8h_a41f1bf2cecba56261e8067a453db4e91"} int ft_isupper (

::: DoxyParamCaption
character
:::

)

Checks if a character is upper case.

::: DoxyParams
Parameters *character* & The character.\
:::

::: DoxyReturn
Returns 1 if its upper case, 0 if its not.
:::

[]{#libft_8h_a2a5fc0f56e2be4d102e4cabb3d439eee
label="libft_8h_a2a5fc0f56e2be4d102e4cabb3d439eee"} char $\ast$ ft_itoa
(

::: DoxyParamCaption
value
:::

)

Converts an integer to its string representation.

::: DoxyParams
Parameters *value* & The integer to be converted.\
:::

::: DoxyReturn
Returns A pointer to the string containing the representation of the
integer, or NULL if memory allocation fails.
:::

This function takes an integer \"value\" and converts it to a
dynamically allocated string representation.

The string is null-terminated and can represent both positive and
negative integers.

[]{#libft_8h_a724d9cb8ce230fc726be7e8dfb2ff9e3
label="libft_8h_a724d9cb8ce230fc726be7e8dfb2ff9e3"} void
ft_list_add_back (

::: DoxyParamCaption
list,

new_node
:::

)

Adds a node at the end of a linked list.

::: DoxyParams
Parameters *list* & A double pointer to the first node of the linked
list.\
*new_node* & The node to add to the end of the list.\
:::

This function traverses the linked list to find the last node and adds
the provided node at the end.

If the list is empty, the new node becomes the first node of the list.

[]{#libft_8h_a5e4418b7a3eb6e65425e111f1c54e491
label="libft_8h_a5e4418b7a3eb6e65425e111f1c54e491"} void
ft_list_add_front (

::: DoxyParamCaption
list,

new_node
:::

)

Adds a new node to the front of the linked list.

::: DoxyParams
Parameters *list* & A double pointer to the head of the list.\
*new_node* & The node to be added to the front of the list.\
:::

[]{#libft_8h_af410b9e16a8bc5f3a5f2305db1dc54ff
label="libft_8h_af410b9e16a8bc5f3a5f2305db1dc54ff"} void ft_list_clear (

::: DoxyParamCaption
list,

function )(void $\ast$)
:::

)

Clears a list, freeing all its nodes.

::: DoxyParams
Parameters *list* & A pointer to the head of the list.\
*function* & The function to apply to the data of each node.\
:::

This function iterates through each node of a linked list, applies the
function to the data in each node, and frees the memory of the node.

[]{#libft_8h_acbad8081a0ba7091cb53e1fc3511b4b2
label="libft_8h_acbad8081a0ba7091cb53e1fc3511b4b2"} void
ft_list_delete_one (

::: DoxyParamCaption
list,

function )(void $\ast$)
:::

)

Deletes a node from a linked list.

::: DoxyParams
Parameters *list* & The node to delete.\
*function* & A pointer to a function used to free the memory associated
with the nodes data.\
:::

This function frees the memory associated with the nodes data using the
provided function pointer and then frees the memory of the node.

[]{#libft_8h_a2e59a560415e35b2a110dfdc4c46a1ea
label="libft_8h_a2e59a560415e35b2a110dfdc4c46a1ea"} void ft_list_iterate
(

::: DoxyParamCaption
list,

function )(void $\ast$)
:::

)

Applies a function to the data of each node in a linked list.

::: DoxyParams
Parameters *list* & The head of the linked list.\
*function* & A function to apply to each nodes data.\
:::

This function traverses through the provided linked list and applies the
specified function to the data in each node.

[]{#libft_8h_a1dc51110a3dd543915d4137085496a9b
label="libft_8h_a1dc51110a3dd543915d4137085496a9b"}
[t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$
ft_list_last (

::: DoxyParamCaption
list
:::

)

Finds the last node in a linked list.

::: DoxyParams
Parameters *list* & A pointer to the head of the list.\
:::

::: DoxyReturn
Returns A pointer to the last node in the list, or NULL if the list is
empty.
:::

[]{#libft_8h_a31e8b1a831d5bde2cde6ac53596a219e
label="libft_8h_a31e8b1a831d5bde2cde6ac53596a219e"}
[t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$ ft_list_map
(

::: DoxyParamCaption
list,

f )(void $\ast$),

d )(void $\ast$)
:::

)

Creates a modified copy of a linked list.

::: DoxyParams
Parameters *list* & The original linked list.\
*f* & The function to apply to each nodes data.\
*d* & The function to free the data in case of an error.\
:::

::: DoxyReturn
Returns A new linked list with the transformed data, or NULL if memory
allocation fails.
:::

This function traverses the given linked list, applies the \"f\"
function to each nodes data, and creates a new list with the results.

If an error occurs during the creation of a new node, the new list is
cleared using the \"d\" function to free the memory of each nodes data.

[]{#libft_8h_abe95f8ff0feeac506ce998821ea21fa5
label="libft_8h_abe95f8ff0feeac506ce998821ea21fa5"}
[t_list](#libft_8h_aefde00352c5326bb1c28ebd4404c4795) $\ast$ ft_list_new
(

::: DoxyParamCaption
data
:::

)

Creates a new list node with the provided data.

::: DoxyParams
Parameters *data* & A pointer to the data to be stored in the node.\
:::

::: DoxyReturn
Returns A pointer to the new node, or NULL if the memory allocation
fails.
:::

[]{#libft_8h_a2c8bf41df06761cbd544e51ff95bc935
label="libft_8h_a2c8bf41df06761cbd544e51ff95bc935"} int ft_list_size (

::: DoxyParamCaption
list
:::

)

Calculates the number of nodes in a linked list.

::: DoxyParams
Parameters *list* & A pointer to the head of the list.\
:::

::: DoxyReturn
Returns The number of nodes in the list.
:::

[]{#libft_8h_af45b645f1578120eb25818a0d935c326
label="libft_8h_af45b645f1578120eb25818a0d935c326"} void $\ast$
ft_memchr (

::: DoxyParamCaption
ptr_str,

character,

length
:::

)

Searches for the first occurrence of a byte in a memory block.

::: DoxyParams
Parameters *ptr_str* & The memory block to search.\
*character* & The byte to search for, interpreted as an \"unsigned
char\".\
*length* & The amount of bytes to search in the memory block.\
:::

::: DoxyReturn
Returns A pointer to the first occurrence of \"character\" in the memory
block, or NULL if the byte isnt found within the specified length.
:::

This function scans the first \"length\" bytes of the memory area
pointed to by \"ptr_str\" for the first occurrence of the byte value
\"character\".

[]{#libft_8h_a65321be8766b1b340b6784788931f27c
label="libft_8h_a65321be8766b1b340b6784788931f27c"} int ft_memcmp (

::: DoxyParamCaption
ptr_find,

ptr_str,

length
:::

)

Compares two memory blocks byte by byte.

::: DoxyParams
Parameters *ptr_find* & The first memory block to compare.\
*ptr_str* & The second memory block to compare.\
*length* & The amount of bytes to compare in each memory block.\
:::

::: DoxyReturn
Returns An integer less than, equal to, or greater than zero if the
first block is found to be less than, equal to, or greater than the
second block.
:::

This function compares the first \"length\" bytes of the memory areas
\"ptr_find\" and \"ptr_str\".

[]{#libft_8h_a21797ba606be6e39790289c969c0f2e5
label="libft_8h_a21797ba606be6e39790289c969c0f2e5"} void $\ast$
ft_memcpy (

::: DoxyParamCaption
destination,

source,

length
:::

)

Copies memory from a source to a destination over a defined length.

::: DoxyParams
Parameters *destination* & Pointer to the memory area where the data is
copied.\
*source* & Pointer to the memory area from which data is copied.\
*length* & Amount of bytes to be copied.\
:::

::: DoxyReturn
Returns The \"destination\" pointer, after copying is done.
:::

[]{#libft_8h_a1b30746b78c66da11b8a8bd4d9c2f902
label="libft_8h_a1b30746b78c66da11b8a8bd4d9c2f902"} void $\ast$
ft_memmove (

::: DoxyParamCaption
destination,

source,

length
:::

)

Safe memory-moving function that handles memory overlapping.

::: DoxyParams
Parameters *destination* & Pointer to the memory area where the data is
moved.\
*source* & Pointer to the memory area from which data is moved.\
*length* & Amount of bytes to be moved.\
:::

::: DoxyReturn
Returns The \"destination\" pointer, after moving is done.
:::

Moves memory from a source to a destination over a defined length. It
ensures that data is copied correctly, even if the memory areas overlap.

The most important aspect is how it handles memory overlapping:

When the destination is lower than the source, copies forwards. When the
destination is higher than the source, copying in reverse ensures that
the source data isnt overwritten before its moved to the destination.

[]{#libft_8h_a43cc85e4cca6808b987693ddcda18d6e
label="libft_8h_a43cc85e4cca6808b987693ddcda18d6e"} void $\ast$
ft_memset (

::: DoxyParamCaption
buffer,

character,

length
:::

)

Sets a block of memory to a specific value over a defined length.

::: DoxyParams
Parameters *buffer* & Pointer to the starting position of the memory
block.\
*character* & The value to fill the memory block with.\
*length* & Specifies how many bytes of memory should be set.\
:::

::: DoxyReturn
Returns The original pointer to the block of memory.
:::

[]{#libft_8h_a39d4f5727b0c5d00104d44fb27ddd419
label="libft_8h_a39d4f5727b0c5d00104d44fb27ddd419"} void ft_pf_char (

::: DoxyParamCaption
args,

count
:::

)

Prints a character from a variadic argument list.

::: DoxyParams
Parameters *args* & The variadic argument list to retrieve the character
from.\
*count* & A pointer to the counter, updated with the number of
characters printed.\
:::

This function retrieves a character from the variadic argument list and
prints it using the \"ft_putchar_fd\" function.

It also increments the counter that tracks the number of printed
characters.

[]{#libft_8h_aacb14fe46e5c2d17da596a70cb0d7b1d
label="libft_8h_aacb14fe46e5c2d17da596a70cb0d7b1d"} void ft_pf_int (

::: DoxyParamCaption
args,

count
:::

)

Prints an integer value from a variadic argument list.

::: DoxyParams
Parameters *args* & The variadic argument list to retrieve the integer
from.\
*count* & A pointer to the counter, updated with the number of
characters printed.\
:::

This function retrieves an integer from the variadic argument list,
converts it to a string using \"ft_itoa\", and prints it to the standard
output using \"ft_putstr_fd\".

It also updates the count of printed characters by adding the length of
the printed string.

[]{#libft_8h_ab91de12492786ac2ee705b34815acdef
label="libft_8h_ab91de12492786ac2ee705b34815acdef"} void ft_pf_lower_hex
(

::: DoxyParamCaption
args,

count
:::

)

Prints the (lower) hexadecimal representation of an unsigned integer.

::: DoxyParams
Parameters *args* & The variable argument list from which to retrieve
the unsigned integer.\
*count* & A pointer to an integer representing the total number of
characters printed.\
:::

This function retrieves an unsigned integer from the argument list and
prints its hexadecimal representation using lower case letters.

[]{#libft_8h_ab7dcd687e96bc86aa2442368de6adb6d
label="libft_8h_ab7dcd687e96bc86aa2442368de6adb6d"} void ft_pf_ph_base (

::: DoxyParamCaption
ph,

args,

i,

count
:::

)

Handles a base format specifier.

::: DoxyParams
Parameters *ph* & The format specifier character.\
*args* & The variadic argument list from which the values are
retrieved.\
*i* & A pointer to the index of the format string.\
*count* & A pointer to the counter.\
:::

This function checks the \"ph\" format specifier and calls the
appropiate print function from the variadic argument list.

It also increments both the index and the count of printed characters.

It handles specifiers for lower, and upper hexadecimal formats.

[]{#libft_8h_a1be9049225e188a1ecc38d3a58a61142
label="libft_8h_a1be9049225e188a1ecc38d3a58a61142"} void
ft_pf_ph_default (

::: DoxyParamCaption
i,

count
:::

)

Handles the printing of a literal percentage sign .

::: DoxyParams
Parameters *i* & A pointer to an integer representing the current
index.\
*count* & A pointer to an integer representing the total number of
characters prined.\
:::

This function prints a character to the standard output and increments
both the index and the count of characters printed by one.

[]{#libft_8h_ade70ec8220b6465af4a5716a0e20568c
label="libft_8h_ade70ec8220b6465af4a5716a0e20568c"} void ft_pf_ph_int (

::: DoxyParamCaption
ph,

args,

i,

count
:::

)

Handles a numeric format specifier.

::: DoxyParams
Parameters *ph* & The format specifier character.\
*args* & The variadic argument list from which the values are
retrieved.\
*i* & A pointer to the index of the format string.\
*count* & A pointer to the counter.\
:::

This function checks the \"ph\" format specifier and calls the
appropiate print function from the variadic argument list.

It also increments both the index and the count of printed characters.

It handles specifiers for integer, and unsigned integer formats.

[]{#libft_8h_a033bf9fd5711547f2e044751f95db4ed
label="libft_8h_a033bf9fd5711547f2e044751f95db4ed"} void
ft_pf_ph_percentage (

::: DoxyParamCaption
i,

count
:::

)

Prints a percentage sign and updates the counters.

::: DoxyParams
Parameters *i* & A pointer to an integer representing the current
index.\
*count* & A pointer to an integer representing the total number of
characters printed.\
:::

This function increments the index counter by 2, outputs a percentage
sign to the standard output, and updates the character count to reflect
that one character has been printed.

[]{#libft_8h_a27b932cba249b5673541f1c151f759c2
label="libft_8h_a27b932cba249b5673541f1c151f759c2"} void ft_pf_ph_str (

::: DoxyParamCaption
ph,

args,

i,

count
:::

)

Handles a string format specifier.

::: DoxyParams
Parameters *ph* & The format specifier character.\
*args* & The variadic argument list from which the values are
retrieved.\
*i* & A pointer to the index of the format string.\
*count* & A pointer to the counter.\
:::

This function checks the \"ph\" format specifier and calls the
appropiate print function from the variadic argument list.

It also increments both the index and the count of printed characters.

It handles specifiers for character, string, and pointer formats.

[]{#libft_8h_a7271bea0b6adb43ebdc22fc275694218
label="libft_8h_a7271bea0b6adb43ebdc22fc275694218"} void ft_pf_ptr (

::: DoxyParamCaption
args,

count
:::

)

Prints a pointer as a hexadecimal value, prepended by \"0x\".

::: DoxyParams
Parameters *args* & The variadic argument list to retrieve the pointer
from.\
*count* & A pointer to the counter, updated with the number of
characters printed.\
:::

This function retrieves the pointer from a variadic argument list,
converts it to its hexadecimal representation, and prints it.

If the pointer is NULL, it prints \"(nil)\".

[]{#libft_8h_aa3c88d49f6a5ef50917abf6425b0cfdd
label="libft_8h_aa3c88d49f6a5ef50917abf6425b0cfdd"} void ft_pf_str (

::: DoxyParamCaption
args,

count
:::

)

Prints a string from a variadic argument list.

::: DoxyParams
Parameters *args* & The variadic argument list to retrieve the string
from.\
*count* & A pointer to the counter, updated with the number of
characters printed.\
:::

This function retrieves a string from the variadic argument list and
prints it using the \"ft_putstr_fd\" function.

It also increments the counter that tracks the number of printed
characters by the length of the string.

[]{#libft_8h_adf1847aadd8f6d9dda03c10846ea3dc3
label="libft_8h_adf1847aadd8f6d9dda03c10846ea3dc3"} void ft_pf_uns_int (

::: DoxyParamCaption
args,

count
:::

)

Prints an unsigned integer from a variadic argument list.

::: DoxyParams
Parameters *args* & The variadic argument list to retrieve the value
from.\
*count* & A pointer to the counter, updated with the number of
characters printed.\
:::

This function retrieves an unsigned integer from the variadic argument
list, converts it to a string, and prints it to the standard output.

[]{#libft_8h_a2e34e514b02a9fe5ec7ace78478b7969
label="libft_8h_a2e34e514b02a9fe5ec7ace78478b7969"} void ft_pf_upper_hex
(

::: DoxyParamCaption
args,

count
:::

)

Prints the (upper) hexadecimal representation of an unsigned integer.

::: DoxyParams
Parameters *args* & The variable argument list from which to retrieve
the unsigned integer.\
*count* & A pointer to an integer representing the total number of
characters printed.\
:::

This function retrieves an unsigned integer from the argument list and
prints its hexadecimal representation using upper case letters.

[]{#libft_8h_ae76f70badadcc67ba651a5f68f0ef3e8
label="libft_8h_ae76f70badadcc67ba651a5f68f0ef3e8"} int ft_printf (

::: DoxyParamCaption
format,

\...
:::

)

Custom implementation of a printf-like function.

::: DoxyParams
Parameters *format* & The format string containing plain characters and
placeholders for values to be printed.\
:::

::: DoxyReturn
Returns The total number of characters printed, or -1 if the format
string is NULL.
:::

This function processes a format string and prints the corresponding
characters and formatted values to the standard output.

It supports various format specifiers, including characters, strings,
integers, unsigned integers, and hexadecimal values.

[]{#libft_8h_a0db039bfaee123d2f651cd0713c032e7
label="libft_8h_a0db039bfaee123d2f651cd0713c032e7"} void ft_putchar_fd (

::: DoxyParamCaption
character,

file_descriptor
:::

)

Writes a character to a file descriptor.

::: DoxyParams
Parameters *character* & The character.\
*file_descriptor* & The file descriptor.\
:::

This function sends the \"character\" to the given \"file_descriptor\",
allowing for output to standard output, files, or other output streams.

[]{#libft_8h_a40751d8db789fd8d8e9aacba8909a6f5
label="libft_8h_a40751d8db789fd8d8e9aacba8909a6f5"} void ft_putendl_fd (

::: DoxyParamCaption
string,

file_descriptor
:::

)

Writes a string to a file descriptor, followed by a newline.

::: DoxyParams
Parameters *string* & The string.\
*file_descriptor* & The file descriptor.\
:::

This function outputs the given string to the specified file descriptor,
character by character, with a newline at the end.

If the string is NULL, the function does nothing.

[]{#libft_8h_a9f94d5cc92061a7ee83f8c6da5ef3698
label="libft_8h_a9f94d5cc92061a7ee83f8c6da5ef3698"} void ft_putnbr_fd (

::: DoxyParamCaption
value,

file_descriptor
:::

)

Outputs an integer, as a string, to a file descriptor.

::: DoxyParams
Parameters *value* & The integer.\
*file_descriptor* & The file descriptor.\
:::

This function converts an integer to a string and writes it to the
specified file descriptor.

It uses \"ft_itoa\" to perform the conversion, and it ensures the
allocated memory is freed after use.

[]{#libft_8h_abf0755477514b27264f30eea5b854fed
label="libft_8h_abf0755477514b27264f30eea5b854fed"} void ft_putstr_fd (

::: DoxyParamCaption
string,

file_descriptor
:::

)

Writes a string to a file descriptor.

::: DoxyParams
Parameters *string* & The string.\
*file_descriptor* & The file descriptor.\
:::

This function outputs the given string to the specified file descriptor,
character by character.

If the string is NULL, the function does nothing.

[]{#libft_8h_a4e6950fb2e94c5d0f81eb7d789b9e6e7
label="libft_8h_a4e6950fb2e94c5d0f81eb7d789b9e6e7"} char $\ast$$\ast$
ft_split (

::: DoxyParamCaption
string,

delim
:::

)

Splits a string into an array of substrings based on a delimiter.

::: DoxyParams
Parameters *string* & The string to be split.\
*delim* & The delimiter character used to split the string.\
:::

::: DoxyReturn
Returns A pointer to the array of substrings, or NULL if memory
allocation fails or if the input string is NULL.
:::

This function splits the given string \"string\" into multiple
substrings delimited by the character \"delim\".

The resulting substrings are stored in a newly allocated array of
strings, and the last element of the array is a NULL pointer to mark the
end.

[]{#libft_8h_a10a131efee4ba403f352bbe4c280c093
label="libft_8h_a10a131efee4ba403f352bbe4c280c093"} char $\ast$
ft_strchr (

::: DoxyParamCaption
string,

character
:::

)

Locates the first occurrence of a character in a string.

::: DoxyParams
Parameters *string* & The null-terminated string to be searched.\
*character* & The character.\
:::

::: DoxyReturn
Returns A pointer to the first occurrence of the character in the
string, or NULL if the character isnt found.
:::

[]{#libft_8h_a2654424fa992297acc5aca714e143cc5
label="libft_8h_a2654424fa992297acc5aca714e143cc5"} char $\ast$
ft_strdup (

::: DoxyParamCaption
string
:::

)

Duplicates a string by allocating sufficient memory for it.

::: DoxyParams
Parameters *string* & The string to be duplicated.\
:::

::: DoxyReturn
Returns A pointer to the duplicated string, or NULL if the input string
is NULL or memory allocation fails.
:::

This function allocates memory for a new string, copies the input string
into the allocated memory, and returns a pointer to the new string.

[]{#libft_8h_a06bd1d6dc761319349406859be00fd61
label="libft_8h_a06bd1d6dc761319349406859be00fd61"} void ft_striteri (

::: DoxyParamCaption
string,

function )(unsigned int, char $\ast$)
:::

)

Modifies a string applying a function to each character.

::: DoxyParams
Parameters *string* & The mutable string to be iterated over.\
*function* & A pointer to a function that takes an index and a pointer
to a character. This function can modify the original character.\
:::

This function iterates over each character of the input string, passing
both the characters index and a pointer to the character itself to the
specified function.

This allows the function to modify the original string.

[]{#libft_8h_a32687c68baf426db779dea923df0df97
label="libft_8h_a32687c68baf426db779dea923df0df97"} char $\ast$
ft_strjoin (

::: DoxyParamCaption
string,

to_join
:::

)

Joins two strings into a new allocated string.

::: DoxyParams
Parameters *string* & The first string.\
*to_join* & The string to append to the first string.\
:::

::: DoxyReturn
Returns A pointer to the allocated string containing both \"string\" and
\"to_join\", or NULL if memory allocation fails or any of the inputs is
NULL.
:::

This function concatenates the contents of \"string\" followed by
\"to_join\" into a newly allocated string.

[]{#libft_8h_a1fe99981839db735d6e195d8ec96f8fc
label="libft_8h_a1fe99981839db735d6e195d8ec96f8fc"} size_t ft_strlcat (

::: DoxyParamCaption
destination,

source,

length
:::

)

Appends the source string to the destination string.

::: DoxyParams
Parameters *destination* & The buffer containing the initial string.\
*source* & The string to append to the end of \"destination\".\
*length* & The total size of the destination buffer.\
:::

::: DoxyReturn
Returns The length of the string it tried to create. The initial length
of \"destination\" plus the length of \"source\".
:::

Ensures that the resulting string is null-terminated. Doesnt exceed the
buffer size specified by \"length\".

[]{#libft_8h_a3750f18640d704767c76cef11b8246b6
label="libft_8h_a3750f18640d704767c76cef11b8246b6"} size_t ft_strlcpy (

::: DoxyParamCaption
destination,

source,

length
:::

)

Copies a string from source to destination.

::: DoxyParams
Parameters *destination* & The buffer where the string will be copied.\
*source* & The string that will be copied.\
*length* & Total size of the destination buffer.\
:::

::: DoxyReturn
Returns The length of the source string.
:::

Ensures that the destination string is null-terminated. No more than
\"length - 1\" characters are copied to prevent overflow.

[]{#libft_8h_aa54248218dc266f260bc074e4dce0245
label="libft_8h_aa54248218dc266f260bc074e4dce0245"} size_t ft_strlen (

::: DoxyParamCaption
character
:::

)

Calculates the length of a string.

::: DoxyParams
Parameters *\[character\]* & A pointer to the first character of the
string.\
:::

::: DoxyReturn
Returns The length of the string.
:::

[]{#libft_8h_ac98bb600791efbd136bf8339e0702485
label="libft_8h_ac98bb600791efbd136bf8339e0702485"} char $\ast$
ft_strmapi (

::: DoxyParamCaption
string,

function )(unsigned int, char)
:::

)

Applies a function to each character of a string.

::: DoxyParams
Parameters *string* & The input string to be transformed.\
*function* & A pointer to a function that takes an index and a
character, returning a transformed character.\
:::

::: DoxyReturn
Returns A pointer to the string with transformed characters, or NULL if
memory allocation fails or if the input string or function is NULL.
:::

This function creates a new string by applying the function to each
character of the input string.

The function takes the index of the character and the character itself
as parameters and returns the transformed character.

The new string is dynamically allocated.

[]{#libft_8h_ac860595580d7b5d2f3e5dc5620c2a645
label="libft_8h_ac860595580d7b5d2f3e5dc5620c2a645"} size_t ft_strncmp (

::: DoxyParamCaption
ptr_find,

ptr_str,

length
:::

)

Compares two strings up to a specified amount of characters.

::: DoxyParams
Parameters *ptr_find* & The first string to compare.\
*ptr_str* & The second string to compare.\
:::

::: DoxyReturn
Returns An integer less than, equal to, or greater than zero if the
first string is found to be less than, equal to, or greater than the
second string, respectively.
:::

This function compares two strings character by character up to the
specified length or until a null-terminator is encountered.

The return value indicates the difference between the two strings at the
first differing position.

[]{#libft_8h_a8b5607f682467c782ab46cb691adcbcb
label="libft_8h_a8b5607f682467c782ab46cb691adcbcb"} char $\ast$
ft_strnstr (

::: DoxyParamCaption
string,

to_find,

length
:::

)

Searches for a substring in a string up to a specified length.

::: DoxyParams
Parameters *string* & The string to be searched.\
*to_find* & The substring to search for.\
*length* & The maximum number of characters to search.\
:::

::: DoxyReturn
Returns A pointer to the beginning of the located substring within the
string, or NULL if the substring is not found.
:::

The \"ft_strnstr\" function searches for the first occurrence of the
substring \"to_find\" within the string \"string\", but it only examines
the first \"length\" characters.

[]{#libft_8h_a6293eaf34272bef4fce98e27edb3f43b
label="libft_8h_a6293eaf34272bef4fce98e27edb3f43b"} char $\ast$
ft_strrchr (

::: DoxyParamCaption
string,

character
:::

)

Locates the last occurrence of a character in a string.

::: DoxyParams
Parameters *string* & The null-terminated string to be searched.\
*character* & The character.\
:::

::: DoxyReturn
Returns A pointer to the last occurrence of the character in the string,
or NULL if the character isnt found.
:::

[]{#libft_8h_a8481379d0d903f3623719ff94bbf484e
label="libft_8h_a8481379d0d903f3623719ff94bbf484e"} char $\ast$
ft_strtrim (

::: DoxyParamCaption
string,

characters
:::

)

Trims leading and trailing characters from a string.

::: DoxyParams
Parameters *string* & The string to be trimmed.\
*characters* & The set of characters to trim for both ends of the
string.\
:::

::: DoxyReturn
Returns A pointer to the trimmed string, or NULL if memory allocation
fails or if either input is NULL.
:::

This function removes any characters found in \"characters\" from the
start and end of the string \"string\", returning a new string with the
trimmed content.

The original string is not modified, and the result is stored in newly
allocated memory.

[]{#libft_8h_a71f65d4907d37d5991f240bb3d0cbb45
label="libft_8h_a71f65d4907d37d5991f240bb3d0cbb45"} char $\ast$
ft_substr (

::: DoxyParamCaption
string,

start,

length
:::

)

Extracts a substring from a string.

::: DoxyParams
Parameters *string* & The original string from which to extract the
substring.\
*start* & The starting position of the substring in the original
string.\
*length* & The maximum number of characters to include in the
substring.\
:::

::: DoxyReturn
Returns A pointer to the substring, or NULL if the input string is NULL
or memory allocation fails.
:::

This function allocates memory for and returns a substring of the given
string. The substring starts at the specified position and will contain
up to \"length\" characters, or fewer if the string ends before that.

[]{#libft_8h_a91fb5059ccb8a44e7e6cbbe8b5bbbfa3
label="libft_8h_a91fb5059ccb8a44e7e6cbbe8b5bbbfa3"} int ft_tolower (

::: DoxyParamCaption
character
:::

)

Converts an upper case character to its lower case equivalent.

::: DoxyParams
Parameters *character* & The character.\
:::

::: DoxyReturn
Returns The lower case equivalent of the character.
:::

If the character isnt upper case, returns the character unchanged.

[]{#libft_8h_a907feb90b929e7bc67671b4e009a1884
label="libft_8h_a907feb90b929e7bc67671b4e009a1884"} int ft_toupper (

::: DoxyParamCaption
character
:::

)

Converts a lower case character to its upper case equivalent.

::: DoxyParams
Parameters *character* & The character.\
:::

::: DoxyReturn
Returns The upper case equivalent of the character.
:::

If the character isnt lower case, returns the character unchanged.
[]{#libft_8h_source}[]{#libft_8h_source label="libft_8h_source"}
[Go to the documentation of this file.](#libft_8h)

::: DoxyCode
0
:::
