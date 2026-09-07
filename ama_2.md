# AMA - 7 Sep

## 1. How do you clone a Git repository?
You can clone a Git repository using `git clone <repository-url>`. It copies the repository to your local system.

## 2. Which command is used to find unique words count in a file?
You can use `tr '[:upper:]' '[:lower:]' < file.txt | tr ' ' '\n' | sort | uniq -c` to find unique words/lines and count in a file.

## 3. What is the difference between a list and a dictionary?
A list stores items in an ordered way using indexes, while a dictionary stores data as key-value pairs.

## 4. What is the difference between a list and a tuple?
A list can be changed after creation, but a tuple cannot be changed.

## 5. Which command is used to check free disk space?
The `df -h` command is used to check the available disk space in a readable format.

## 6. What is the difference between remove() and pop()?
`remove()` deletes an item by its value, while pop() deletes an item by its index and returns it.

## 7. What does mutable mean in Python?
Mutable means an object can be changed after it is created. For example, a list is mutable because we can add, remove, or change its items.

## 8. What is the difference between inline and block-level elements?
Inline elements take only the required space, while block-level elements usually take the full available width and start on a new line.

## 9. What is clamp() in CSS?
`clamp()` sets a value between a minimum and maximum limit. It is commonly used for responsive font sizes.

**Example:**
```css
font-size: clamp(16px, 2vw, 24px);
```
- Here, the font size will stay between 16px and 24px.

## 10. What is the difference between pass-by-value and pass-by-reference?
Pass-by-value sends a copy of the value, while pass-by-reference works with the original data or its reference.

## 11. What is the difference between the staging area and the working directory?
The working directory contains your current changes, while the staging area contains the changes selected for the next commit.
 
## 12. What is the full form of lspci?
`lspci` stands for List Peripheral Component Interconnect. It is used to display information about PCI devices connected to the system.
