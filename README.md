# The last supper
This project is about a peer implementation for group communication via UDP. The language is Python.

## Requirements
These are the requirements for the implementation:
- Each peer has an ID
  - These IDs may be conflicted but in general are unique
- Each peer knows all peer IDs and their IP addresses in form of a list in a config file
- They send UDP messages
- The communication protocol or implementation has to work for 5 participants
- Each message has a unique ID comprised of the peer ID that has sent it and a sequence number

## General overview
Each peer is comprised of the following components:
- UI
  - Everything can be done via this UI, i.e.
    - Configuration
    - Message sending
    - Displaying messages and writing them to logs
- Middleware
  - This component sends and receives messages
- OS / Web
  - This component is implicitely there
  - This project

# UI definition
TBD
