# **KotlinPlayGround**

*Write your first program in Kotlin*

**What is Kotlin?**<br>
Kotlin is a cross-platform, statically typed, general-purpose programming language with type inference.
Android apps are written in the Kotlin programming language. Kotlin is a modern language created to help developers write code efficiently and with as few errors as possible.

**Programming Language?**<br>
Just like you use human language to communicate with another person, you use a programming language to communicate with the operating system of your computer. Fortunately, programming languages are less complex than human languages and quite logical!

**(IDE) Integrated Development Environment**<br>
IDE is a programming tool or software application that provides comprehensive facilities to computer programmers for software development.
we can simply say that IDE is use as a code editor.


In your browser, open https://developer.android.com/training/kotlinplayground. This will opens a browser-based programming tool.<br>
OR<br>
Clone this project in android studio and navigate to the kotline playground Git: https://github.com/mustafakamal88/KotlinPlayGround.git<br>

**This is the program code in the editor:**<br>
```
fun main() {
    println("Hello, world!")
}
```
<br>

**Run the program code**<br>
Running a program that you created is not much different than running a program such as a word processor on your computer. The difference is that when you run a program to accomplish a task, or play a game, you primarily care about what the program can do for you, and you don't concern yourself with the code that makes it work. When you are programming, you get to see and work with the actual code that makes the magic happen.<br>

Let's see what this program does!<br>

In the editor, in the top-right corner, find the green triangle ![63ca117bafffc8da_1920](https://user-images.githubusercontent.com/35607112/205415450-8b92f8d8-796a-4bcd-89b2-2061e0c2a831.png) and click it to run the program.
Look at the pane at the bottom.<br>

**Output**<br>

Hello, world!<br>

**Notice** Hello, world! printed, So now you know what this program does: It prints, or outputs, a hello world message.


**Compilation:** is a process that translates the Kotlin program code into a form that the system can run. If compilation completes successfully, there are no errors in the program that would keep it from running. If there are problems, they will appear in the pane at the bottom.

**Modify your program**<br>
Change the Hello World code
Let's change the program to make it do something a little different.<br>

Change the "Hello, world!" text to say "Happy Birthday!".<br>
Run your program by clicking the blue or green run button at the top right.<br>
At the bottom, you should now see Happy Birthday! printed.<br>

**How does it work?**<br>
How is this done? This seems like a lot of code to just print something!<br>

Well, if you wanted a friend to write "Hello, world!" on a piece of paper, there is a lot of implied information. If you just tell them, "Write ‘Hello world!' on this piece of paper", they are going to make assumptions about the information you left out. For example, they are going to assume they need to use a pen, and that you want them to write it using letters! The computer does not make these assumptions, so you have to give precise instructions that include every step.<br>

Just like the English language has structure, so does a programming language. If you've ever learned another language, you know the challenge of learning the grammar, the spelling, perhaps a new alphabet of symbols, and the vocabulary. Learning to program has similar challenges, but fortunately, it is less complex and a lot more logical than learning, for example English.<br>

**Understand the parts of the program**
Now, take a look at the code. Each piece of this program serves a specific purpose, and you need all the pieces in order to be able to run the program. Let's start with the first word.

```
fun
```
<br>
"fun" is a word in the Kotlin programming language. fun stands for function. A function is a section of a program that performs a specific task.<br>

**Note:** Kotlin has many special words with very specific meanings. As you learn to program in the Kotlin language, you will learn these words. They are often called keywords or reserved words.<br>

```fun main```<br>

main is the name of this function. Functions have names, so they can be distinguished from each other. This function is called main, because it is the first, or main, function that is called when you run the program. Every Kotlin program needs a function named main.<br>

```fun main()```<br>

The function name is always followed by () two parentheses.
Inside the parentheses, you can put information for the function to use. This input to the function is called "arguments" or args for short. You will learn more about arguments later.<br>

```fun main() {}```<br>
Notice the pair of curly braces {} after the parentheses. Inside a function is code that accomplishes a task. These curly braces surround those lines of code.<br>

Look at the line of code between the curly braces:
```println("Happy Birthday!")```<br>

This line of code prints the Happy Birthday! text.<br>

println tells the system to print a line of text.<br>
Inside the parentheses you put the text to be printed.<br>
Notice that the text to be printed is surrounded by quotes. This tells the system that everything inside the quotation marks should be printed exactly as given.<br>
To actually print the text, this whole println instruction has to be inside the main function.<br>

So, there it is. The smallest Kotlin program.<br>

```
fun main() {
    println("Happy Birthday!")
}
```
<br>








## Reference Site<br>
[Google Android Developer Training](https://developer.android.com/courses/android-basics-kotlin/course) "I learn Kotlin from this Google official documentation you can also check for more references")
