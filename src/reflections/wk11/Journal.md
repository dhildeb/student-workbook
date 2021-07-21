# Monday
> Lab
- https://github.com/dhildeb/Vacay

>What does Inheritance accomplish for us in C#?
- inheritance allows us to transfer code from class to class.

>How does Member inheritance work in C#? Does a class inherit all members of the base class?
- All non private members are inherited in C#. keeping base classes simply allows for modification on child classes.

>How does accessibility affect inheritance?
- cant inherit if its private.

# Tuesday
> Lab
- https://github.com/dhildeb/Contracted

>What is the difference between a primary key and a foreign key
- a primary keys are unique and not null, foreign keys reference some other table or attribute.

>What is an Alias?
- an alias is the reference of a name usually a duplicate, to prevent data conflicts

>Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:
- _db.Query<doctors, patients, doctors>(sql,
            (d, p) =>
            {
                d.Creator = p;
                return d;
            }).ToList();

# Wednesday
> Lab
- 

>What is SQL injection?

>What are 3 methods SQL injection can be done by?

>How can we detect and sanitize SQL injection attacks?

# Thursday
> Lab
- 

>Write a review and reflection of your experiences in this course, as this is the last lecture before your final project, what are your concerns, how do you plan to manage your time, what have you enjoyed most about the course up to this point.
