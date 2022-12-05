-ft_atoi. Converts the initial portion of the string pointed to by *str to int.
-ft_bzero. Erases the data in the n bytes of the memory starting at the location 
	pointed to by s, by writing zeros (bytes containing '\0') to that area.
-ft_calloc. Allocates memory for an array of nitems elements of size bytes each 
	and returns a pointer to the allocated memory. The memory is set to zero.
-ft_isalnum. Checks whether the unsigned char c is alphanumeric
-ft_isalpha. Checks whether the unsigned char c is alphabetic
-ft_isascii. Checks whether the unsigned char c is a 7-bit unsigned char value that
	fits into the ASCII character set
-ft_isdigit. Checks whether the unsigned char c is a digit
-ft_isprint. Checks whether the unsigned char c is a printable char
-ft_itoa. Converts an integer into a string made of ascii chars. Memory is allocated
	with malloc(3)).
-ft_memchr. Scans the initial n bytes of the memory area pointed to by s for the first 
	instance of c.  Both c and the bytes of the memory area pointed to by s are 
	interpreted as unsigned char.
-ft_memcmp. compares the first n bytes (each interpreted as unsigned char) of the memory 
	areas s1 and s2. Returns an integer less than, equal to, or greater than zero if the 
	first n bytes of s1 is found, respectively, to be less than, to match, or be greater 
	than the first n bytes of s2.
-ft_memcpy. Copies n bytes from memory area src to memory area dest. Returns a pointer 
	to dest
-ft_memmove. copies n bytes from memory area src to memory area dest. Unlinke memcpy,
	the memory areas may overlap: copying takes place as though the bytes in src are 
	first copied into a temporary array that does not overlap src or dest, and the bytes 
	are then copied from the temporary array to dest. Returns a pointer to dest
-ft_memset. Fills the first n bytes of the memory area pointed to by s with the constant 
	byte c. Returns a pointer to the memory area s
-ft_putchar_fd. Outputs the char c to the given file descriptor
-ft_putendl_fd. Outputs the string ’s’ to the given file descriptor followed by a newline.
-ft_putnbr_fd. Outputs the integer ’n’ to the given file descriptor.
-ft_putstr_fd. Outputs the string ’s’ to the given file descriptor
-ft_split. Takes the first occurrence of the null-terminated string string s and a char c, 
	and returns an array of strings obtained by splitting ’s’ using the character ’c’ as 
	a delimiter. Memory for the array is allocated 	with malloc.
-ft_strchr. Locates the first occurrence of the character c in the string s, and returns a 
	pointer to the matched character or NULL if the character is not found. 
-ft_strdup. Duplicates the string s given as parameter and returns a pointer to the new string.
	memory is allocated with malloc
-ft_striteri. Applies the function ’f’ on each character of the string passed as 
argument, passing its index as first argument. Each character is passed by address to 
’f’ to be modified if necessary.
-ft_strjoin. Takes as parameters two strings, s1 and s2, and concatenates them. Returns
	the new string resulting from the concatenation
-ft_strlcat. appends the NUL-terminated string src to the end of dst.  It will append at
	most size - strlen(dst) - 1 bytes, NUL-terminating the result. Returns the total
	length of the string it tried to create (length of dst + length of str)
-ft_strlcpy. Copies up to size - 1 characters from the NUL-terminated string src to dst,
	NUL-terminating the result. Resturns the length of src
-ft_strlen. Counts and the returns the length of a string, including the terminating NULL 
-ft_strmapi. Applies the function ’f’ to each character of the string ’s’, and passing 
	its index as first argument to create a new string (with malloc(3)) resulting from 
	successive applications of ’f’. Returns the string created from the successive 
	applications of f
-ft_strncmp. Compares at most n bytes of s1 and s2. Returns an integer less than, equal to, 
	or greater than zero if the first n bytes of s1 is found, respectively, to be less than,
	to match, or be greater than s2.
-ft_strnstr. Locates the first occurrence of the null-terminated string tofind in the string str,
	searching up to len characters. If tofind is an empty string, str is returned; if tofind 
	occurs nowhere in str, NULL is returned; otherwise a pointer to the first character of the 
	first occurrence of tofind is returned
-ft_strrchr. Locates the last occurrence of the character c in the string s, and returns 
	a pointer to the matched character or NULL if the char is not found.
-ft_strtrim. Creates a copy of string s1, with the chars specified in set removed from the 
	beginning and end of the string. Memory for the trimmed string is allocated with malloc. 
	Returns the trimmed string
-ft_substr. Extracts a substring from a string s, starting from index start and of max size
	len. Returns the substring. Memory for the new string is allocated with malloc
-ft_tolower. Converts uppercase letter c to lowercase. If c is a uppercase letter, 
	returns its lowercase equivalent, if a lowercase representation exists in the 
	current locale.  Otherwise, it returns c.
-ft_toupper. Converts lowercase letter c to uppercase. If c is a lowercase letter, 
	returns its uppercase equivalent, if an uppercase representation exists in the 
	current locale.  Otherwise, it returns c.

BONUS PART 
-ft_lstadd_back
-ft_lstadd_front
-ft_lstclear
-ft_lstdelone
-ft_lstiter
-ft_lstlast
-ft_lstmap
-ft_lstnew
-ft_lstsize
