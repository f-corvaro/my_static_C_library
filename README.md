<h1 align="center">My static C library</h1>

<p align="center" style="text-decoration: none;">
    <a href="https://github.com/f-corvaro/my_static_C_library"><img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/f-corvaro/my_static_C_library?color=blueviolet" /></a>
    <a href="https://github.com/f-corvaro/my_static_C_library"><img alt="Code language count" src="https://img.shields.io/github/languages/count/f-corvaro/my_static_C_library?color=yellow" /></a>
    <a href="https://github.com/f-corvaro/my_static_C_library"><img alt="GitHub top language" src="https://img.shields.io/github/languages/top/f-corvaro/my_static_C_library?color=blueviolet" /></a>
    <a href="https://github.com/f-corvaro/my_static_C_library"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/f-corvaro/my_static_C_library?color=yellow" /></a>
</p>

<h3 align="center">Index</h3>

<p align="center">
  <a href="#my-static-c-library">1 - My Static C Library</a><br>
  <a href="#about">2 - About</a><br>
  <a href="#running-tests-and-features">3 - Running Tests and Features</a><br>
  <a href="#folder-structure">4 - Folder Structure</a><br>
  <a href="#support-me">5 - Support Me</a><br>
  <a href="#license">6 - License</a><br>
  <a href="#author">7 - Author</a><br>
</p>

## About

<p align="justify">

This is my static library, which encompasses the 42's project: get_next_line (only the bonus functions), ft_printf (with all format bonuses), and libft (with bonus functions). Furthermore, I have defined my bool and other useful things that you can check into the code. All the functions have a comment in Doxygen style to explain what it does. From the terminal, in the lib path, you can run the command ```make help``` to get an overview of the available commands in this library.

<p>
<br>

## Running tests and features

<a href="https://github.com/f-corvaro/my_static_C_library/tree/main"><img align="center" alt="make" src="https://github.com/f-corvaro/my_static_C_library/blob/main/.other/compile.gif">

<a href="https://github.com/f-corvaro/my_static_C_library/tree/main"><img align="center" alt="comment" src="https://github.com/f-corvaro/my_static_C_library/blob/main/.other/about.gif">


<br>


## Folder Structure

<p align="justify">

The folder structure is very easy, and the Makefile is made with the purpose of having repeatable and easily implemented rules.

- All the sources are stored in the srcs folder.

- The header is stored in the include folder.

- The library.a is stored in the build folder.

- The files.o are stored in  the objs folder.

The last two folders and files are created only after compiling.

This is the folder structure before compiling:

```
.
├─ lib
├── include
│   └── ft_printf.h
├── libft
│   ├── include
│   │   └── libft.h
│   ├── srcs
│   │   ├── ft_atoi.c
│   │   ├── ft_bzero.c
│   │   ├── ft_calloc.c
│   │   ├── ft_isalnum.c
│   │   ├── ft_isalpha.c
│   │   ├── ft_isascii.c
│   │   ├── ft_isdigit.c
│   │   ├── ft_isprint.c
│   │   ├── ft_itoa.c
│   │   ├── ft_lstadd_back.c
│   │   ├── ft_lstadd_front.c
│   │   ├── ft_lstclear.c
│   │   ├── ft_lstdelone.c
│   │   ├── ft_lstiter.c
│   │   ├── ft_lstlast.c
│   │   ├── ft_lstmap.c
│   │   ├── ft_lstnew.c
│   │   ├── ft_lstsize.c
│   │   ├── ft_memchr.c
│   │   ├── ft_memcmp.c
│   │   ├── ft_memcpy.c
│   │   ├── ft_memmove.c
│   │   ├── ft_memset.c
│   │   ├── ft_putchar_fd.c
│   │   ├── ft_putendl_fd.c
│   │   ├── ft_putnbr_fd.c
│   │   ├── ft_putstr_fd.c
│   │   ├── ft_split.c
│   │   ├── ft_strchr.c
│   │   ├── ft_strdup.c
│   │   ├── ft_striteri.c
│   │   ├── ft_strjoin.c
│   │   ├── ft_strlcat.c
│   │   ├── ft_strlcpy.c
│   │   ├── ft_strlen.c
│   │   ├── ft_strmapi.c
│   │   ├── ft_strncmp.c
│   │   ├── ft_strnstr.c
│   │   ├── ft_strrchr.c
│   │   ├── ft_strtrim.c
│   │   ├── ft_substr.c
│   │   ├── ft_tolower.c
│   │   ├── ft_toupper.c
│   │   ├── get_next_line_bonus.c
│   │   └── get_next_line_utils_bonus.c
│   └── Makefile
├── srcs
│   ├── ft_format.c
│   ├── ft_parse_and_handle_funcs.c
│   ├── ft_printf_funcs.c
│   ├── ft_printf.c
│   ├── ft_ptr.c
│   └── ft_utility_funcs.c
└── Makefile
```

