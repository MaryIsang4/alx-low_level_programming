In this project, I learnt sbout Structure and typedef in C. A Structureis a declaration that defines a physically grouped list of variables under one name in a block of memory, allowing the different variables to be accessed via a single pointer or by the struct declared name which returns the same address. 

dog.h: Header file containing definitions and prototypes for all types and functions written in the project. Type/File Defintion/Prototype struct dog

char *name float age char *owner typedef dog_t struct dog 1-init_dog.c void init_dog(struct dog *d, char *name, float age, char *owner); 2-print_dog.c void print_dog(struct dog *d); 4-new_dog.c dog_t *new_dog(char *name, float age, char *owner); 5-free_dog.c void free_dog(dog_t *d); Tasks page_with_curl

Django dog.h: Header file that defines a new type struct dog with the following elements: char *name float age char *owner

A dog is the only thing on earth that loves you more than you love yourself 1-init_dog.c: C function that initializes a variable of type struct dog.

A dog will teach you unconditional love. If you can have that in your life, things won't be too bad 2-print_dog.c: C function that prints a struct dog. If an element of d is NULL, the function prints (nil) instead of the element. If d is NULL, the function prints nothing.

Outside of a dog, a book is a man's best friend. Inside of a dog it's too dark to read dog.h: Header file that defines a new type dog_t as a new name for the type struct dog.

A door is what a dog is perpetually on the wrong side of 4-new_dog.c: C function that creates a dog. Returns NULL if the function fails.

How many legs does a dog have if you call his tail a leg? Four. Saying that a tail is a leg doesn't make it a leg 5-free_dog.c: C function that frees dogs.
