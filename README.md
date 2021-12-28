# CST211-Lab5
Lab 6
Stack – List Implementation
Description
Develop a Circular Queue class based on an Array (from Lab 1).
UML Class Diagram

template:T

CircularQueue

private:
* m_queue: Array
* m_size: int
* m_head: int

public:
* Enqueue(in data: T): void
* Dequeue(): T
* <<const>> Peak(): T
* <<const>> getSize(): void
* <<const>> isEmpty(): bool
* <<const>> isFull(): bool

Stipulations
* Throw Underflow and Overflow exceptions using your Exception class where appropriate.
* Although not shown in the UML class diagram, include the appropriate manager functions. (Be sure to have the correct ones! ☺)
* Selected function explanations:
** Peek – Return the data at the head/front of the list.

Deliverables
One file including:
Your code
Your test(s) similar to Lab1_test.cpp & Lab2_test.cpp and their results

