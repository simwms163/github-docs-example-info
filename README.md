 # Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown youneed to use three backticks (`)
- Not to be confused with quotation (')
```
# Define a Person class
class Person
  # Constructor
  def initialize(name, age)
    @name = name    # Instance variable for the person's name
    @age = age      # Instance variable for the person's age
  end

  #Instance method to return a greeting
  def greeting
    "Hello, my name is #{@name} and I am #{@age} years old."
  end
end
```


-When you can you should attempt to apply syntax highlighting to your codeblocks

```ruby
# Define a Person class
class Person
  # Constructor
  def initialize(name, age)
    @name = name    # Instance variable for the person's name
    @age = age      # Instance variable for the person's age
  end

  #Instance method to return a greeting
  def greeting
    "Hello, my name is #{@name} and I am #{@age} years old."
  end
end
```

- Make note of where the backtick button is located.
- But it may vary based on your keyboard layout.

  ![image](https://github.com/simwms163/github-docs-example-info/assets/134225066/92cbf81c-bdd5-468c-bd68-646aefadd2cd)

Good Cloud Engineers use codeblocks for both code and errors that appear in the console. 

```bash
Traceback (most recent call last):
        2: from /usr/bin/irb:23:in  `<main>'
        1: from (irb):1
RuntimeError: This is a custom error message
``` 

< Here is an example of using a codeblock for an error that appears in bash.

## Next Step - Use Github Flavored Markdown Task Lists

GitHub extends Markdown to have a list where you can check off items. <sup>[1]</sup>

- [x] Finish First Step
- [x] Finish Next Step
- [x] Finish Another Step

## Followup Step - Use Emojis

GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

## How To Create A Table 

```markdown
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud With Lightning and Rain | `:cloud_with_lightning_and_rain:` | :cloud_with_lightning_and_rain: |
```
:cloud:
:cloud_with_lightning_and_rain:

GiHub extends the functionality of Markdown tables to provide more alignment and table cell formatting cell. [<sup>[2]</sup>](#external-reference)



## References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/gfm/) <sup>[1]</sup>
- [Basic writing and formatting syntax (GitHub Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text) <sup>[2]</sup>
- [Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) <sup>[3]</sup>
- [GitHub Emoji Cheatsheet](https://jimit105.github.io/github-emoji-cheatsheet/) <sup>[4]</sup>
