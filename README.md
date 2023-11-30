# Structure-of-Atom

<img width="1141" src="https://media.discordapp.net/attachments/1133396899177709700/1179780249425281065/257155476-b5026aab-6bcc-4ac4-bcb1-450f384609e1.png?ex=657b06fa&is=656891fa&hm=2844c8dc16f8dbb43c618d14ed39a138d34fc66343cf57854e750d36fed598ad&">

		transform: rotate(80deg) !important;
		right: 14vmin !important;
		margin-top: 51vmin !important;
	}

 here is the step-by-step process to create the HTML and CSS for the given atom structure:

Step 1: Set up the basic HTML structure

Create a new file called "index.html" and add the following content:

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Structure of Atom</title>
  <link rel="stylesheet" href="./style.css">
</head>
<body>
  <h1>Carbon</h1>
  <div class="atom">
    <!-- Atom structure will be added here -->
  </div>
  <div class="show-info">i</div>
  <div class="info">
    <div class="inner-shell">     
      <div class="info-particle">
        <h3>INNER SHELL</h3>
        <p><strong>2</strong> ELECTRONS</p>
      </div>
    </div>
    <div class="outer-shell">
      <div class="info-particle">
        <h3>OUTER SHELL</h3>
        <p><strong>4</strong> ELECTRONS</p>
      </div>
    </div>
    <div class="inner-nucleous">
      <div class="info-particle">
        <h3>NUCLEOUS</h3>
        <p><strong>6</strong> PROTONS</p>
        <p><strong>6</strong> NEUTRONS</p>
      </div>
    </div>
  </div>
  <script src='https://cdnjs.cloudflare.com/ajax/libs/matter-js/0.19.0/matter.min.js'></script>
</body>
</html>
Step 2: Save the provided CSS code

Create a new file called "style.css" and paste the provided CSS code into it.

Step 3: Link the CSS file

In the "index.html" file, link the "style.css" file by adding the following line in the head section:

html
Copy code
<link rel="stylesheet" href="./style.css">
Step 4: View the Result

Save both the "index.html" and "style.css" files in the same folder and open the "index.html" file in your web browser. You should now see an atom structure with protons, neutrons, and electrons orbiting around the nucleus. The "i" icon will be visible in the bottom center of the page, and clicking on it will show the particle information. The information will be displayed in an overlay with details about the inner shell, outer shell, and nucleus of the atom.

That's it! You've successfully created the HTML and CSS for the given atom structure.
