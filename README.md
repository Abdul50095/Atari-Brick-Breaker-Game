Brick Breaker – x86 Assembly Game

A fully functional Brick Breaker (Breakout) game implemented entirely in 16-bit x86 Real Mode Assembly.
This project demonstrates low-level programming techniques including direct video memory access, hardware interrupt handling, PC speaker sound, and real-time game logic — all without using any high-level frameworks or OS APIs.

🚀 Features
🎮 Gameplay

Paddle movement controlled via keyboard interrupts

Real-time ball physics and movement using the hardware timer (PIT)

Dynamic brick layout and collision detection

Score, lives, bonus system

Win/Loss end screens with restart functionality

🖥 Graphics / Rendering

Direct manipulation of text-mode video memory at segment 0xB800

Character-based graphics rendered using custom print functions

Borders, bricks, paddle, and ball drawn as text cells

⌨️ Hardware Integration

Custom Keyboard ISR (INT 9) for responsive input

Custom Timer ISR (INT 8) to drive game updates

Safe installation/restoration of interrupt vectors

PC Speaker sound generation via PIT channels & I/O ports (43h/42h/61h)

🧠 What I Learned

Low-level hardware programming

Working with the Interrupt Vector Table (IVT)

Mapping coordinates to video memory addresses

Structuring large assembly programs with stack frames

Timing, polling, and real-time interrupts

How early DOS-era games were built
