# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: whorpe <marvin@42.fr>                      +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/11/05 22:12:14 by whorpe            #+#    #+#              #
#    Updated: 2019/11/05 22:33:41 by whorpe           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a
SRCS = ./src/*.c
OBJS = ./*.o
HDR = includes/
FLAGS = -Wall -Wextra -Werror

all: $(NAME)
	
$(NAME):
	gcc $(SRCS) $(FLAGS) -I$(HDR) -c 
	ar -rc $(NAME) $(OBJS)
	ranlib $(NAME)

clean: 
	/bin/rm -f $(OBJS)

fclean: clean
	/bin/rm -f $(NAME)

re: fclean all
