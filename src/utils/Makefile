# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: msarigul <msarigul@student.42kocaeli.com.  +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/08/02 10:09:01 by msarigul          #+#    #+#              #
#    Updated: 2022/12/27 12:19:44 by msarigul         ###   ########.tr        #
#                                                                              #
# **************************************************************************** #

OBJDIR	:= ../../obj
CFLAGS	:= -I ../../inc -c
FILES	:= ft_check_argv.c\
				 ft_exit_sys.c\
				 ft_file_descriptor.c\
				 ft_read_and_write.c

OBJ		:= $(FILES:%.c=$(OBJDIR)/%.o)

all: $(OBJ)

$(OBJDIR)/%.o: %.c
	@$(CC) $(CFLAGS) -c $< -o $@

.PHONY: all 
