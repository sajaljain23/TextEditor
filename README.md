# Text-Editor
This program implements a text editor using Linked List and Stack data structures.

Each line of text is saved into a linked list node, which consists of a data portion holding the text and a pointer to the next node of the linked list, which is the next line of the text. The program utilizes the Stack data structure to implement the Undo function, enabling users to revert changes made to the text. It provides a robust and efficient solution for managing and editing text.

Contributions to enhance the functionality and performance of the text editor program are welcome. Feel free to open issues and submit pull requests.

## Features:

-Open and Parse: Open an existing file and parse each line into a linked list for efficient storage and retrieval.

-Save: Save the edited text back into a file, preserving the modifications made.

-Insert: Insert text into a specific line (user-provided line number and text), allowing easy insertion of content at any position.

-Delete: Delete a line (user-provided line number), facilitating the removal of unwanted lines from the text.

-Move: Move a line (user-provided source line number) to a new position (user-provided destination line number), enabling the interchange of two lines.

-Replace: Replace the text in a specific line (user-provided line number and text), providing the ability to update content seamlessly.

-Next Page: Navigate to the next page of the text, useful for browsing lengthy texts that exceed the display capacity.

-Previous Page: Navigate to the previous page of the text, facilitating smooth navigation through extensive texts.

-Undo: Utilize the Stack data structure to implement an Undo feature, allowing users to revert the most recent action. Please note that this feature may have slight bugs and limitations.
