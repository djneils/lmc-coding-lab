# LMC Coding Lab

A Little Man Computer editor and simulator for OCR A Level Computer Science (H446). Students write LMC assembly, assemble it into memory, and step through it watching the program counter, accumulator, inputs and outputs change.

## Features

### Writing programs
- Code editor with line numbers and a **Format code** button that lines up labels, opcodes and operands
- **Assemble into memory** turns the program into a memory table, with a symbol table showing every label and its address
- Built-in examples: add two numbers, add two stored values, countdown, larger of two numbers, count up, an endless loop and multiply by repeated addition
- Save programs as `.txt` files and open them again later

### Running programs
- **Step**, **Back**, **Run** and **Instant** with an adjustable speed
- The memory table highlights the instruction the PC points at, with an optional machine code column
- Accumulator, labelled variables, inputs and outputs shown as separate panels, with a history of past values
- Breakpoints, and values can be edited directly in the memory table
- Instruction set reference built in

### In the classroom
- Keyboard shortcuts: → step, ← back, R run/pause, I instant, ? instructions, L labels, B blank screen
- Text size buttons and full screen mode for the board

## How to Use

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari). Nothing to install, no login.
2. Pick an example from **Program**, or press **New program** and type your own
3. Press **Assemble into memory**
4. Press **Step** (or →) to run one instruction at a time, or **Run** to watch it go
5. Use **Back** to rewind and talk through what just happened

## Use Cases

- Introducing LMC instructions one at a time
- Students writing and debugging their own programs
- Tracing programs on the board with the class

## Tech

- A single HTML file: HTML, CSS and plain JavaScript
- No libraries, no build step, no backend
- Uses the browser's local storage to remember your options
- Light and dark themes

---

## License

Copyright © Neil Southin. Free for personal use. Schools, colleges, and organisations wishing to use this in classrooms or on a VLE must get in touch first — see [LICENSE.md](LICENSE.md) for full details or email **southinn@colchsfc.ac.uk**.
