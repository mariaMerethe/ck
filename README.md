# ck
Help file for Bold & Italic:
This test is ***really important***.
Help File for making a link in Markdown:

[LINK]
(https://www.example.com/my%20great%20page)

<a href="https://www.example.com/my great page">link</a>
This is a list!
- First item
- Second item
- Third item

Help for making a Blockquote:
< Dorothy followed her through many of the beautiful rooms in her castle.
<
< The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
T
hat is so funny! :joy:
![An image of a dog](https://i.sstatic.net/Id207.png)


Userstory-003
Images
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3. Close the file.

iAt the command prompt, type `nano`
[Heading IDs] (#heading-ids)

UserStory 006
This is a help file for makin a table in markdown.

To add a table, use three or more hyphens (-) to create each columns header, and use pipes (|) to separate each column.
| Syntax | Description |
|---|---|
|Header | Title|
|Paragraph | Text |

Userstory 015
This is a help file for highlighting certain words in Markdown.
To highlight words, you can do it in two different ways, depending on what markdown processor you've got.
The first way is to put two equal signs before and after the words, like this:
I need to highlight these ==very important words==.

As you can see, you can see the equal signs. That's because this syntax is an extended Markdown feature.

If your Markdown application supports HTML, wich mine those, you can use the mark HTML tag instead. (mark)(/mark) but pointing.
This will look like:
I need to highlight these <mark>Very important words</mark>.

Userstory 016
This is a help file for making a sequence diagram in markdown.

## Sample sequence diagram
Here is a hello world example.
First you write three backticks and the word "mermaid", no space in between.
Then you write:

sequenceDiagram
    participant Bob
    participant Alice

    Bob->>Alice: Hello
    Alice-->>Bob: How are you?
    Note left of Bob: Bob thinks
    Bob->>Alice: I'm good thanks, how about you?
    Alice-->>Bob: I'm doing great.

```mermaid
sequenceDiagram
    participant Bob
    participant Alice

    Bob->>Alice: Hello
    Alice-->>Bob: How are you?
    Note left of Bob: Bob thinks
    Bob->>Alice: I'm good thanks, how about you?
    Alice-->>Bob: I'm doing great.
At the command prompt, type `nano`
[Heading IDs] (#heading-ids)}
erDiagram
CUSTOMER ||--o{ ORDER : places
ORDER ||--|{ LINE-ITEM : contains
CUSTOMER}|..|{ DELIVERY-ADDRESS : uses
| Syntax     | Description | Text        |
| :---       | :-----:     |     ---:    |
| Header     | Title       | Here's this |
| Paragarph  | Text        | And more    |
