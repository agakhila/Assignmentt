# Assignmentt
Examples of S3 and S4.

# Defining an S4 class for student

setClass("student",

         slots = c(name = "character",

                   age = "numeric",

                   GPA = "numeric"))

# Creating an S4 object

s4 <- new("student", name = "Myself", age = 29, GPA = 3.5)



# Displaying the S4 object

print(s4)

> # Creating an S3 object
> s3 <- list(name = "Myself", age = 29, GPA = 3.5)
> 
> # Displaying the S3 object
> print(s3)
$name
[1] "Myself"

$age
[1] 29

$GPA
[1] 3.5

> # Defining an S4 class for student
> setClass("student",
+          slots = c(name = "character",
+                    age = "numeric",
+                    GPA = "numeric"))
> 
> # Creating an S4 object
> s4 <- new("student", name = "Myself", age = 29, GPA = 3.5)
> 
> # Displaying the S4 object
> print(s4)
An object of class "student"
Slot "name":
[1] "Myself"

Slot "age":
[1] 29

Slot "GPA":
[1] 3.5
