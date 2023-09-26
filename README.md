# Github Docs Example

## Step 1 - Using Codeblocks.

**Codeblocks** in markdown make it *very easy* for tech guys to **copy, paste, share code.**
A good Cloud Engineer uses Codeblocks whenever possible.

Because it allows others to copy and paste their codes to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with qoutation (')

# Define a Person class
class Person
  # Constructor
  def initialize(name, age)
    @name = name    # Instance variable for the person's name
    @age = age      # Instance variable for the person's age
  end

  # Instance method to return a greeting
  def greeting
    "Hello, my name is #{@name} and I am #{@age} years old."
  end
end

- When you can you should attempt to apply syntax highlighting to your codeblocks

# Define a Person class
class Person
  # Constructor
  def initialize(name, age)
    @name = name    # Instance variable for the person's name
    @age = age      # Instance variable for the person's age
  end

  # Instance method to return a greeting
  def greeting
    "Hello, my name is #{@name} and I am #{@age} years old."
  end
end

- Make note of where the backtick keyboard key is located.
- It should appear above the tab key,
- But it may vary based on your keyboard layout.
