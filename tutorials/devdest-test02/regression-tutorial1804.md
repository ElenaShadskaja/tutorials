---
title: Resgression Tutorial with all components 13/06 11-31am
description: example
tags: [products>sap-hana, products>sap-hana-cloud-platform, tutorial>beginner]
primary_tag: tutorial:product/sapHana
---


You can use:

***Image by link***
![Image](https://photos.app.goo.gl/SMHb64Ku3XWmidRe9)


***Text*** (including bold, italic, etc)

  **Example:** 
It's very easy to make some words **bold** and other words *italic* and ***bold italic*** with Markdown.

You can use ~~strikethrough~~ font

***Headers***

  **Example:** 
## This is an h2 header 
### This is an h3 header
###### This is an h6 header

***Lists***

  **Example:** 
  
Sometimes you want numbered lists:

1. One 
2. Two 
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

You can create nested lists: 

* item1
    * one_one
    * two

***Blockquotes***

  **Example:** 
In the words of Abraham Lincoln:
> Pardon my French

***Links***

  **Example:** 
[Primer] [id]:
[id]: http://tut.by

<http://tut.by>

<address@example.com>

***There are three different types of messages: Note, Caution and Warning.***

>### Warning
>jhkjhkjhkjhkj
>>### Warning
>>>### Warning
>>>>### Warning
>>>>This is a Warning. 

&nbsp;

>### Caution
>iikjhiojhioji
>>### Caution
>>This is a Caution. 

&nbsp;

>### Testyy
>This is a note. 

&nbsp;


***Task Lists*** (Please note, this requires empty line before task list):

  **Example:** 
  
- [x] @mentions, #refs, [links](), **formatting**, and ~~tags~~ supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

***Tables:***

  **Example:** 

First Header | Second Header | Third Header | Fourth Header | Fifth Header | Sixth Header
------------ | ------------- | ------------ | ------------- | -------------| -------------
Content from cell 1 | Content from cell 2 | Content from cell 3 | Content from cell 4 | Content from cell 5 | Content from cell 6
Content in the first column | Content in the second column | Content in the third column | Content in the fourth column | Content in the fifth column | Content in the sixth column


and

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |


***You can use ONE! VIDEO:***

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]


[ACCORDION-BEGIN [STEP 1](Accordion component which contains Images in Body)]
    
2nd video

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 2](Accordion component which contains link(s) in Body)]
Select a tutorial from the [Tutorial Navigator](http://go.sap.com/developer/tutorial-navigator.html) or the [Tutorial Catalog](http://go.sap.com/developer/tutorials.html)
3d video

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 3](Accordion component which contains tables in Body)]
***Tables:***

  **Example:4th video** 

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


and

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 4](Accordion component which contains markup code in Body)]

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 5](Accordion component which contains Text in Body)]
We are currently in open beta for the new SAP community. Here's your opportunity to test out the new features and give us your feedback. Not in the mood to try out the new community just yet? Then continue on to the SAP Community Network (SCN) where you currently collaborate with other members.

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]

We are currently in open beta for the new SAP community. Here's your opportunity to test out the new features and give us your feedback. Not in the mood to try out the new community just yet? Then continue on to the SAP Community Network (SCN) where you currently collaborate with other members.

 **Example:Swift** 
```swift
let apples = 3
let oranges = 5
let appleSummary = "I have \(apples) apples."
let fruitSummary = "I have \(apples + oranges) pieces of fruit."
class TriangleAndSquare {
    var triangle: EquilateralTriangle {
        willSet {
            square.sideLength = newValue.sideLength
        }
    }
    var square: Square {
        willSet {
            triangle.sideLength = newValue.sideLength
        }
    }
    init(size: Double, name: String) {
        square = Square(sideLength: size, name: name)
        triangle = EquilateralTriangle(sideLength: size, name: name)
    }
}
var triangleAndSquare = TriangleAndSquare(size: 10, name: "another test shape")
triangleAndSquare.square.sideLength
triangleAndSquare.triangle.sideLength
triangleAndSquare.square = Square(sideLength: 50, name: "larger square")
triangleAndSquare.triangle.sideLength
enum ServerResponse {
    case Result(String, String)
    case Error(String)
}

let success = ServerResponse.Result("6:00 am", "8:09 pm")
let failure = ServerResponse.Error("Out of cheese.")

switch success {
    case let .Result(sunrise, sunset):
        let serverResponse = "Sunrise is at \(sunrise) and sunset is at \(sunset)."
    case let .Error(error):
        let serverResponse = "Failure...  \(error)"
}
extension Int: ExampleProtocol {
    var simpleDescription: String {
        return "The number \(self)"
    }
    mutating func adjust() {
        self += 42
    }
 }
7.simpleDescription
```

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 6](Accordion component which contains Headers in Body)]
***Headers***

  **Example:** 

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]
## This is an h2 header

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]
### This is an h3 header

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]
###### This is an h6 header

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 7](Accordion component which contains Lists in Body)]
***Lists***

  **Example:** 
  