This is the folder structure after the compiling:

```
.
├── lib
│   ├── build
│   │   └── libftprintf.a
│   ├── include
│   ├── libft
│   │   ├── build
│   │   │   └── libft.a
│   │   ├── include
│   │   ├── objs
│   │   │   ├── ft_atoi.o
│   │   │   ├── ft_bzero.o
│   │   │   ├── ft_calloc.o
│   │   │   ├── ft_isalnum.o
│   │   │   ├── ft_isalpha.o
│   │   │   ├── ft_isascii.o
│   │   │   ├── ft_isdigit.o
│   │   │   ├── ft_isprint.o
│   │   │   ├── ft_itoa.o
│   │   │   ├── ft_lstadd_back.o
│   │   │   ├── ft_lstadd_front.o
│   │   │   ├── ft_lstclear.o
│   │   │   ├── ft_lstdelone.o
│   │   │   ├── ft_lstiter.o
│   │   │   ├── ft_lstlast.o
│   │   │   ├── ft_lstmap.o
│   │   │   ├── ft_lstnew.o
│   │   │   ├── ft_lstsize.o
│   │   │   ├── ft_memchr.o
│   │   │   ├── ft_memcmp.o
│   │   │   ├── ft_memcpy.o
│   │   │   ├── ft_memmove.o
│   │   │   ├── ft_memset.o
│   │   │   ├── ft_putchar_fd.o
│   │   │   ├── ft_putendl_fd.o
│   │   │   ├── ft_putnbr_fd.o
│   │   │   ├── ft_putstr_fd.o
│   │   │   ├── ft_split.o
│   │   │   ├── ft_strchr.o
│   │   │   ├── ft_strdup.o
│   │   │   ├── ft_striteri.o
│   │   │   ├── ft_strjoin.o
│   │   │   ├── ft_strlcat.o
│   │   │   ├── ft_strlcpy.o
│   │   │   ├── ft_strlen.o
│   │   │   ├── ft_strmapi.o
│   │   │   ├── ft_strncmp.o
│   │   │   ├── ft_strnstr.o
│   │   │   ├── ft_strrchr.o
│   │   │   ├── ft_strtrim.o
│   │   │   ├── ft_substr.o
│   │   │   ├── ft_tolower.o
│   │   │   ├── ft_toupper.o
│   │   │   ├── get_next_line_bonus.o
│   │   │   └── get_next_line_utils_bonus.o
│   │   ├── srcs
│   │   └── Makefile
│   ├── objs
│   │   ├── ft_format.o
│   │   ├── ft_parse_and_handle_funcs.o
│   │   ├── ft_printf_funcs.o
│   │   ├── ft_printf.o
│   │   ├── ft_ptr.o
│   │   └── ft_utility_funcs.o
│   ├── srcs
│   └── Makefile
```

<br>

## Support Me

<p align="justify">
Remember to ⭐ the repository.
If you want to support me:</p>

<p align="center">
<a href="https://ko-fi.com/fcorvaro"><img width="180" img align="center" src="https://github.com/f-corvaro/42.common_core/blob/main/.extra/support-me-ko-fi.svg"><alt=""></a>
<a href="https://github.com/sponsors/f-corvaro"><img width="180" img align="center" src="https://github.com/f-corvaro/42.common_core/blob/main/.extra/support-me-github.svg"><alt=""></a>

<br>

## License
<p align="center">
<a href="https://choosealicense.com/licenses/mit/"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="MIT License"></a>
<a href="https://opensource.org/licenses/"><img src="https://img.shields.io/badge/License-GPL%20v3-yellow.svg" alt="GPLv3 License"></a>
<a href="http://www.gnu.org/licenses/agpl-3.0"><img src="https://img.shields.io/badge/license-AGPL-blue.svg" alt="AGPL License"></a>
<br>

## Author

<p align="center"><a href="https://profile.intra.42.fr/users/fcorvaro"><img style="height:auto;" src="https://avatars.githubusercontent.com/u/102758065?v=4" width="100" height="100"alt=""></a>
<p align="center">
<a href="mailto:fcorvaro@student.42roma.it"><kbd>Email</kbd><alt=""></a>
<a href="https://github.com/f-corvaro"><kbd>Github</kbd><alt=""></a>
<a href="https://www.linkedin.com/in/f-corvaro/"><kbd>Linkedin</kbd><alt=""></a>
<a href="https://42born2code.slack.com/team/U050L8XAFLK"><kbd>Slack</kbd><alt=""></a>

<hr/>