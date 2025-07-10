# StarTravelSFML (Refactored)

A real-time starfield simulation written in modern C++ using [SFML 3](https://www.sfml-dev.org/), refactored from the original `StarTravelSFML` project by [@johnBuffer](https://github.com/johnBuffer).

This project updates the original implementation to work with **SFML 3.38**, replacing deprecated functionality such as `sf::PrimitiveType::Quads` with triangle-based rendering, and refactoring parts of the code for clarity and modern C++20 standards.

---

## Tutorial

This project was originally followed and adapted from the tutorial:

**“How to do Rendering using C++ - From installing the tools to implementation”**  
YouTube: [https://www.youtube.com/watch?v=t0z3RojiKFg](https://www.youtube.com/watch?v=t0z3RojiKFg)

---

## Changes

- Updated to **SFML 3.38** (original project used SFML 2.x)
- Replaced deprecated rendering primitives (e.g., `sf::Quads` → `sf::Triangles`)
- Cleaned up code structure and CMake configuration

---

## License

This project is licensed under the **MIT License**.

Majority of this project is based on  
[`StarTravelSFML`](https://github.com/johnBuffer/StarTravelSFML) by **Jean Tampon (@johnBuffer)**,  
also licensed under the MIT License.

You can find the original license in [`LICENSE.original`](LICENSE.original).
