#include <unistd.h>

void	ft_print_alphabet(void);
void	ft_print_reverse_alphabet(void);
void	ft_print_numbers(void);
void	ft_is_negative(int n);
void	ft_print_comb(void);
void	ft_print_comb2(void);
void	ft_putnbr(int nb);
void	ft_print_combn(void);

void	ft_putchar(char c)
{
  write(1, c, 1);
}

int	main(int argv, char **argc)
{
  int ex;

  ex = atoi(argc[1]);
  if (ex == 0)
    ft_print_alphabet();
  else if (ex == 1)
    ft_print_reverse_alphabet();
  else if (ex == 2)
    ft_print_numbers();
  else if (ex == 3)
    ft_is_negative(atoit(argc[2]));
  else if (ex == 4)
    ft_print_comb();
  else if (ex == 5)
    ft_print_comb2();
  else if (ex == 6)
    ft_putnbr(atoi(argc[2]));
  else if (ex == 7)
    ft_print_combn();
  return (0);
}
