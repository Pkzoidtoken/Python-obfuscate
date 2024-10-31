Most Powerful Python Code Obfuscation Tool: Easy to Use

```
python ob.py script_name.py output_name.py
```
Before:

```
def encrypt():
    call.generate_zip()
    call.inject_code()
    call.write_content(content=read_FS())
    call.final()

def decrypt():
    get_file(content=call.read_file())
    call.extract_zip()

if __name__ == "__main__":
    if method == "e":
        encrypt()
    elif method == "d":
        decrypt()
    else:
        print("no method select")
```
After:

```
def XXXXXXXXXXX():
    X_X_X_X_X_X_X_X_X_X_.XXXX()
    X_X_X_X_X_X_X_X_X_X_.XXXXXXX()
    X_X_X_X_X_X_X_X_X_X_.XXXXXXXX(content=X())
    X_X_X_X_X_X_X_X_X_X_.XXXXXXXXXX()

def XXXXXXXXXXXX():
    XX(content=X_X_X_X_X_X_X_X_X_X_.XXXXXXXXX())
    X_X_X_X_X_X_X_X_X_X_.XXXXX()

if __name__ == "__main__":
    if X_X_X_X_ == "e":
        XXXXXXXXXXX()
    elif X_X_X_X_ == "d":
        XXXXXXXXXXXX()
    else:
        print("no X_X_X_X_ select")
```
