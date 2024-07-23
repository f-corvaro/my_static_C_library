<h1 align="center">
<a href="https://github.com/f-corvaro/my_static_C_library"><img src="https://github.com/f-corvaro/my_static_C_library/blob/main/.other/mylib.png"></a>
</h1>

<p align="center" style="text-decoration: none;">
    <a href="https://github.com/f-corvaro/my_static_C_library"><img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/f-corvaro/my_static_C_library?color=blueviolet" /></a>
    <a href="https://github.com/f-corvaro/my_static_C_library"><img alt="Code language count" src="https://img.shields.io/github/languages/count/f-corvaro/my_static_C_library?color=yellow" /></a>
    <a href="https://github.com/f-corvaro/my_static_C_library"><img alt="GitHub top language" src="https://img.shields.io/github/languages/top/f-corvaro/my_static_C_library?color=blueviolet" /></a>
    <a href="https://github.com/f-corvaro/my_static_C_library"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/f-corvaro/my_static_C_library?color=yellow" /></a>
</p>

<h3 align="center">Index</h3>

<p align="center">
  <a href="#library-overview">Library Overview</a><br>
  <a href="#running-tests-and-features">Running tests and features</a><br>
  <a href="#folder-structure-and-compilation">Folder Structure and Compilation</a><br>
  <a href="#folder-structure-before-compiling">Folder Structure Before Compiling</a><br>
  <a href="#support-me">Support Me</a><br>
  <a href="#author">Author</a><br>
</p>

## Library Overview

<p align="justify">

This static library includes the following 42 projects: `get_next_line` (bonus functions only), `ft_printf` (with all format bonuses), and `libft` (with bonus functions). Additionally, custom boolean types and other useful utilities are defined within the code. Each function is documented with Doxygen-style comments for clarity. 

To see the available commands for this library, navigate to the library path in the terminal and run:
```sh
make help
```

<p>
<br>

## Running tests and features

<a href="https://github.com/f-corvaro/my_static_C_library/tree/main"><img align="center" alt="make" src="https://github.com/f-corvaro/my_static_C_library/blob/main/.other/compile.gif">

<a href="https://github.com/f-corvaro/my_static_C_library/tree/main"><img align="center" alt="comment" src="https://github.com/f-corvaro/my_static_C_library/blob/main/.other/about.gif">

<br>

## Folder Structure and Compilation

<p align="justify">

The folder structure is straightforward, and the Makefile is designed for repeatable and easily implemented rules.

- All source files are stored in the `srcs` folder.
- The header files are stored in the `include` folder.
- The compiled library (`library.a`) is stored in the `build` folder.
- The object files (`files.o`) are stored in the `objs` folder.

The `build` and `objs` folders, along with their contents, are created only after compiling.

### Folder Structure Before Compiling

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

## Support Me

<p align="justify">

Remember to ⭐ the repository.
If you want to support me:</p>

<p align="center">
<a href="https://ko-fi.com/fcorvaro"><img width="180" img align="center" src="https://github.com/f-corvaro/42.common_core/blob/main/.extra/support-me-ko-fi.svg"><alt=""></a>
<a href="https://github.com/sponsors/f-corvaro"><img width="180" img align="center" src="https://github.com/f-corvaro/42.common_core/blob/main/.extra/support-me-github.svg"><alt=""></a>

<br>

## Author

<p align="center"><a href="https://profile.intra.42.fr/users/fcorvaro"><img style="height:auto;" src="https://avatars.githubusercontent.com/u/102758065?v=4" width="100" height="100"alt=""></a>
<p align="center">
<a href="mailto:fcorvaro@student.42roma.it"><kbd>Email</kbd><alt=""></a>
<a href="https://github.com/f-corvaro"><kbd>Github</kbd><alt=""></a>
<a href="https://www.linkedin.com/in/f-corvaro/"><kbd>Linkedin</kbd><alt=""></a>
<a href="https://42born2code.slack.com/team/U050L8XAFLK"><kbd>Slack</kbd><alt=""></a>

<hr/>
