# Thoughts on multithreaded programming

## What is multithreaded programming anyway ?

Multithreaded programming in the most general sense is the act of creating and manipulating multiple threads, which is used to concurrently run the user code so that the program executes faster. It involves maximizing the CPU usage since for all computers, the CPU runs way faster than the main memory, memory bus, etc. So the CPU will be on idle while it wait for the other component and not fully utilized if we just use multithreading to its fullest potential.

## Is it useful ?

Multithreading is present everywhere in our daily life. From our browser that let us download file and listen to music at the same time. Or to the most website we use everyday that handles thousand of users concurrently by creating threads.

## But it is very hard

Multithreading can always be a pain to developer. Just imagine the bugs you cause when your program is only single threaded. But now there are multiple thread causing the multiples of those bugs lol. This leads to many problems like dead lock, starvation, race condition, concurrent modification. And these problems are usually very hard to detect by the eyes, these are logical problems to be fair. But now you don't need to worry much about it since:

## Most of it have been abstracted away by now

As time move on much of this have been abstracted away from the programmer by the multiple tools given to make our daily life much easier. For example,the server we use for deploying our web application. They handle thousand of users by creating multiple threads for each user. Or Javascript gives us promises, async, await or Python also gives us async, await to give the programmer an easier time writing "single-threaded", "non-blocking" code. But nothing is ever really "single-threaded". The behind the scene involves a thread pool that execute those promises, async, await function and an event queue that notify the main thread. This makes life so much easier for the programmer and speed up the development process greatly since not everyone can handle multithreaded programming with confidence.

## Should you still learn it though ?

Yes and 100% yes. Because IMO, it gives us a new way of thinking, a new way of solving the problem. We can imagine the problem and how to solve it if we had multiple thread doing things at the same time. And besides I find it very fun as well.

## How to learn it ?

I would recommend learning it using the book The little book on semaphores. Great book on concurrency problems. And it is fairly short, you only need to read like 200 pages.