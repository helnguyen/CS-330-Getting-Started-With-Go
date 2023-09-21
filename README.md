# CS-330 Getting-Started-With-Go
This repository was created to provide an introduction to the programming language Go also known as Golang, for the use of a class project at Simmons University.

By Hel Nguyen

## History
Go, also known as Golang or Go Language, was developed by Robert Griesemer, Rob Pike, and Ken Thompson at Google in 2007, with the aim of creating a new programming language that would address some of the shortcomings found in existing languages, such as long compilation times, complicated dependencies, and a lack of built-in support for concurrent programming. Go was officially launched as an open-source programming language in 2009. Despite being a relatively newer programming language, Go has gained popularity among software developers due to its simplicity, efficiency, and ease of learning. It is a statically typed, concurrent, and garbage-collected programming language, making it well-suited for various applications, including building high-performance and scalable network services, solving complex computational problems, cloud services, microservices, and, network-related software. 

## Installing Visual Studio Code
One of the best cross-platform Integrated Development Environments (IDEs) for Go development is Visual Studio Code (VS Code), which offers extensive support for the Go programming language through has a large library of many Go-specific extensions. Another popular choice for Go development is GoLand, known for its advanced features such as improved refactoring, import management, autocompletion, package and, type recognition. 

For our purposes, we will be installing Visual Studio Code as our IDE of choice, primarily because it is freely available and accessible to a wide range of users.

Download and install Visual Studio Code from the official website: https://code.visualstudio.com/

## Setting Up Go
To install and set up Go in Visual Studio Code, you can follow these steps:

### Installing 
1. **Install Go**: Before you begin, ensure that you have Go installed on your system. You can download and install it from the official Go website: https://golang.org/dl/

2. **Install Visual Studio Code**: If you haven't already,download and install Visual Studio Code from the official website: https://code.visualstudio.com/

3. **Install Go Extension**: Open Visual Studio Code, and in the Extensions sidebar, search for "Go" in the marketplace. Look for the official Go extension by Microsoft and install it. It is optional but it is also helpful to install "Code Runner" also downloadable in the Extension sidebar.

### Writing "Hello World!" Program

4. **Create a Go Project**: Create a new directory for your Go project. Inside this directory, you can create your Go source code files (`.go` files). In our case write `hello.go`

6. **Write Go Code**: Build code following the code below:  
   ```go
   package main

   import "fmt"

   func main() {
       fmt.Println("Hello, World!")
   }
   ```
### Ensuring Go Is Working Properly

7. **Run and Debug**: Use the integrated terminal to execute commands like `go run` to run your program or click on the play icon on the top right. If code run in the `Output` tab, click on the setting icon in the bottom left corner, select `Setting` > `User` > `Extension` > `Run Code configeration`. Ensure that the `Run In Terminal` box is checked off.

8. **Manage Notifications**: After running the code notificatios may pop up from the `Go (Extension)` depending on your system. Just install all the recommeded modules.

### Commenting on Go
In Go, you can add comments to your code using two different styles: single-line comments and multi-line (block) comments. Here's how you can use both styles:

1. **Single-Line Comments**: To add a single-line comment in Go, you use double slashes `//`. Anything after `//` on the same line is considered a comment and is ignored by the Go compiler.

   ```go
   package main

   import "fmt"

   func main() {
       // This is a single-line comment
       fmt.Println("Hello, World!")
   }
   ```

   Single-line comments are typically used for short comments or explanations on the same line as the code.

2. **Multi-Line (Block) Comments**: For longer comments that span multiple lines, you can use the `/*` and `*/` delimiters. Anything between `/*` and `*/` is treated as a comment block.

   ```go
   package main

   import "fmt"

   func main() {
       /*
       This is a multi-line comment
       that can span multiple lines.
       */
       fmt.Println("Hello, World!")
   }
   ```

   Multi-line comments are often used for documenting code or providing more extensive explanations.


That's it! You've successfully installed and set up Go in Visual Studio Code. You can now start writing, commenting, running, and debugging your Go programs.

## References 
[1] https://www.geeksforgeeks.org/go-programming-language-introduction/ \
[2] https://www.youtube.com/watch?v=E6VOlUKOEI0 \
[3] https://www.bairesdev.com/blog/best-golang-ide-text-editor/ \
[4] https://code.visualstudio.com/docs/languages/go \
[5] https://www.geeksforgeeks.org/how-to-install-golang-in-vscode/ \
[6] https://www.geeksforgeeks.org/hello-world-in-golang/ \
[7] https://tip.golang.org/doc/comment \
[8] https://www.w3schools.com/go/go_comments.php#:~:text=Go%20Single%2Dline%20Comments,(will%20not%20be%20executed).
