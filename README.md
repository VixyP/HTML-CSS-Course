# HTML-CSS-Course



#1. Welcome to HTML

<!DOCTYPE html>
<head>
    <meta charset="UTF-8">
    <title>Welcome</title>
</head>
<body>
    <p>I am learning <strong>HTML</strong> and <strong>CSS</strong>!</p>
</body>
</html>



#2. Fruits

<!DOCTYPE html>
<head>
    <meta charset="UTF-8">
    <title>Fruits</title>
</head>
<body>
    <h1>Fruits</h1>
    <p><img src="banana.png">
        <img src="orange.png">
        <img src="kiwi.png">
        <img src="kiwi.png">
        <img src="apple.png"></p>

    <p><img src="apple.png">
        <img src="apple.png">
        <img src="banana.png">
        <img src="kiwi.png">
        <img src="orange.png"></p>

    <p><img src="orange.png">
        <img src="banana.png">
        <img src="orange.png">
        <img src="orange.png">
        <img src="apple.png"></p>
</body>
</html>



#3. Wiki Page

<!DOCTYPE html>
<head>
    <meta charset="UTF-8">
    <title></title>
</head>
<body>

    <h1>The Brown Bear</h1>
    <p>The brown bear (Ursus arctos) is native to parts of northern Eurasia and North America. Its conservation status is currently "Least Concern." There are many subspecies within the brown bear species, including the Atlas bear and the Himalayan brown bear.</p>
        
    <a href="https://en.wikipedia.org/wiki/Brown_bear">Learn More</a>
        
    <p>Here are some bear species:</p>

    <ul>
        <li>Arctos</li>
        <li>Collarus</li>
        <li>Horribilis</li>
        <li>Nelsoni (extinct)</li>
    </ul>
        
    <p>The following countries have the largest populations of brown bears:</p>

    <ol>
        <li>Russia</li>
        <li>United States</li>
        <li>Canada</li>
    </ol> 

    <img src="bear.jpg">

</body>
</html>



#4. HTML Lists

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Document</title>
    <!--link rel="stylesheet" href="styles.css"-->
</head>
<body>
    <ol type="I">
        <li>List item 1
            <ol type="a">
                <li>Nested item 1.1</li>
                <li>Nested item 1.2</li>
            </ol>
        </li>
        <li>List item 2
            <ol type="1">
                <li>Nested item 2.1</li>
                <li>Nested item 2.2
                    <ul type="circle">
                        <li>Nested item 2.2.1</li>
                        <li>Nested item 2.2.2</li>
                        <li>Nested item 2.2.3</li>
                    </ul>
                </li>
                <li>Nested item 2.3</li>
            </ol>
        </li>
        <li>List item 3
            <ul type="disc">
                <li>Nested item 3.1</li>
                <li>Nested item 3.2</li>
                <li>Nested item 3.3</li>
            </ul>
        </li>
    </ol>
</body>
</html>



#5. To Do List

#to-do-list.html


<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Document</title>
    <link rel="stylesheet" href="to-do-list.css">
</head>
<body>
    <div class="my-list">
        <h1>Today's to do list</h1>
        <p>Monday, September 19th</p>
        <ol>
            <li>Write a blog post</li>
            <li>Go to the bank</li>
            <li>Study for exams</li>
            <li>Renew web hosting account and domain name</li>
            <li>Learn something new</li>
            <li>Update project</li>
        </ol>
    </div>
</body>
</html>


#to-do-list.css

.my-list
{
    background-color: #f7f381;
    padding: 8px 24px;
    width: 500px;
    font-size: 30px;
    border: 1px solid #f7f381;
    box-shadow: 0 0 10px 2px #333333;
    margin: auto;
}

.my-list ol
{
    margin: 12px;
}

.my-list p
{
    text-align: center;
}



#6. Simple HTML Page

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Simple HTML Page</title>
</head>
<body>
    <p>I am learning <strong>HTML</strong> and <strong>CSS</strong>!</p>
</body>
</html>



#7. Tags Cardio - Paragraphs

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Paragraphs</title>
</head>
<body>
    <h1>Top Tips for Effective Presentations</h1>
    <p>This page draws on published <strong>advice</strong> from expert presenters around the world, which will help to take your presentations from merely <strong>good</strong>
    to <strong>great</strong>.</p>
    <p>By bringing together advice from a wide range of people, the aim is to cover a whole range of areas.</p>
    <p>Whether you are an experienced presenter, or just starting out, there should be ideas here to help you to <strong>improve</strong>.</p>
    <p><strong>It's hard to be relaxed and be yourself when you're nervous.</strong></p>
    <p>But time and again, the great presenters say that the most important thing is to connect with your audience, and the best way to do that is to let your passion for the subject shine through.</p>
    <p><em>Be <strong>honest</strong> with the audience about what is important to you and why it matters.</em></p>
    <p><strong>Your presentation needs to be built around what your audience is going to get out of the presentation.</strong></p>
    <p>As you prepare the presentation, you always need to bear in mind what the audience needs and wants to know, not what you can tell them.</p>
    <p><em>While you're giving the presentation, you also need to remain <strong>focused</strong> on your audience's response, and <strong>react</strong> to that.</em></p>
    <p>For more ideas, see our page on Coping with Presentation Nerves.</p>
    <p><strong>Author: <em>Jhon Devis</em></strong></p>
</body>
</html>



