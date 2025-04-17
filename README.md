# COBOL Zero to Master

## Dependencies

Debian/Ubuntu:
```bash
sudo apt install -y gnucobol3
```

## Compile and Run

```bash
cobc -x -o ./out/hello-compiled ./classes/class001_hello-world.cob
```
This will create an executable file named `hello-compiled` in the `out` directory.
To run the compiled program, use the following command:

```bash
./out/hello-compiled
```