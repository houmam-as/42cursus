# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: hait-sal <hait-sal@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/10/11 15:36:31 by hait-sal          #+#    #+#              #
#    Updated: 2022/11/05 18:52:33 by hait-sal         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

SRC = ft_bzero.c ft_isalpha.c ft_isdigit.c ft_memcpy.c ft_memset.c ft_tolower.c ft_isalnum.c ft_isascii.c ft_isprint.c ft_memmove.c ft_strlen.c  ft_toupper.c ft_strchr.c ft_strrchr.c ft_strlcpy.c ft_strlcat.c ft_atoi.c ft_strncmp.c ft_memchr.c ft_memcmp.c ft_strnstr.c ft_calloc.c ft_strdup.c ft_substr.c ft_strjoin.c ft_strtrim.c ft_split.c ft_itoa.c ft_strmapi.c ft_striteri.c ft_putchar_fd.c ft_putstr_fd.c ft_putendl_fd.c ft_putnbr_fd.c

OBJ = ft_bzero.o ft_isalpha.o ft_isdigit.o ft_memcpy.o ft_memset.o ft_tolower.o ft_isalnum.o ft_isascii.o ft_isprint.o ft_memmove.o ft_strlen.o  ft_toupper.o ft_strchr.o ft_strrchr.o ft_strlcpy.o ft_strlcat.o ft_atoi.o ft_strncmp.o ft_memchr.o ft_memcmp.o ft_strnstr.o ft_calloc.o ft_strdup.o ft_substr.o ft_strjoin.o ft_strtrim.o ft_split.o ft_itoa.o ft_strmapi.o ft_striteri.o ft_putchar_fd.o ft_putstr_fd.o ft_putendl_fd.o ft_putnbr_fd.o

all : $(NAME)

$(NAME) : $(OBJ) libft.h
	@echo finishing
	@ar -rc $(NAME) $(OBJ)

$(OBJ) : $(SRC)
	@echo compiling
	@gcc -Wall -Werror -Wextra -c $(SRC)
	
clean :
	@echo removing *.o 
	@rm -f *.o

fclean : clean
	@echo removing libft.a
	@rm -f libft.a
	
re : fclean all
