
NAME = phonebook

SRC = main.cpp PhoneBook.cpp Contacts.cpp Helpers.cpp

OBJ = ${SRC:.cpp=.o}

CXX = c++

FLAGS = -Wall -Wextra -Werror

all : $(NAME)

$(NAME) : $(OBJ)
	$(CXX) $(FLAGS) $(OBJ) -o $(NAME)

clean :
	rm -rf *.o

fclean : clean
	rm -rf $(NAME)

re : fclean all