Sometimes you want numbered lists:

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]
1. One
2. Two 
3. Three

Sometimes you want bullet points:

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]
* Start a line with a star
* Profit!

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 8](Accordion component which contains nested lists in Body)]
You can create nested lists: 

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]
* item1
    * one_one
    * two

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 9](Accordion component which contains Blockquotes in Body)]
***Blockquotes***

  **Example:** 
In the words of Abraham Lincoln:

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]
> Pardon my French

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 10](Accordion component which contains types of messages (Note, Caution and Warning) in Body)]
***There are three different types of messages: Note, Caution and Warning.***

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]
>### Warning
>jhkjhkjhkjhkj
>>### Warning
>>>### Warning
>>>>### Warning
>>>>This is a Warning. 

&nbsp;

>### Caution
>iikjhiojhioji
>>### Caution
>>This is a Caution. 

&nbsp;

>### Note

>This is a note. 

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 11](Accordion component which contains Task Lists in Body)]
**Task Lists*** (Please note, this requires empty line before task list):

  **Example:** 
  
  [EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]  
- [x] @mentions, #refs, [links](), **formatting**, and ~~tags~~ supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 12](Accordion component which contains code block and no code block in Body)]
***Code blocks:***

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]

```markup
 quit;
 !@#$%^&*&*(*(()_++|"}?><>??*&^%#!~~~~@33123-090=|"]?>{}|\\
  require 'redcarpet'
  markdown = Redcarpet.new("Hello World!")
  puts markdown.to_html
  exit;
```

```js
 quit;
 !@#$%^&*&*(*(()_++|"}?><>??*&^%#!~~~~@33123-090=|"]?>{}|\\
  require 'redcarpet'
  markdown = Redcarpet.new("Hello World!")
  puts markdown.to_html
  exit;
```

[EMBEDDED-VIDEO [](/content/dam/site/sapcom/multimedia/2017/12/746085f5-e27c-0010-82c7-eda71af511fa.mp4)]

[DONE]
[ACCORDION-END]

***Validation rules***

[ACCORDION-BEGIN [STEP 1]( Extra match rule)] 
[VALIDATE_1]
[ACCORDION-END]

 
[ACCORDION-BEGIN [STEP 2]( Regex Sub-string)] 
[VALIDATE_2]
[ACCORDION-END]


[ACCORDION-BEGIN [STEP 3](Regex begins with)] 
[VALIDATE_3]
[ACCORDION-END]
 
 
[ACCORDION-BEGIN [STEP 4](Regex with id Exact Match)] 
[VALIDATE_4]
[ACCORDION-END]
 
 
[ACCORDION-BEGIN [STEP 5](http-status-check 404)] 
[VALIDATE_5] 
[ACCORDION-END]


[ACCORDION-BEGIN [STEP 6](http-status-check 301, 401)] 
There are advances being made in science and technology everyday, and a good example of this is the LCD monitor. LCD monitors have several benefits over the old chunky computer monitors that most users are familiar with?

[VALIDATE_6] 

There are advances being made in science and technology everyday, and a good example of this is the LCD monitor. LCD monitors have several benefits over the old chunky computer monitors that most users are familiar with?

**Example:html** 

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/xhtml;charset=UTF-8"/>
<title>Related Pages</title>
<link href="qt.css" rel="stylesheet" type="text/css"/>
</head>
<body>
<div class=header>
<a class=headerLink  href="index.html">Main Page</a> &middot;
<a class=headerLink  href="classoverview.html">Class Overview</a> &middot;
<a class=headerLink  href="hierarchy.html">Hierarchy</a> &middot;
<a class=headerLink  href="annotated.html">All Classes</a>
</div>
<!-- Generated by Doxygen 1.8.1.2 -->
</div><!-- top -->
<div class="header">
  <div class="headertitle">
