Markdown-Grammar
=============
This repository shows you how to use markdown so that you can create better documentation and reports


## Table of contents
Headings  
Paragraphs  
Line Break  
Italic  
Bold  
Bold and Italic  
Strikethrough  
Link  
Blockquotes  
Tables  
Ordered Lists  
Unordered Lists  
Images  
Video  

## Headings

# Heading 1

    MARKDOWN: # Heading 1

    OR

    ===========

    HTML5 TAG:  <h1>Heading 1</h1>

## Heading 2

    MARKDOWN: ## Heading 2

    OR

    ------------

    HTML5 TAG:  <h2>Heading 2</h2>

### Heading 3

    MARKDOWN: ### Heading 3

    HTML5 TAG:  <h3>Heading 3</h3>

#### Heading 4

    MARKDOWN: #### Heading 4

    HTML5 TAG:  <h4>Heading 4</h4>

##### Heading 5

    MARKDOWN: ##### Heading 5

    HTML5 TAG:  <h5>Heading 5</h5>

###### Heading 6

    MARKDOWN: ###### Heading 6

    HTML5 TAG:  <h6>Heading 6</h6>

## Heading Best Practices

    DO: # Space between content and your #

    DON'T: #Write without a space between number signs and header content

## Paragraphs

    MARKDOWN: Paragraphs are so much easier in markdown

    HTML5 TAG: <p>Paragraphs are so much easier in markdown</p>

## Paragraphs Best Practices

    DO: Keep content left-aligned like this documentation

    DON'T: Tab or space at the beginning of a paragraph as this can result in bad formatting unless in a list

    Tab Example:

        Hello world

## Formatting

## Line Break

    Markdown: First line, add two spaces at the end [SPACE] [SPACE]    
              Oh hey a new line

    HTML5 TAG: First line, add two spaces at the end <br>
               Oh hey a new line

### Line Break Best Practices

    DO: First line with two spaces after.[SPACE] [SPACE]    
        And the next line.

        First line with the HTML tag after.<br>
        And the next line.

    DON'T: First line with a backslash after.\
           And the next line.

           First line with nothing after.
           And the next line.


*Italic*

    Markdown: What is this *sideways text*.

    HTML5 TAG: What is this <em>sideways text</em>.


*Italic Best Practices*

    For compatibility sake we recommend using * over _
    DO: What is this *sideways text*.

    DON'T: What is this _sideways text_.


**Bold**

    Markdown: That's a **bold statement**.

    HTML5 TAG: That's a <strong>bold statement</strong>.


**Bold Best Practices**

      For compatibility sake we recommend using ** over __
      DO: That's a **bold statement**.

      DON'T: That's a __bold statement__.


***Bold and Italic***

    Markdown: What is this ***sideways and bold text***.

    Alternative Markdown:

              What is this ___sideways and bold text___.

              What is this __*sideways and bold text*__.

              What is this **_sideways and bold text_**.

    HTML5 TAG: What is this <strong><em>sideways and bold text</em></strong>.


***Bold and Italic Best Practices***

    For compatibility sake we recommend using *** over ___
    DO: This is ***the right approach***.

    DON'T: This is ___not___.


~~Strikethrough~~

    Markdown: ~~Strikethrough text~~

    HTML5 TAGS: <strike>Strikethrough text</strike>

                OR

                <s>Strikethrough text</s>


[Links](https://github.com/Styrle)

      Markdown: [Named Link](http://www.google.fr/ "Named link title")

      Markdown Alternatives:

      http://www.google.fr/

      <http://example.com/>

      HTML5 TAG:  <a href="https://github.com/Styrle">Visit my portfolio</a>


## Images Inline
![alt text](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png "Logo Title Text 1")

    MARKDOWN:
    ![alt text](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png "Logo Title Text 1")

    HTML5 TAGS:    
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Github logo">


## Images Reference
![Github logo][logo]

[logo]: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png "Github logo"

    MARKDOWN:
    ![alt text][logo]

    [logo]: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png "Logo Title Text 2"

    HTML5 TAGS:   
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"  alt="Github logo" title="Github logo">


### Images Reference Best Practices

    DO: Add a line break between the alt text and the reference to the image

    DON'T: Put the alt text and image reference next to each other like the markdown text displays


>## Blockquotes

    Markdown:  > Nice Blockquotes

    HTML5 TAG: <blockquote> Nice Blockquotes </blockquote>


## Tables

| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |

    Markdown:
    | Tables   |      Are      |  Cool |
    |----------|:-------------:|------:|
    | col 1 is |  left-aligned | $1600 |
    | col 2 is |    centered   |   $12 |
    | col 3 is | right-aligned |    $1 |

    HTML TAGS:
    <table>
      <tr>
        <th>Tables</th>
        <th>Are</th>
        <th>Cool</th>
      </tr>
      <tr>
        <td>col 1 is</td>
        <td>left-aligned</td>
        <td>$1600</td>
      </tr>
      <tr>
        <td>col 2 is</td>
        <td>centered</td>
        <td>$12</td>
      </tr>
      <tr>
        <td>col 3 is</td>
        <td>right-aligned</td>
        <td>$1</td>
      </tr>
    </table>


## Ordered Lists

    Markdown:
    1. First item
    2. Second item
    3. Third item
        1. Indented item
        2. Indented item
    4. Fourth item

    HTML5 TAGS:
    <ol>
      <li>First item</li>
      <li>Second item</li>
      <li>Third item
    <ol>
      <li>Indented item</li>
      <li>Indented item</li>
    </ol>
      </li>
      <li>Fourth item</li>
    </ol>


## Unordered Lists

    Markdown:
    - First item
    - Second item
    - Third item
        - Indented item
        - Indented item
    - Fourth item

    HTML5 TAGS:
    <ul>
      <li>First item</li>
      <li>Second item</li>
      <li>Third item
    <ul>
      <li>Indented item</li>
      <li>Indented item</li>
    </ul>
      </li>
      <li>Fourth item</li>
    </ul>
