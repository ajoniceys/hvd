<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Valentine's Day Invitation</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;

    }
    h1, p, button {
      margin: 10px;
    }
    button {
      padding: 10px 20px;
      background-color: #ff4081;
      color: #fff;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
  </style>
</head>
<body>

     <img class="valentine-image" src="milk-and-mocha.gif" alt="Valentine's Day Image">
     
  <h1></h1>

  <p>Claudine, can you be my Valentine?</p>
  
  <button id="yesButton" onclick="reply('Yes')">Yes</button>
  <button id="noButton" onclick="reply('No')">No</button>

  <script>
    let yesButtonSize = 20;

    function reply(response) {
      if (response === 'Yes') {
        // Redirect to another page
        window.location.href = "clong.html"; // Replace "nextpage.html" with the URL of your next page
      } else if (response === 'No') {
        alert("Anong NO? Bumalik ka don sa YES.");
        yesButtonSize += 20; // Increase the size of the Yes button by 5px
        document.getElementById('yesButton').style.padding = `10px ${yesButtonSize}px`;
      }
    }
  </script>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valentine's Message</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('https://example.com/background-image.jpg'); /* Add your background image URL here */
            background-size: cover;
            background-repeat: no-repeat;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .valentine-message {
            width: 80%;
            background-color: rgba(255, 255, 255, 0.8); /* Adjust the background color and opacity here */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            font-size: 14px; /* Adjust the font size here */
        }
        .signature {
            font-style: italic;
            margin-top: 20px;
            font-size: 14px; /* Adjust the font size here */
        }
    </style>
</head>
<body>

    <div class="valentine-message">
         <img class="valentine-image" src="milk-and-mocha-milk.gif" alt="Valentine's Day Image">
        <p>My heart is pleased to be your Valentine's date, even though you didn't have a choice because you're my girlfriend! Kidding aside, I'm excited because we get to celebrate together. I love being with you and spending Valentine's Day with you means a lot to me. Let's make it a day full of love and fun memories.</p>
        <p>Para 'to kay Cahlia at Arkielle, inggitin natin sila.</p>
        <p>I love you, even if it's not the 'months of love'.</p>
        <p class="signature">Your hottest girl friend,<br>Jam</p>

        <!-- Add the audio element for background music -->
        <audio autoplay loop>
            <source src="Mitski - My Love Mine All Mine (Official Lyric Video).mp3" type="audio/mp3">
        </audio>
    </div>
</body>
</html>


