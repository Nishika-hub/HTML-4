# HTML-4
<!DOCTYPE html>
<html>
<head>
    <title>Tech Innovate Blog</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace; 
            background-color: #f0f0f0;
            margin: 0;
        }

        header {
            background-color: #2c003e; 
            color: #00ff00; 
            padding: 20px;
            border-bottom: 5px solid #00ff00;
            text-align: center;
        }

        nav a {
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            font-size: 20px;
        }

        section {
            background-color: white;
            width: 80%;
            margin: 20px auto;
            padding: 20px;
            border: 2px solid #2c003e;
        }

        h2 {
            background-color: #00ff00; 
            color: #2c003e;
            display: inline-block;
            padding: 5px 10px;
        }

        
        ul.categories li {
            background-color: #eee;
            margin: 5px 0;
            padding: 5px;
            list-style-type: square;
        }

        
        .tag {
            background-color: #2c003e;
            color: white;
            padding: 5px 10px;
            margin-right: 5px;
            font-size: 12px;
        }

        input, textarea {
            width: 90%;
            padding: 10px;
            border: 2px solid #2c003e;
            margin-bottom: 10px;
        }

        input[type="submit"] {
            background-color: #2c003e;
            color: #00ff00;
            font-weight: bold;
            cursor: pointer;
            width: auto;
        }
    </style>
</head>
<body>

    <header>
        <h1>Tech Innovate</h1>
        <nav>
            <a href="#article">Article</a> | 
            <a href="#categories">Categories</a> | 
            <a href="#comments">Discussion</a>
        </nav>
    </header>

    <br>

    <section id="article">
        <h2>The Future of AI</h2>
        <p>Artificial Intelligence is changing the world rapidly. From coding to painting, AI is everywhere.</p>
        
        <img src="https://i.pinimg.com/736x/a3/dd/21/a3dd212965b4d0a0d9abc1004b524c69.jpg" width="1100" height="300" alt="Tech Image">
        
        <p>In this blog, we explore how AI will impact education in the next 10 years.</p>
        
        <br>
        <strong>Tags: </strong>
        <span class="tag">Technology</span>
        <span class="tag">Education</span>
        <span class="tag">Future</span>
    </section>

    <section id="categories">
        <h2>Categories</h2>
        <ul class="categories">
            <li>Software Development</li>
            <li>Cyber Security</li>
            <li>Data Science</li>
            <li>Cloud Computing</li>
        </ul>
    </section>

    <section id="comments">
        <h2>Leave a Comment</h2>
        <form>
            <label for="username">Name:</label><br>
            <input type="text" id="username" name="username" placeholder="Enter name"><br>

            <label for="usercomment">Comment:</label><br>
            <textarea id="usercomment" name="usercomment" rows="4" placeholder="Write your thoughts here..."></textarea><br>

            <input type="submit" value="Post Comment">
        </form>

        <hr>
        
        <h3>Recent Comments:</h3>
        <p><strong>Rahul K:</strong> This is a very informative article!</p>
        <br>
        <p><strong>Anita S:</strong> I agree, AI is the future.</p>
    </section>

</body>
</html>