<div class="title">Related Pages</div>  </div>
</div><!--header-->
<div class="contents">
<div class="textblock">Here is a list of all related documentation pages:</div><div class="directory">
<table class="directory">
<tr id="row_0_" class="even"><td class="entry"><img src="ftv2node.png" alt="o" width="16" height="22" /><a class="el" href="classoverview.html" target="_self">Class Overview</a></td><td class="desc"></td></tr>
<tr id="row_1_"><td class="entry"><img src="ftv2lastnode.png" alt="\" width="16" height="22" /><a class="el" href="thelayoutsystem.html" target="_self">The Layout System</a></td><td class="desc"></td></tr>
</table>
</div><!-- directory -->
</div><!-- contents -->
<div class="footer" />Generated with <a href="http://www.doxygen.org/index.html">Doxygen</a> 1.8.1.2</div>
</body>
</html>
```

[ACCORDION-END]


[ACCORDION-BEGIN [STEP 7](http-status-check 200)] 
[VALIDATE_7] 
[ACCORDION-END]


[ACCORDION-BEGIN [STEP 8](single-choice rule)] 
[VALIDATE_6] 
[VALIDATE_8] 
[ACCORDION-END]


[ACCORDION-BEGIN [STEP 9](multiple-choice rule)] 
[VALIDATE_6] 
[VALIDATE_9] 
[ACCORDION-END]


[ACCORDION-BEGIN [STEP 10](multiple-choice rule + single-choice rule)] 
[VALIDATE_9] 
[VALIDATE_8]
[ACCORDION-END]
  
   **Image from another folderS. Example: folder_with_images/inner_folder/image.png (png format)**
   
   ![folder](folder_with_images/inner_folder/window.png)
   
   
  [ACCORDION-BEGIN [STEP 1](Image with  *JPG format (jpg format))]
   
   ![Repositories](cat0.JPG)
   [ACCORDION-END]
   
   
     [ACCORDION-BEGIN [STEP 2](Image with  *PNG format (png format))]

     ![Repositories](watch.PNG)
     [ACCORDION-END]
   

     [ACCORDION-BEGIN [STEP 3](Image with *jpg format)]

   ![Repositories](Funny-Baby-11.jpg)
   [ACCORDION-END]
   
   
  [ACCORDION-BEGIN [STEP 4](Image with *png format)]

   ![Repositories](monster.png)
   [ACCORDION-END]
   
   
     [ACCORDION-BEGIN [STEP 5](Image with spaces between words (jpg format))]

      ![Repositories](cat 1508613.jpg)
![Image](https://octodex.gi
thub.com/images/yaktocat.png)

**Example:html out of accordion** 

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/xhtml;charset=UTF-8"/>
<title>Related Pages</title>
<link href="qt.css" rel="stylesheet" type="text/css"/>
</head>
<body>
<div class=header>
<a class=headerLink  href="index.html">Main Page</a> &middot;
<a class=headerLink  href="classoverview.html">Class Overview</a> &middot;
<a class=headerLink  href="hierarchy.html">Hierarchy</a> &middot;
<a class=headerLink  href="annotated.html">All Classes</a>
</div>
<!-- Generated by Doxygen 1.8.1.2 -->
</div><!-- top -->
<div class="header">
  <div class="headertitle">
<div class="title">Related Pages</div>  </div>
</div><!--header-->
<div class="contents">
<div class="textblock">Here is a list of all related documentation pages:</div><div class="directory">
<table class="directory">
<tr id="row_0_" class="even"><td class="entry"><img src="ftv2node.png" alt="o" width="16" height="22" /><a class="el" href="classoverview.html" target="_self">Class Overview</a></td><td class="desc"></td></tr>
<tr id="row_1_"><td class="entry"><img src="ftv2lastnode.png" alt="\" width="16" height="22" /><a class="el" href="thelayoutsystem.html" target="_self">The Layout System</a></td><td class="desc"></td></tr>
</table>
</div><!-- directory -->
</div><!-- contents -->
<div class="footer" />Generated with <a href="http://www.doxygen.org/index.html">Doxygen</a> 1.8.1.2</div>
</body>
</html>
```

