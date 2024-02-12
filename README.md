# Voting System

## Description
This is a simple command-line based voting system implemented in C. The system allows for voter registration, candidate application, vote casting, and viewing election results. It supports multiple voters and candidates, with customizable minimum voter and candidate ages, as well as a minimum vote percentage required to win the election.

## Features
- Voter Registration: Allows individuals to register as voters by providing their name, age, and choosing a password.
- Candidate Application: Allows registered voters to apply as candidates by providing their voter ID and password.
- Vote Casting: Registered voters can cast their votes for their preferred candidates.
- View Candidate Information: Displays information about all the candidates including their name, age, and number of votes received.
- View Voter Information: Displays information about all the registered voters including their name, age, and whether they have casted their vote or not.
- View Election Result: Displays the winner of the election based on the number of votes received by each candidate and the minimum percentage of votes required to win.

## How to Use
1. Compile the code using a C compiler such as GCC.
2. Run the compiled executable file.
3. Follow the on-screen prompts to navigate through different options such as conducting an election, registering voters, applying for candidacy, casting votes, and viewing election results.
4. Provide necessary information as requested by the system to perform various actions.

## Notes
- Ensure that all input values are entered correctly and within the specified ranges to avoid errors.
- The system utilizes a basic authentication mechanism for voters and candidates using a voter ID and password.
