<!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="utf-8">
      <title> Quiz </title>
      <link rel="stylesheet" type+"text/css" href="main.css">
      <style>
        #quiz{
          display:none;
        }
        body{
          margin-left:50px;
        }
        #question1, #question2, #question3, #question4, #question5, #question6, #question7, #question8{
          display:none;
        }
        canvas{
          display:none;
        }
        .correct{
          background-color:#24399f;
          color:white;
        }
        if(jQuery){
          var checkAnswers = function(){
            var answerString = "";
            var answers = $(":checked");
            answers.each(function(i){
              answerString = answerString + answers[i].value;
            });
            $(":checked").each(function(i) {
              var answerString = answerString + answers[i].value;
            });
            checkIfCorrect(answerString);
          };
          var checkIfCorrect = function(theString){
            if(parseInt(theString, 16) === 811124566973){
              $("body").addClass("correct");
              $("h1").text("You Win!!!");
              $("canvas").show();
            }
          };
          $("#question1").show();
        }
        if(impress){
          $("#question2").show();
        }
        if(atom){
          $("#question3").show();
        }
        if(createjs){
          $("#question4").show();
        }
        if(me){
          $("#question5").show();
        }
        if(require){
          $("#question6").show();
        }
        if($().playground){
          $("#question7").show();
        }
        if(jaws){
          $("#question8").show();
        }
      </style>
    </head>
    <body onclick="checkAnswers();">
      <h1>Quiz</h1>
      <div id="quiz">
        <div id="question1">
          <div class="question">Which is not a main file type that we use to make website?</div>
          <input type="radio" name="queston1" value="a">
          <label>.html</label>
          <input type="radio" name="queston1" value="b">
          <label>.exe</label>
          <input type="radio" name="queston1" value="c">
          <label>.js</label>
          <input type="radio" name="queston1" value="d">
          <label>.css</label>
         </div>
         <br />
         <div id="question2">
          <div class="question">A JavaScript object is wrapped by what characters?</div>
          <input type="radio" name="queston2" value="a">
          <label>[]</label>
          <input type="radio" name="queston2" value="b">
          <label>;;</label>
          <input type="radio" name="queston2" value="c">
          <label>{}</label>
          <input type="radio" name="queston2" value="d">
          <label>()</label>
         </div>
         <br />
         <div id="question3">
          <div class="question">Moles are which of the following?</div>
          <input type="radio" name="queston3" value="a">
          <label>Omniverous</label>
          <input type="radio" name="queston3" value="b">
          <label>Adorable</label>
          <input type="radio" name="queston3" value="c">
          <label>Whackable</label>
          <input type="radio" name="queston3" value="d">
          <label>All of the above</label>
         </div>
         <br />
         <div id="question4">
          <div class="question">The gravitational constant on the Earth is approximately?</div>
          <input type="radio" name="queston4" value="a">
          <label>10m/s^2</label>
          <input type="radio" name="queston4" value="b">
          <label>.809m/s^2</label>
          <input type="radio" name="queston4" value="c">
          <label>9.81m/s^2</label>
          <input type="radio" name="queston4" value="d">
          <label>84.4m/s^2</label>
         </div>
         <br />
         <div id="question5">
          <div class="question">45 (in base 10) is what in binary (base 2)?</div>
          <input type="radio" name="queston5" value="a">
          <label>101101</label>
          <input type="radio" name="queston5" value="b">
          <label>110011</label>
          <input type="radio" name="queston5" value="c">
          <label>011101</label>
          <input type="radio" name="queston5" value="d">
          <label>101011</label>
         </div>
         <br />
         <div id="question6">
          <div class="question">4 << 2 = ...</div>
          <input type="radio" name="queston6" value="a">
          <label>16</label>
          <input type="radio" name="queston6" value="b">
          <label>4</label>
          <input type="radio" name="queston6" value="c">
          <label>2</label>
          <input type="radio" name="queston6" value="d">
          <label>8</label>
         </div>
         <br />
         <div id="question7">
          <div class="question">Given the lengths of two sides of s right triangle (one with a 90 degree angle), how  would you find the hypotenuse</div>
          <input type="radio" name="queston7" value="a">
          <label>Pi*Radius^2</label>
          <input type="radio" name="queston7" value="b">
          <label>Pythagorean Theorm</label>
          <input type="radio" name="queston7" value="c">
          <label>Calculator</label>
          <input type="radio" name="queston7" value="d">
          <label>Sin(side1 + sides2)</label>
         </div>
         <br />
         <div id="question8">
          <div class="question">Using a server can help you to...</div>
          <input type="radio" name="queston8" value="a">
          <label>hide your code.</label>
          <input type="radio" name="queston8" value="b">
          <label>have a performant game.</label>
          <input type="radio" name="queston8" value="c">
          <label>create shared experinces for players.</label>
          <input type="radio" name="queston8" value="d">
          <label>all of the above.</label>
        </div>
      </div>
      <script src="jquery.js"></script>
      <script src="impress.js"></script>
      <!-- atom needs this to run -->
      <canvas></canvas>
      <script src="atom.js"></script>
      <script src="easel.js"></script>
      <script src="melon.js"></script>
      <script src="yabble.js"></script>
      <script src="jquery.gamequery.js"></script>
      <script src="jaws.js"></script>
      <script src="game.js"></script>
    </body>
    </html>   
