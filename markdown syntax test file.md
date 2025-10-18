# Heading 1

Add {++this++} here, remove {--this--}, and replace {~~this~>that~~}.

Here is a sentence.[^This is totally necessary inline footnote.] {>>Is this necessary?<<}

{==Here is another sentence.==}{>>What about this?<<}

## Heading 2

<https://daringfireball.net/projects/markdown/syntax#link>

[This is an inline link](https://sublimetext-markdown.github.io/MarkdownEditing/usage/ "Text Formatting")

[And this is a reference link][ref]

[ref]: https://sublimetext-markdown.github.io/MarkdownEditing/ "MarkdownEditing"

![This is an inline image](https://images.unsplash.com/photo-1548199973-03cce0bbc87b?fm=jpg&q=50&w=500 "two doggos")

![And this is a reference image linke][dog]

[dog]: https://images.unsplash.com/photo-1534361960057-19889db9621e?fm=jpg&q=50&w=500And "shallow focus photography of white shih tzu puppy running on the grass"

### Heading 3

This is `inline code`.

    SELECT *
    FROM table
    WHERE column = 'column'

```csharp
public class
{
    private string greeting = string.empty;

    public static void SayHello() //TODO: Change method name to SayHi
    {
        greeting = "Hi!";
        console.print(greeting);
    }
}
```

#### Heading 4

> [!NOTE]
>
> This is a note.

For the linter!

> [!TIP]
>
> This is a tip.

For the linter!

> [!IMPORTANT]
>
> This is _important_.[^2]

For the linter!

> [!WARNING]
>
> This is a **warning**.

Praise the linter!

> [!CAUTION]
>
> This is a **_caution_**.[^1]

##### Heading 5

**Tasks:**

- [ ] This is an _unfinished_ task.
- [x] This is a _finished_ task.

**Ordered list:**

1. First
2. Second
3. Third

**Unordered list:**

- Level 1
    + Level 2
        * Level 3

###### Heading 6

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. ~~Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur.~~ Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
> tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
> quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
> consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
> cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
> proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


---

Here is some math ${e}^{i\pi }+1=0$.

And some more:

$${e}^{i\pi }+1=0$$

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

[^1]: **_This_** is very important.
[^2]: This quote isn't actually important, but it _is_ a reference footnote.
