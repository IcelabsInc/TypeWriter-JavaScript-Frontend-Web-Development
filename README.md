# TypeWriter JavaScript Frontend Web Development
The **TypeWriter JavaScript class** is designed to create engaging and dynamic text animations that mimic the effect of a typewriter. This class simplifies the process of animating multiple text strings simultaneously, allowing developers to enhance their web applications with visually appealing text transitions.

## Preview 🌟


## Download ⬇️
[Download the TypeWriter.js]()


## Usage ⚙️

### Caution ⚠️
before using use the script tag to load the typewriter.js to your document.
```
<script src="typewriter.js"></script>
```

### Declaring the text and blinker for animation ✨
```
<h1>Welcome to <span id="element">CodeWithPlus</span><span aria-hidden="true" id="blinker"></span></h1>
```

### To animate one text 📝
```
let typeWriter = new TypeWriter("element", "blinker", "CodeWithPlus");
typeWriter.StartAnimation();
```

### To animate multiple texts 🔄
```
let typeWriter = new TypeWriter("element", "blinker", ["C Programming", "C++ Programming", "Python", "Java"]);
typeWriter.StartAnimation();
```

### To change how many times the blinker will show and hide 🔁
```
let typeWriter = new TypeWriter("element", "blinker", ["C Programming", "C++ Programming", "Python", "Java"], 5);
typeWriter.StartAnimation();    
```

### To hide the blinker from one text after writing is done 👀
```
let typeWriter = new TypeWriter("element", "blinker", "CodeWithPlus", 0);
typeWriter.StartAnimation();
```

## To change the duration of text to write and the duration of hiding and showing of blinker:
```
let typeWriter = new TypeWriter("element", "blinker", ["C Programming", "C++ Programming", "Python", "Java"], 5, 500, 100);
typeWriter.StartAnimation();  
```

## Contributing 🤝
We welcome contributions! If you'd like to contribute, please fork the repository and create a pull request.

## License 📄
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
Developed by **Icelabs Inc.** 💼
