[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9528347&assignment_repo_type=AssignmentRepo)
# Linked list queue


We implemented a linked list a while back (and I have put the implementation in `src/queue.py` for your convinience). Today, I want you to implement a queue based on this.

**Exercise:** Implement a queue using doubly-linked lists by filling in the blanks in the code below:

```python
class Queue(Generic[T]):
    """A queue of type-T elements."""

    def __init__(self) -> None:
        """Make a new queue."""
        # FIXME: code here
        ...

    def is_empty(self) -> bool:
        """Check if this queue is empty."""
        # FIXME: code here
        ...

    def enqueue(self, x: T) -> None:
        """Add x to the back of this queue."""
        # FIXME: code here
        ...

    def front(self) -> T:
        """Get the front element of the queue."""
        # FIXME: code here
        ...

    def dequeue(self) -> T:
        """Get the front element, remove it from the queue, and return it."""
        # FIXME: code here
        ...
```
