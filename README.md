# Log debug module

This module provides a series of macros to print messages through the standard C output (in this case associated to a uC serial/uart port).
If the console we use at that moment is standard we will be able to see different debug levels based on the colors. White for information, yellow for warnings and red for errors in parts of the code that we need to signal them. If a standard console is not used we will see some "strange" characters at the end of our debug messages, they are the codes to print with colors in standard consoles. The particularity of this module is that if we do not activate the messages by means of a general macro, the code associated to the printing of the messages is not compiled.

## Deployment

We use [Stable Mainline](https://www.bitsnbites.eu/a-stable-mainline-branching-model-for-git/) for git workflow and branching model.

## Authors

  - [Gonzalo Rivera](gonzaloriveras90@gmail.com)

## License

© 2023 grivera. All rights reserved.
