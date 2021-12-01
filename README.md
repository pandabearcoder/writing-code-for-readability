## Writing code for readability

### Best practices accumulated through years of writing code and doing code reviews

#### 1. Linters

I always recommend that before you start writing code, you prepare your Text Editor/IDE first.

Having a good looking display is great as it will strain your eyes less. But modern Editors and

IDEs can do more than just that. It can help you write code by suggesting you the best practices

developed by large companies and people with long years of experience with writing code. It can

even spot possible errors. This is through the use of linters. Linters are often add-ons to your

Editor/IDE. Install it and let it help you


#### 2. Think and write like an author

I see a lot of starting coders not utilising this simple concept of "blank lines".

Remember when you try to read a book and you saw the pages are so populated with text and

there was no blank lines between paragraphs? Yeah, you probably didn't proceed to read it.

It immediately looks exhausting to read, isn't it?

Same goes with writing code. Try to group your lines of code that are similar then add a

blank line before you write your code that have a different purpose from the line above it.

Think and write like an author. Every line of code are grouped into a "paragraph". And give your

readers some pause.


#### 3. Make your code future-readable and future-understandable rather than future-proof

The common pitfall of most starting coders is that, they try to make their code future-proof.

Meaning, they are already thinking of different possible scenarios that their code could produce

an error once another coder change it. So they code it until it "cannot" fail that it became complicated.

But we know it isn't possible. So the code ended up complicated but still fallible.

So the better way of thinking, is to make it future-readable and future-understandable.

This way, future readers of your code can understand WHY you wrote your code that way.

Remember, it's better to have a code that fails but you understand why, than a code

that works but nobody wants to touch it since it might break.
