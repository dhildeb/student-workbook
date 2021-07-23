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
                d.Patients = p;
                return d;
            }).ToList();

# Wednesday
> Lab
- https://github.com/dhildeb/superKnights

>What is SQL injection?
- its information from the user/hacker that is in the SQL language that is meant to mess up the data in some way.

>What are 3 methods SQL injection can be done by?
- user input
- modify cookies
- HTTP headers

>How can we detect and sanitize SQL injection attacks?
- SQLmap, santitize user input, IDS.

# Thursday
>Write a review and reflection of your experiences in this course, as this is the last lecture before your final project, what are your concerns, how do you plan to manage your time, what have you enjoyed most about the course up to this point.
- Best decision ive ever made! this has not been easy but ive loved nearly every minute of it. i cant believe how fast it has gone by, but even more than that i cant believe how much ive learned. im excited to apply what ive learned in a job setting however i am starting to feel that imposter syndrome. i feel very prepared for the final im going to spend almost every minute of the day coding and i plan on finishing by tuesday. i will be getting plenty of sleep and/or caffiene. 