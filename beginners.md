# npc lua learning
#### this treats you as if you do not know a single thing about a programming language
###### also btw this is extremely not finished

hello, if you want to learn how to get scammed by roblox you got it chief

### Simple Hello, World
```lua
print("Hello, World!") -- you should already know how to do this by the millions of memes about it, you can change the "hello, world" part to anything you want
```
### Customising print()
```lua
--example
print("I am a sentient computer") -- just don't forget to have the speech marks
```
there is also different types of print
```lua
warn("Frappe employees most typed word") -- yellow text and icon
error("only use this one if you want your code to stop if it won't stop by itself") -- acts like a code error
assert("i don't even remember how this one works") -- read in the string
```
let's talk about why you need the speech marks
### Variables
```lua
-- if you do something like this
print(Hi)
-- the code is trying to find something in the code named "Hi", if you wanted to make it work you would need to add a variable
local Hi = "Hi" -- this is a variable and they are very useful for making code more readable and quicker
print(Hi)
```
this would now actually print "Hi" instead of not just erroring
### Functions
functions are basically just running a ton of code through one line
```lua
local function test(extra_argument) -- test is the name of the function, and you can optionally add arguments in the brackets, remove if not necessary
   print(extra_argument)
end
test("This is the argument") -- this would print "This is the argument"
```
