# 42-libft

## Project Structure

This project has been reorganized for better code organization:

- `INC/` - Header files
  - `libft.h` - Main library header
  - `ft_printf.h` - ft_printf function header
- `SRC/` - Source files organized by function type
  - `ft_is/` - Character classification functions
  - `ft_lst/` - Linked list functions (bonus)
  - `ft_mem/` - Memory manipulation functions
  - `ft_printf/` - ft_printf implementation
  - `ft_put/` - Output functions
  - `ft_str/` - String manipulation functions
  - `ft_to/` - Type conversion functions
  - `getnextline/` - get_next_line function (to be implemented)

## ⚠️ Important Note for Submission

**This version includes additional functions that are NOT part of the original libft project:**

- `ft_printf` - A printf implementation
- `getnextline` - get_next_line function (placeholder)

**If you plan to submit this project for the libft assignment, you MUST:**

1. Remove the `ft_printf/` folder and its contents
2. Remove the `getnextline/` folder
3. Update the `Makefile` to remove references to these functions
4. Remove `ft_printf.h` from the `INC/` folder
5. Remove the ft_printf function declarations from `libft.h`

The original libft project should only contain the mandatory and bonus functions as specified in the assignment requirements.

## Building

```bash
make        # Build the library
make bonus  # Build with bonus functions
make clean  # Remove object files
make fclean # Remove object files and library
make re     # Rebuild from scratch
```