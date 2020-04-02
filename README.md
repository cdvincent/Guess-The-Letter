<h1>Guess The Letter</h1>

<h4>Link</h4>
<p>https://cdvincent.github.io/Guess-The-Letter/</p>

<h4>Technology used</h4>
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>Javascript</li>
</ul>

<h2>Description</h2>
<p>Guess The Letter is a Javascript-based game in which the user types a letter in order to guess the randomly generated letter within 10 tries. The User Interface will keep track of the amount of Wins, Losses, and amount of guesses reamaining for that round.</p>

<h2>Development</h2>
<p>Guess The Letter uses the HTML getElementById in order to update the win/loss statistics and guesses made displayed on the page. The letter is randomly generated using the Math.random() method on an array of all letters. The guess event is handled by the onkeyup global event handler, and sets off an alert if the entered key code is not an alphabetic letter. Due to using the onkeyup event handler, this application is not playable on mobile devices.</p>