# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: suchen <suchen@student.42.fr>              +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/11/27 12:28:50 by suchen            #+#    #+#              #
#    Updated: 2022/11/27 12:28:50 by suchen           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

CC =		gcc
CFLAGS =	-Werror -Wextra -Wall
Name = 		server.c\
			client.c\
			server_bonus.c\
			client_bonus.c\


all:
			$(CC) $(CFLAGS) -o server server.c
			$(CC) $(CFLAGS) -o client client.c
			$(CC) $(CFLAGS) -o server_bonus server_bonus.c
			$(CC) $(CFLAGS) -o client_bonus client_bonus.c


clean:
			rm -f server client
			rm -f server_bonus client_bonus

fclean:
			rm -f server client
			rm -f server_bonus client_bonus

re:			fclean all

.PHONY: 	re all clean fclean
