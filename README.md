# RailsTraining
A guide to go from Zero Ruby knowledge to a Rails Ninja. Read On!!

## Object Oriented Programming
Lets start with the basics, You need to Google everything thats written henceforth.

* What really is OOP(Object Oriented Programming)?
* How is it different from Procedural Programming?
* Why do we need OOP?
* Explore basic concepts of Java as an OOP Language.

## Ruby

* What is Ruby?
* How is it a Pure Object Oriented Language? How is it different from Java?

### Installation

We are going to use `rvm` to install Ruby on our systems.

Please log onto https://rvm.io and follow the installation instructions according to the machine you have. (Mac/Linux/Windows)

Once done, install Ruby `2.3` which is the latest stable version at the time of this writing as follows:

```
rvm install 2.3
```

Install a Text Editor which we will use to write Ruby code. You can choose from: `Atom`,`Sublime Text`,`Brackets`,`Visual Studio Code` etc. No IDE's please :)

### Going into the Battlefield

I will assume you have Ruby & a Text Editor installed. Lets try to write a Hello World program in ruby and try to execute it to check if the environment is setup properly.

Create a folder RailsTraining on your system and a file named `hello.rb` inside it with the following content:

```Ruby
# hello.rb
puts 'Hello World'
```

Go to the terminal/commandline and execute these lines

```
# cd RailsTraining
# ruby hello.rb
```

And you should see the following Output on your terminal:

```Hello World!```

If this goes well, congratulations, you're all set.

#### Some More Theory

Whatever concepts we are going to read about further, I would encourage you to read and implement them as well.

##### Basics

* irb (Interactive Ruby)
* Control Structures/ Loops in Ruby. (If, Unless, Each, Case etc)
* Methods
* Classes
* Instance Methods, Class Methods, `self`
* Instance Variables, Class Variables, Global Variables.
* `attr_reader`, `attr_writer`, `attr_accessor`
* Access Control (public, protected, private)
* Modules
* How to achieve Multiple Inheritance in Ruby.
* Inheritence, Mixins, `include` & `extend`
* `reuqire` & `load`
* Bundler

##### Metaprogramming

* What is Metaprogramming?
* How it helps us.
* `method_missing`, `define_method`, `send` methods
* `class_eval` / `instance_eval`

##### Advanced

* Exceptions (try, catch, except)
* Duck Typing
* What are Gems/Engines?
* What is an EigenClass?
* How a method is looked up when called?
* Monkey Patching


## MVC

* What is MVC(Model View Controller) Pattern?
* Why do we need it?
* What goes where? What part of the app code goes into the Model, Controller & View?

## Rails

Rails is a Web Framework made in Ruby. Its USP is that it helps you in creating Web Applications really fast. It is a Ruby gem. The latest version is `5.0.0.1`

### Installation

The following will install the latest version if `Rails` on your system.

```
gem install rails
```

### Creating a new app in Rails

The following command will create a new Rails app:

```
rails new my_first_app
```