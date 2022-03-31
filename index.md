<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Feedback Form</title>
  <link href="https://fonts.googleapis.com/css2?family=Cabin:ital,wght@0,400;0,500;0,600;1,400;1,500;1,600&family=Indie+Flower&family=Mali:ital,wght@0,200;0,300;0,400;0,600;1,200;1,300;1,400;1,500;1,600&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;700;900&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>

<body>
    
    <div class="feedback-container">
        <!-- <div class="feedback-main"> -->
            
            <div class="feedback-text">
                <h1>Hello!</h1>
                <p>Did you enjoy learning to code with Agba Akin?</p>
                <p>Let us know. We would love to hear from you.</p>
            </div>
            <div class="feedback-form" id="form">
                <h1>Feedback Form</h1>  
                <form>
                    <div class="input-container name">
                    <label for="fname">
                        Full Name
                    <input type="text" required id="fname" name="fname"/>
                    </label>
                    </div>
                    
                    <div class="input-container email">
                        <label for="email">
                            Email
                        <input type="email" required id="email" name="email"/>
                        </label>
                        </div>

                    <div class="input-container country">
                    <label for="country">
                        Country
                    <input type="text" required id="country" name="country"/>
                    </label>
                    </div>  

                    <div class="input-container selector">
                        <label for="selector">Select learning track</label>
                        <select id="selector">
                            <option>Web Development</option>
                            <option>Cloud Computing</option>
                            <option>Data Analysis</option>
                            <option>Cyber Security</option>
                        </select>

                    </div>
                    
                    
                    
                    <div class="input-container message">
                    <label for="messsage">
                        Leave your message!
                    <textarea id="message"></textarea>      
                    </label>
                    </div>
                    
                    <button id="submit-btn" class="submit-btn" type="button">Submit</button> 
                    <script type="text/javascript">
                        document.getElementById("submit-btn").onclick = function () {
                            location.href = "submit.html"
                        };
                    </script>
                </form>
            </div>
        </div> 
    </div>

</div>
</body>


</html>
