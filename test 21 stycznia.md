
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
# Nagłówek jest w krzyżyku #  
## W dwoch krzyżykach jest podnagłówek ##
### A w trzech krzyżykach taki maly podtytulik.  

  
*You **can** combine them*  
*Gwiazdka da nam kursywę.*  
_Underscore też da nam kursywę._  

**Dwie gwiazdki dadzą pogrubienie czyli *wytluszczenie*.**  

L I STS
Unordered
Ordered
* Item 1
* Item 2
* Item 2a
* Item 2b
1. Item 1
2. Item 2
3. Item 3
* Item 3a
* Item 3b  
  1. To będzie lista numerowana
  2. A to jej drugi punkt.
  3. A to trzeci.  
1. A jak zacząć nową listę?
2. MOże tak?
3. Chyba działa. 

* A teraz lista wypunkktowana
* I jej drugi podppunkt. 
* A także trzeci.



BACKSLASH ESCAPES  
\*literal asterisks\*  
*literal asterisks*  
Markdown allows you to use backslash escapes to generate literal characters which would otherwise have special meaning in Markdown’s formating syntax.  
Gdy chcemy prawdziwą gwiazdkę, 
* to dodajemy ukośnik.  
  \* Bo inaczej będzie lista wypunktowana.\*  


IMAGES  
![GitHub Logo](/images/logo.png)  
Format:    
![Alt Text](url)  
A teraz będziemy wstawiać obrazki.   
![tu będzie obrazek](./praca%20domowa/apply.jpg)  
![tu będzie drugi obrazek](./praca%20domowa/czerwonykapturek.png)  
![tu będzie trzeci obrazek](./praca%20domowa/English.docx)  
![tu będzie czwarty obrazek](./praca%20domowa/English.jpg)  
![tu będzie piąty obrazek](./praca%20domowa/English.pdf)  
![i jeszcze jeden](./praca%20domowa/English2.jpg)


A tu będą obrazki z innych źródeł

[tu będzie obrazek](https://st.depositphotos.com/1000792/3933/v/950/depositphotos_39337247-stock-illustration-playful-tubby-kitten.jpg)  
![to jest ten sam obrazek](https://st.depositphotos.com/1000792/3933/v/950/depositphotos_39337247-stock-illustration-playful-tubby-kitten.jpg)  
LINKS

http://github.com - automatic!  
[GitHub](http://github.com)  

BLOCKQUOTES  
As Kanye West said:
> We're living the future so
> the present is our past.

BACKSLASH ESCAPES  
\*literal asterisks\*  
*literal asterisks*  
Markdown allows you to use backslash escapes to generate literal characters which would otherwise have special meaning in Markdown’s formating syntax.
Markdown provides backslash escapes for the following characters:  
\ backslash  
` backtick  
* asterisk  
_ underscore  
{} curly braces  
[] square brackets  
() parentheses  
# hash mark  
+ plus sign  
- minus sign (hyphen)  
. dot  
! exclamation mark  

FENCED CODE BLOCKS
```javascript
function test() {
console.log("look ma`, no spaces");
}
```
Markdown coverts text with four leading spaces
into a code block; with GFM you can wrap your code
with ``` to create a code block without the
leading spaces. Add an optional language identifier
and your code with get syntax highlighting.

TABLES  
First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2  
Content cell 1 Content cell 2
Content column | 1 Content column 2
i coś tam | i coś jeszcze  

GITHUB FLAVORED MARKDOWN  
Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.  
You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe | :

EMOJ I  
To see a list of every image we support, check out www.emoji-cheat-sheet.com  
ISSUE REFERENCES  
Any number that refers to an Issue or Pull Request will be automatically converted into a link.  
#1  
defunkt#1  
defunkt/github-flavored-markdown#1  
GitHub supports emoji!  
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:
