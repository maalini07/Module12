# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program
```
  stack = []
  
  for i in range(3):
      value = input(f"Enter value {i + 1}: ")
      stack.append(value) 
  
  top_element = stack[-1]
  print("Top element of the stack is:", top_element)
```

## Output
<img width="488" height="215" alt="446626041-efe4682a-74e7-4102-abfd-14a418f630fa" src="https://github.com/user-attachments/assets/e3529146-2a3b-432d-8b6f-766cc390234d" />

## Result
Thus, the program has executed successfully
