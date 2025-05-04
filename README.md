## NAME:YUGESH K C
## REG NO:111923AI01118
## DEPARTMENT:B.TECH (AI&DS)


# PASSWORD-GENERATOR-USING-PYTHON
```
import random
import string

def generate_password(length):
    if length < 4:
        print("Password length should be at least 4 for better security.")
        return ""

    all_characters = string.ascii_letters + string.digits + string.punctuation

    password = ''.join(random.choice(all_characters) for _ in range(length))
    return password

try:
    length = int(input("Enter the desired password length: "))
    password = generate_password(length)
    if password:
        print(f"Generated Password: {password}")
except ValueError:
    print("Please enter a valid number.")

```
## OUTPUT:
![Screenshot 2025-05-04 131758](https://github.com/user-attachments/assets/999f634d-a08a-4fee-9ff0-eddd6fe2218e)
![Screenshot 2025-05-04 131815](https://github.com/user-attachments/assets/3ee2453a-2294-4022-873c-7658ad12bd35)

## RESULT:
The code has been executed successfully.


