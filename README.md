## **Turbo C++ in Browser 🚀**

A web-based Turbo C++ IDE running in your browser using DOSBox emulation. Write and compile C++ code from anywhere, on any device!

Storage functionality will be added in future.

✨ Features

· Full Turbo C++ 3.0 Environment - Complete IDE with compiler
· Mobile-Friendly - Custom on-screen keyboard with multiple layers
· Responsive Design - Works on desktop, tablet, and mobile
· Touch Optimized - Prevents zooming/gestures for better typing experience
· No Installation Required - Runs entirely in your browser

🎮 Virtual Keyboard Layout

The on-screen keyboard features three layers for complete access to all keys:

Layer 0 - Main Keyboard

· Full QWERTY layout with lowercase letters
· Number row (0-9)
· Function keys (F1-F10)
· Arrow keys (←↑↓→)
· Special keys: Backspace (⌫), Enter (⏎), Space (␠)
· Modifier keys: Ctrl (C), Alt (A)

Layer 1 - Symbols & Special Characters (↑ to access)

· All shifted symbols (!@#$%^&*() etc.)
· Brackets and braces ({[<>]})
· Punctuation (;,.:, etc.)
· Escape key (␛)
· Access via ↑ button on main layer

Layer 2 - Uppercase Letters (Â to access)

· Capital letters (A-Z)
· Function keys (F1-F10)
· Access via Â button on main layer

🚀 Quick Start

1. Open the website - Navigate to your hosted page
2. Wait for loading - DOSBox and Turbo C++ will load automatically
3. Tap the play button.
4. Start coding - Use physical keyboard or on-screen keyboard
5. Compile & Run - Press Ctrl+F9 to compile and run
6. View Output - Alt+F5 to view output screen

💻 Usage Tips

Physical Keyboard

· Full keyboard support works out of the box
· Standard Turbo C++ shortcuts:
  · Ctrl+F9 - Compile & Run
  · Alt+F5 - View Output
  · F2 - Save
  · F3 - Open
  · Alt+X - Exit

Touch/Mobile Users

1. Use the on-screen keyboard at the bottom
2. Switch between layers using:
   · ↑ - For symbols and special characters
   · Â - For uppercase letters
   · ↓ - To return to main keyboard


🔧 Technical Details

Built With

· js-dos - DOSBox emulation in JavaScript
· Turbo C++ 3.0 - Classic C++ IDE
· Custom virtual keyboard with multi-layer support

DOSBox Configuration

· Machine: SVGA S3
· Memory: 32 MB
· CPU: Dynamic core with auto cycles
· Sound: Sound Blaster 16 emulation
· Mouse sensitivity: 0.18

Keyboard Map

Key codes follow SDL mapping:

· Letters: 65-90 (A-Z), 97-122 (a-z)
· Numbers: 48-57 (0-9)
· Function keys: 290-301 (F1-F12)
· Modifiers: 340 (Shift), 341 (Ctrl), 342 (Alt)
· Special: 256 (Escape), 257 (Enter), 259 (Backspace), 262 (→), etc.

📱 Browser Support

· Chrome/Edge (recommended)
· Firefox
· Safari
· Mobile browsers (iOS/Android)

🚦 Loading States

The application shows:

· Initial DOSBox boot sequence
· Turbo C++ loading screen
· Ready state when IDE is fully loaded


⚠️ Note

Turbo C++ is an older compiler and doesn't support modern C++ standards. This project is great for:

· Learning C basics
· Running legacy code
· Educational institutions
· Nostalgia

For modern C++ development, consider using contemporary tools.

---

Happy Coding! 🎉
