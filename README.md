## Motivation
Many existing remote learning tools focus primarily on one-way content delivery,
resulting in limited student participation and interaction.
We observed that insufficient interaction often reduces engagement
and learning effectiveness.

In addition, we aimed to avoid reliance on high-end hardware.
Instead of increasing hardware requirements,
this system focuses on optimizing software design and communication efficiency,
allowing students to participate using their existing devices.
This approach helps reduce learning inequality caused by hardware limitations.

## Design Principles
- Low hardware requirements
- Low network bandwidth consumption
- High real-time interaction
- Accessibility and fairness in learning

## System Architecture
The system adopts a client-server architecture.
The teacher hosts the server, and both teachers and students connect
by entering the server's IP address and port.

To minimize network load, only drawing coordinates are transmitted.
This lightweight communication design enables stable real-time interaction
even under unstable network conditions.

## Key Features
### Whiteboard Functions
- Drawing tools and eraser
- Undo / redo
- Clear board

### Interactive Teaching Tools
- Real-time chat
- Random student selection
- Hand-raising system
- Announcements
- Q&A quizzes

## Social Impact (SDGs)
This project aligns with:
- **SDG 4: Quality Education**
- **SDG 10: Reduced Inequalities**

By adopting a low-barrier and low-hardware-requirement design,
the system aims to provide equal learning opportunities,
especially in resource-limited or unstable network environments.

## Reflection
This project strengthened my understanding of designing
efficient, human-centered interactive systems.
It also highlighted how software optimization can play
a crucial role in reducing educational inequality.
