# Guided Assignment 1
## Code View and Message Box
---
### Goal
The goal of this assignment will have you practice creating a new assignment, uploading it on GitHub, navigating Visual Studio, and learning about the ```MessageBox.Show()``` method.  

---
### Assignment
This assignment will have you 
1. Create a new wpf file
2. Initialize it as a GitHub repository
3. Get practice jumping between code and designer view
4. Adding a ```MessageBox.Show(message)``` to your MainWindow() method
5. Save your project, commit your changes, push your changes

---
### The Result

![Guided Assignment 1 Result](https://raw.githubusercontent.com/WCramRTC/GA_Images/main/GA_1_Images/GA_1_Result.gif)

When you run your code, a small popup with your information should appear.

*You do not need to add anything in the designer.*

---

## <r>Assignment</r>

#### **<r>Step 1 and 2</r> - Create a new WPF Project, Initialize as a repo, and push to GitHub**
(Refer to assignment one if you need to refresh)

1. Create a new WPF project. Name it  
_**GA_1_yourName**_
2. Initialize it as a repository and push it to GitHub

**Result of Step 1 and 2**

[GitHub Repository Example GA_1_WillCram](https://github.com/WCramRTC/GA_1_WillCram)

---
#### **<r>Step 3</r> - Practice Navigating between Designer and Code View**

You will constantly be jumping between the Designer and the Code view of your wpf projects.

There are 2 ways of doing this

1. Solution Explorer

    * In the Solution Explorer **right click** on your .xaml file.
    * A menu will appear. 
    * Select **View Code** to go to the code for that .xaml page
    * Repeat and select **View Designer** to view the designer for the .xaml page

2. Hot Keys
    * Press **F7** for Code View
    * Press **Shift + F7** for Designer View

**Result**

You should easily be able to jump back and forth between the Designer and Code

![Jumping between Designer and Code using Hot Keys](https://raw.githubusercontent.com/WCramRTC/GA_Images/main/GA_1_Images/GA_1_Designer_Code.gif)


---
#### **<r>Step 4</r> - MessageBox.Show(string message)**

The ```MessageBox.Show(string message)``` method creates a popup that dispalys your message when it is called.

We are going to test this by having a message box with your message appear when we first run the code.

In your **code view** you will see a method that has the same name as your .xaml file

```csharp
public partial class MainWindow : Window
{
    public MainWindow() // This method
    {
        InitializeComponent(); // Don't Delete This!
    }
}
```

Inside of your ```MainWindow()``` method, type in.

```csharp
MessageBox.Show("Your name and what you want to do after you graduate");
```

Your could should look like

```csharp
    public MainWindow()
    {
        InitializeComponent();
        MessageBox.Show("Your name and what you want to do after you graduate");
    }
```

**Run Your Code**

When you run your project, a small pop up with your message should appear.

---
#### **<r>Step 5</r> - Save, Commit, Push, Submit**

And your done!!

The last steps are your standard _**workflow**_ when working with GitHub. You
1. **Save your project**
    * I constantly do **ctrl + s** to save as I go.
    * You can also do File -> Save or Save All
2. **Commit** - This creates a save to your local GitHub Repo
    1. Git -> Commit or Stash
    2. Type your Message
    3. Commit

![Gif showing how to commit in Visual Studio](https://raw.githubusercontent.com/WCramRTC/GA_Images/main/GA_1_Images/GA_1_Commit.gif)

3. **Push your repo** - This uploads it to your GitHub online
    * Git -> Push

If you go to your repository online you should now see all your recent changes reflected.

---

## Submitting Your Assignment
Now that your done. Submit the URL to your Guided Assignments repository in Canvas for your assignment.

