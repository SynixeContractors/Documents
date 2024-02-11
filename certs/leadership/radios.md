# Leadership - Radios

## Command Net

Using the command net effectively and correctly is a key part of being a leader. It is important to be able to communicate with other teams, and to be able to do so quickly and accurately.

The key is to be quick, clear, and concise. Always know what you are going to say before you call for the attention of the net.

## Radio Lingo

| Term | Meaning |
| --- | --- |
| Roger | Message received and understood |
| Wilco | Message received, understood, and will comply |
| Repeat Repeat Repeat | Repeat the last support action (mortar, cas, etc.) |
| Say Again | Repeat the last message |
| Break | Indicates a pause in the conversation |
| Break, Break, Break | Indicates a time-critical message |
| Over | Indicates the end of your transmission, and that you are expecting a response |
| Out | Indicates the end of your transmission and the conversation |
| Wait one | I need to check something, less than a 30 second delay |
| Wait out | I need to check something, more than a 30 second delay, ends the conversation, and the station will call back when ready |

### Conversation Structure

It is important to follow a predictable structure when communicating on the command net.

1. Initiate a conversation
    * Identify the station you are calling
    * Identify yourself
    * State the purpose of the call

2. Wait for the station to respond
    * Give them time to respond, they may be busy

3. The conversation goes back and forth
    * Start each message with the station you are talking to
    * When getting an instruction, repeat it back when possible to ensure you understand
    * End your messages with "over" to indicate you are done speaking
    * Leave a pause before responding to allow stations to interject
    * End the conversation with "out" to indicate you are done speaking

Only the station initiating the conversation that initiated the conversation should end with "out", after all messages are acknowledged

#### Examples

Scenario: Teams are moving towards a waypoint, and need to coordinate their movements.

```ansi
[2;31mRed[0m: Command, this is Red, message, over.
[2;33mCommand[0m: Red, Command, send your message, over.
[2;31mRed[0m: Command, we are at the waypoint, ready to move, over.
[2;33mCommand[0m: Red, Command, wait for Blue to reach theirs, then clear the buildings, over.
[2;31mRed[0m: Command, understood, will move when Blue is ready, over.
[2;33mCommand[0m: Red, Command, acknowledged, over
[2;31mRed[0m: Command, Red, out.
```

This may seem like a lot of extra words, but it is important to ensure that everyone is on the same page, and that the message is clear and understood. During high stress situations, it is easy to miss or misunderstand a message, and this structure helps to mitigate that. It is ok to cut things down a little when required, but the general structure should be maintained.

Scenario: Teams are in contact, and need to coordinate their movements.

```ansi
[2;31mRed[0m: Command, this is Red, message, over.
[2;33mCommand[0m: Red, Command, send , over.
[2;31mRed[0m: Command, we are taking heavy fire to the north, need support, over.
[2;33mCommand[0m: Red understood, sending a team to support, over.
[2;31mRed[0m: Command, copy that, out.
[2;33mCommand[0m: Blue, command, urgent, over.
[2;34mBlue[0m: Command, Blue, send, over.
[2;33mCommand[0m: Blue, we need you to support Red to your west, taking fire from the north, over.
[2;34mBlue[0m: Command, Blue, understood, moving to support, over.
[2;33mCommand[0m: Blue, command, acknowledged, out.
```

### Interjection

Sometimes, you may need to interject into a conversation. This is usually done by saying "Break, break, break", and then your station. This is usually done when there is a time-critical message that needs to be passed, and the current conversation is less important to the current situation. After calling for a break, wait for all stations to stop transmitting, a second or two to ensure they are done, and then pass your message.

```ansi
[2;31mRed[0m: Command, this is Red, message, over.
[2;33mCommand[0m: Red, Command, send your message, over.
[2;31mRed[0m: Command, we are at the waypoint, ready to move, over.
[2;33mCommand[0m: Red, Command, wait for Blue to reach theirs, then clear the buildings, over.
[2;34mBlue[0m: break, break, break, Blue
**All stations should stop transmitting, blue waits a second, then transmits**
[2;34mBlue[0m: Command, Blue, we have a large element that just arrived to our west, we are taking heavy fire, over.
[2;33mCommand[0m: Blue, Command, understood, we'll send support, over.
[2;34mBlue[0m: Command, Blue, copy, out.
[2;33mCommand[0m: Red, Command, move immediately to support Blue, over.
[2;31mRed[0m: Command, Red, understood, moving to support, over.
[2;33mCommand[0m: Red, Command, acknowledged, out.
```
