# CS-340-Client-Server-Development
Portfolio repository for CS 340 Client/Server Development at Southern New Hampshire University.
# CS-340-Client-Server-Development

Portfolio repository for CS 340 Client/Server Development at Southern New Hampshire University.

## Reflection

### How do you write programs that are maintainable, readable, and adaptable?

I write maintainable, readable, and adaptable programs by separating different responsibilities into different parts of the program and using clear variable, function, and class names. In Project One, I created a CRUD Python module that handled the connection between MongoDB and my Python application. I was then able to reuse this module in Project Two to connect the database to my dashboard. One advantage of this approach was that I did not have to rewrite the database connection and CRUD operations throughout the dashboard code. It also made the program easier to test and modify. In the future, I could reuse or adapt a similar CRUD module for other applications that need to create, read, update, or delete information from a MongoDB database.

### How do you approach a problem as a computer scientist?

I approach a problem by first breaking the requirements into smaller tasks and determining what data and tools are needed for each one. For the Grazioso Salvare project, I first needed to understand the animal shelter data and how MongoDB queries could retrieve the animals that matched specific rescue requirements. I then connected those database queries to the dashboard so the user could filter the data and view the results through the data table, charts, and map. This project was different from some of my previous assignments because multiple components had to work together, including Python, MongoDB, Dash, and the CRUD module. In future projects, I would continue breaking client requirements into smaller problems, testing each component separately, and then integrating the components into the complete application.

### What do computer scientists do, and why does it matter?

Computer scientists use technology and problem-solving skills to create systems that organize information, automate tasks, and help people make better decisions. This matters because software can turn large amounts of data into information that is easier and faster to understand. For a company such as Grazioso Salvare, the dashboard allows users to search animal shelter records, filter animals based on rescue requirements, and visualize important information. Instead of manually searching through thousands of records, employees can use the application to quickly identify animals that may be good candidates for rescue training. This can save time, improve decision-making, and allow the organization to focus more effectively on its work.
