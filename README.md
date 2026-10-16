# Reverse-string-cpp

# Reverse String in C++

A beginner-friendly C++ program that reverses a string entered by the user.

## About

This program takes a string as input (spaces included) and prints it in reverse order. It uses a simple `for` loop that starts from the last character and moves back to the first one.

## Example

```
Enter a string: Hello
Reversed string: olleH
```

```
Enter a string: Hello World
Reversed string: dlroW olleH
```

## How It Works

1. The program reads the full line using `getline(cin, str)`.
2. A loop starts at the last index (`str.length() - 1`) and goes down to index `0`.
3. Each character is added to a new string `rev`.
4. The final reversed string is printed.

## Concepts Used

- Strings (`string`)
- Input and output (`cin`, `cout`, `getline`)
- `for` loop
- String indexing (`str[i]`)

