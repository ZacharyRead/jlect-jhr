# JLect Japanese Handwriting Recognition Tool (JLect JHR)

(c) Zachary Read | JLect.com  
2013-2023

## Table of contents

- [JLect Japanese Handwriting Recognition Tool (JLect JHR)](#jlect-japanese-handwriting-recognition-tool-jlect-jhr)
  * [What is it?](#what-is-it)
  * [Live demo](#live-demo)
  * [License](#license)
  * [Advantages and disadvantages](#advantages-and-disadvantages)
  * [Contributing](#contributing)

## What is it?

JLect JHR is a JavaScript library that provides support for Japanese handwritten character recognition. Users can draw a character in a defined HTML canvas element and the library will output guesses based on stroke direction.

Example:

![Example of Japanese Handwriting Recognition Tool](jhr-example.png?raw=true "Example of Japanese Handwriting Recognition Tool")

## Live demo

For a live demo, please check out https://zacharyread.github.io/jlect-jhr/example.html

For an example implementation, you can visit https://www.jlect.com and click on the "字 (draw)" button beside the search bar.

## License

The library and all associated files provided in the official repository are covered by the following Creative Commons license:
* Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0): https://creativecommons.org/licenses/by-sa/3.0/

## Advantages and disadvantages

Pros:

* The library is open-sourced, so anyone can contribute to the project to improve it and anyone can use it as long as the license conditions are met.
* The library has no dependencies, which makes it easy to deploy in comparison to other tools.
* The library can be easily modified and expanded. The "example.html" file provides data output that you can use to expand the existing dataset.
* The library, while being stroke-oriented, considers the fact that users are likely to draw characters in the wrong stroke order.

Cons:

* The library is stroke-oriented and does not handle cursive character input.
* The dataset is incomplete, so it may fail at recognizing a fair number of characters.
* It only supports drawing one character at a time.

## Contributing

I strongly encourage anyone who uses the library to contribute back to the project: https://github.com/ZacharyRead/jlect-jhr.
