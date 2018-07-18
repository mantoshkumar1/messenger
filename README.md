#Messenger (In Progress):

This application offers a Player class. An instance of this class communicate with other Player(s) (other instances of this class).
Please use pure Java as much as possible (no additional frameworks like spring, etc) and builds a maven project.

This application focuses on design and not on technology, that means the used technology is as simple as it could be. 
The focus of the application is to deliver (and practice patter) the cleanest and clearest design that we can achieve.

##Having a Player class - an instance of this class with that can communicate with other Player(s) (other instances of this class)

#### The use case for this task is as bellow:
The use case for this application is as bellow:

1. create 2 players

2. one of the players should send a message to second player (let's call this player "initiator")

3. when a player receives a message should send back a new message that contains the received message concatenated with the message counter that this player sent.

4. finalize the program (gracefully) after the initiator sent 10 messages and received back 10 messages (stop condition)

5. both players should run in the same java process (strong requirement)

###6. document for every class the responsibilities it has.

# Future Extension
Have every player in a separate JAVA process.


Please deliver a maven project with the source code to build the jar. Please send the sources as archive attached to e-mail (eventual links for download will be ignored!!!).
Please provide a shell script to start the program.
Everything what is not clearly specified is to be decided by developer. Everything what is specified is a hard requirement.
Please focus on design and not on technology, the technology should be the simplest possible that is achieving the target.
The focus of the exercise is to deliver the cleanest and clearest design that you can achieve (and the system has to be functional).
