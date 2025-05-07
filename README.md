# file_bomb - Cli Application For Generating Large Test Files

### Requirements
- [Rust Installation](https://www.rust-lang.org/tools/install)

### Usage
- Clone the repository or [download](https://github.com/f42h/file_bomb/archive/refs/heads/master.zip) the project directly
```
git clone https://github.com/f42h/file_bomb.git
```

- Build and run the program
```
chmod +x build.sh && ./build.sh
``` 

##### This will create a new file `bomb.txt` and fill it with random generated data until the programm receive an interrupt signal.

### Example Output
``` 
File generated: bomb.txt
Generating content.. Press Ctrl+C to interrupt!
OK! Generated test file with size of 16466689 bytes                                                                                                    
Finished in: 5.85s
```