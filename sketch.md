Sketch

## Sketch

<b>String: One of the most widely used data types is a string. A string consists of one or more characters, which can include letters, numbers, or other types of characters. You can think of a string as plain text.
A string represents alphanumeric data. This means that a string can contain many different characters, but they are all considered as if they were text, even if the characters are numbers. A string can also contain spaces. This presents a bit of an issue. How are you going to distinguish between the value of a string and the actual code of the program? The solution is to mark the beginning and end of a string with a special character, typically a quote. For example, the following code is used to print text to the screen:
print 'Hello World!'
The use of quotes ensures that the text 'Hello World!' is recognized as a string and not as two separate words that may have some special meaning in the programming language. The use of quotes also makes it possible to use numeric characters as part of a string. For example, the following code is used to store a street address:
address = '123 Central Avenue'
Without the quotes, the numeric characters 123 would be interpreted as a number, but with the quotes, it is recognized as being part of a string that represents a street address. 
 
<b>Boolean<b>: The Boolean data type can only represent two values: true or false. Typically, a 1 is used to represent True, and a 0 is used to represent False. Consider the following example where a user inputs two values and the program determines whether the first one is smaller than the second one or not.
x = 8
y = 7
xy
In this example the first value is in fact not smaller than the second one, and the program therefore results in a Boolean value of False. The Boolean type is the primary results of conditional statements, which are used to control workflow in program. For example, if a particular condition is true, then do this - if the condition is false, then do something else. 

<b>Integer<b>: An integer is a numeric value without a decimal. Integers are whole numbers and can be positive or negative. Sometimes a distinction is made between short and long integers, referring to how much data storage is used for the number. A short integer is typically stored using 16 bits, which means you can store up to 2^16, or 65,536, unique values. For any numbers larger than that, you would need to use a long integer, which uses 32 bits or more.

<b>Float<b>: Floating point data types, usually represent values as high-precision fractional values (rational numbers, mathematically), but are sometimes misleadingly called reals (evocative of mathematical real numbers). They usually have predefined limits on both their maximum values and their precision. Output of these values are often represented in a decimal number format.

<b>Array<b>: An array is a group of variables that share the same data type, and are referred to by a common name. Arrays of any type can be created and may have one or more dimensions.
A specific element in an array is accessed by its index. The array index ranges from 0 to n−1; therefore, in an array of size 10, the first element is stored at index 0 and the last or the 10th element at index 9.

<b>Object Hash<b>: An object’s hash code allows algorithms and data structures to put objects into compartments, just like letter types in a printer’s type case. The printer puts all “A” types into the compartment for “A”, and he looks for an “A” only in this one compartment. This simple system lets him find types much faster than searching in an unsorted drawer. 

<b>data vs. information<b>: There is a subtle difference between data and information. Data are the facts or details from which information is derived. Individual pieces of data are rarely useful alone. For data to become information, data needs to be put into context. 

<b>database relationships<b>: 
    belongs-to:  
    has-many: 
    one-to-one: In a one-to-one relationship, a row in table A can have no more than one matching row in table B, and vice versa. A one-to-one relationship is created if both of the related columns are primary keys or have unique constraints.
    This type of relationship is not common because most information related in this way would be all in one table. You might use a one-to-one relationship to:
    Divide a table with many columns.
    Isolate part of a table for security reasons.
    Store data that is short-lived and could be easily deleted by simply deleting the table.
    Store information that applies only to a subset of the main table.
    The primary key side of a one-to-one relationship is denoted by a key symbol. The foreign key side is also denoted by a key symbol.
    many-to-many: In a many-to-many relationship, a row in table A can have many matching rows in table B, and vice versa. You create such a relationship by defining a third table, called a junction table, whose primary key consists of the foreign keys from both table A and table B. For example, the authors table and the titles table have a many-to-many relationship that is defined by a one-to-many relationship from each of these tables to the titleauthors table. The primary key of the titleauthors table is the combination of the au_id column (the authors table's primary key) and the title_id column (the titles table's primary key).
