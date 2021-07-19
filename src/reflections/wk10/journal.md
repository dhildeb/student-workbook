# Monday
>Lab
- https://github.com/dhildeb/rock-paper-scissors-cs

>What are the three categories of data types? How are they different?
- value type
- reference type
- pointer type

>What are the Value-type data types? What differences do you notice from JavaScript?
- bool, byte, char, decimal, double, enum, float, int, long, sbyte, short, struct, uint, ulong, ushort
- there are a lot more data types in C# than JavaScript

>In your own words how do Reference types get stored in memory? How does this differ from Value types?
- reference types hold an address or key to where the value is actually stored.
- reference types are a location with another location stored in it.

# Tuesday
>Lab
- https://github.com/dhildeb/gregslist-cs

>What is a List in C#?
- a generic type so that it can become any type, great substitute for arrays 

>What List methods seem like you might use them often? Why?
- Count, Add, Contains, ForEach, Find, FindIndex, Remove, RemoveAt
- similar to array methods that i have already used often.

>How would you retrieve an item from a list? What method could you use? 
- list.Find(item => listItem === searchItem)
- you could also use FindIndex and FindAt

# Wednesday
>Lab
- https://github.com/dhildeb/knights-quest-cs

>In a SQL table, what is the difference between information in a row and information in a column?
- a column is a list of all the values in the table, like all the names or ids.
- a row would be an object inside the table with its different attributes divided into columns.

>Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
- CREATE TABLE characters(
  id int NOT NULL PRIMARY KEY AUTO_INCEMENT,
  names varchar(255) NOT NULL,
  age int NOT NULL,
  description varchar(255)
) DEFAULT charset utf8 COMMENT '';

>What is the difference between the following statements: DELETE FROM table_name;
DROP TABLE table_name;
- delete will delete a name from the table and drop table will delete all the names from the table.

# Thursday
>Lab
- https://github.com/dhildeb/AllSpice

>What is an Enum, and what are some use cases for them?

>How can you modify an Enum?

>How have you used Enums in your afternoon lab projects this far?(if you have not yet, give an example of how you could)

# Friday
>This reflection is an open format, so it can be whatever you like. Take this opportunity to write a bit on some of the things you have learned this week, or some of the things that you are still struggling with, identify some challenges you had at the beginning of the week that you were able to overcome, or just generally how you are feeling at this point in the course.
