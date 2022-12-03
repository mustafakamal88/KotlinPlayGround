# **KotlinPlayGround**

*Write your first program in Kotlin*

## 1. What is Kotlin?<br>
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
```ruby
fun main() {
    println("Hello, world!")
}
```
<br>

## 2. Run the program code<br>
Running a program that you created is not much different than running a program such as a word processor on your computer. The difference is that when you run a program to accomplish a task, or play a game, you primarily care about what the program can do for you, and you don't concern yourself with the code that makes it work. When you are programming, you get to see and work with the actual code that makes the magic happen.<br>

Let's see what this program does!<br>

In the editor, in the top-right corner, find the green triangle ![63ca117bafffc8da_1920](https://user-images.githubusercontent.com/35607112/205415450-8b92f8d8-796a-4bcd-89b2-2061e0c2a831.png) and click it to run the program.
Look at the pane at the bottom.<br>

**Output**<br>
```
Hello, world!
```
**Notice** Hello, world! printed, So now you know what this program does: It prints, or outputs, a hello world message.


**Compilation:** is a process that translates the Kotlin program code into a form that the system can run. If compilation completes successfully, there are no errors in the program that would keep it from running. If there are problems, they will appear in the pane at the bottom.

## 3 Modify your program<br>
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

```ruby
fun
```
<br>
"fun" is a word in the Kotlin programming language. fun stands for function. A function is a section of a program that performs a specific task.<br>

**Note:** Kotlin has many special words with very specific meanings. As you learn to program in the Kotlin language, you will learn these words. They are often called keywords or reserved words.<br>

```ruby
fun main
```
<br>

main is the name of this function. Functions have names, so they can be distinguished from each other. This function is called main, because it is the first, or main, function that is called when you run the program. Every Kotlin program needs a function named main.<br>

```ruby
fun main()
```
<br>

The function name is always followed by () two parentheses.
Inside the parentheses, you can put information for the function to use. This input to the function is called "arguments" or args for short. You will learn more about arguments later.<br>

```ruby
fun main() {}
```
<br>
Notice the pair of curly braces {} after the parentheses. Inside a function is code that accomplishes a task. These curly braces surround those lines of code.<br>

Look at the line of code between the curly braces:<br>
```ruby
println("Happy Birthday!")
```
<br>

This line of code prints the Happy Birthday! text.<br>

println tells the system to print a line of text.<br>
Inside the parentheses you put the text to be printed.<br>
Notice that the text to be printed is surrounded by quotes. This tells the system that everything inside the quotation marks should be printed exactly as given.<br>
To actually print the text, this whole println instruction has to be inside the main function.<br>

So, there it is. The smallest Kotlin program.<br>

```ruby
fun main() {
    println("Happy Birthday!")
}
```
<br>
## 4. Extend your program<br>

Print more than one message<br>
Great job! You printed one line of text using the println() function. However, you can put as many lines of instructions inside a function as you want or need to get a task accomplished.<br>

Copy the line println("Happy Birthday!") and paste it two more times below it. Make sure your pasted lines are inside the curly braces of the main function.<br>
Change one text to be printed to someone's name, say "Jhansi".<br>
Change the other text to be printed to "You are 25!".<br>
Your code should look like the code below.<br>

```ruby
fun main() {
    println("Happy Birthday!")
    println("Jhansi")
    println("You are 25!")
}
```
<br>
What would you expect this code to do when it runs?<br>

Run your program to see what it does.<br>
Go to the output pane, and you should see 3 lines printed in the console window, as shown below.<br>

```
Happy Birthday!
Jhansi
You are 25!
```
`Nice work!`
<br>

**Dealing with errors**
Making mistakes while programming is normal, and most tools will give you feedback to help you fix mistakes. In this step, create a mistake to see what happens.
<br>
In your program, remove the quotes around the text Jhansi, so that line looks as shown below.
<br>
```ruby
println(Jhansi)
```
<br>
Run your program. You should see Jhansi printed in red, and an exclamation mark next to the line of code you changed, to show you where there is an error.<br>
Android Studio
<br>

<img width="1440" alt="Screenshot 2022-12-03 at 8 00 15 PM" src="https://user-images.githubusercontent.com/35607112/205447251-b325425a-d0e3-4ba8-a529-5d6070bac9a5.png">
<br>
Web Tool
<br>

![59b30c831e01b523_1920](https://user-images.githubusercontent.com/35607112/205447804-1bc13127-68e1-4eb9-83ac-9882237a1ea7.png)

<br>

Look at the output pane. It shows a message with the same exclamation mark icon. What follows is a description of the error in your code.

<img width="1440" alt="Screenshot 2022-12-03 at 8 03 50 PM" src="https://user-images.githubusercontent.com/35607112/205447453-897388bb-5413-4ceb-9051-c58d55717e2b.png">
<br>
Web Tool
<br>

![5b166684a2b80dee_1920](https://user-images.githubusercontent.com/35607112/205447828-03c213d2-260b-4835-aece-ed47d9ca00d7.png)

<br>

This message, Unresolved reference: Jhansi, tells you what the system thinks is the error in the code. Even if you don't know what the error message means, you may be able to figure out what's wrong. In this case, you know that the println() instruction prints text. You learned earlier that the text has to be between quotes. If the text is not quoted, that is an error.<br>
Go ahead and add the quotes back in.<br>
Run your program to make sure it works again.<br>

`Congratulations, you have run and changed your first Kotlin program!`

## 5 Solution code
<br>
For the complete code of the program you worked on in this repository Download it manually and then import to android studio.
<br>
OR
<br>
Copy from here ⬇
<br>

```ruby
fun main() {
    println("Happy Birthday!")
    println("Jhansi")
    println("You are 25!")
}
```
---
## What we learn next
- Print more complex text from your program.<br>
- Do basic math in Kotlin and store the results in variables for later use.<br>
- Create a function to print the same string several times.<br>
- Create a loop that prints a text snippet multiple times.<br>

Inside the `fun main()` function, replace the `"Hello, world!"` text with `"Happy Birthday, Rover!"`.<br>
Below that, still inside the curly braces, add two more lines to print: `"You are already 5!"` and `"5 is the very best age to celebrate!"`.<br>

Your finished code should look like this.
```ruby
fun main() {
    println("Happy Birthday, Rover!")
    println("You are already 5!")
    println("5 is the very best age to celebrate!")
}
```
<br>
Run your code.<br>
Verify that the output pane shows Happy Birthday, Rover! and below that, You are already 5! and 5 is the very best age to celebrate!<br>

```
Happy Birthday, Rover!
You are already 5!
5 is the very best age to celebrate!
```
<br>
A birthday message needs a birthday-themed picture. Like, a cake. You can add a cake to your birthday message by printing additional lines that use the letters and symbols on your keyboards and `println()`<br>

In your code, between the two `println()` statements for `Happy Birthday` and `You are already 5`, add the following lines of print statements, as shown below. This creates a cake. The last `println()` statement has no text between the quotes, which prints an empty line.<br>

```ruby
    println("   ,,,,,   ")
    println("   |||||   ")
    println(" =========")
    println("@@@@@@@@@@@")
    println("{~@~@~@~@~}")
    println("@@@@@@@@@@@")
    println(")
````
<br>







<br>
<br>
<br>
---
## Reference Site<br>
[Google Android Developer Training](https://developer.android.com/courses/android-basics-kotlin/course) "I learn Kotlin from this Google official documentation you can also check for more references")
