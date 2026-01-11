# The last supper
This project is about a peer implementation for group communication via UDP. The language is Python.

This are the requirements:
- Each peer has an ID
  - These IDs may be conflicted but in general are unique
- Each peer knows all peer IDs and their IP addresses in form of a list in a config file
- They send UDP messages
- The communication protocol or implementation has to work for 5 participants
- Each message has a unique ID comprised of the peer ID that has sent it and a sequence number
