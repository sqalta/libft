SRC = $(wildcard *.c)

CC = gcc
CFLAG = -Wall -Wextra -Werror
OBJS = $(SRC:%.c=%.o)
RM = rm -rf
NAME = libft.a

all: $(NAME)

%.o: %.c
	$(CC) -c $(CFLAGS) -o $@ $<

$(NAME): $(OBJS) 
	ar rcs $(NAME) $(OBJS)

clean: 
	$(RM) $(OBJS)

fclean:	clean
	$(RM) $(NAME)

re: fclean all

#fonksiyon: koşul
#		target





