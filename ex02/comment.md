`while True:
    direction = input("Type 'encode' to encrypt, type 'decode' to decrypt:\n").lower().strip()
    if direction in ["encode", "decode"]:
        break
    print("Invalid choice please try again!")
`

This is how you can check the input . If it is in correct form .
Just use `if` and the inputs as list. `["encode", "decode"]`