# CSS3 Progress Bars
I made CSS3 progress bars for a display of data inside localized leaderboards for the new platform at G5.

They are light-weight, requiring no javascript. They work on iOS devices, they're incredibly simple to customize, and using them on your site is as easy as linking to the css file and pasting in the markup. No images are used.

## Instructions
1. Include the progress bar stylesheet:

	    <link rel="stylesheet" href="css3-progress-bar.css">

2. Paste the following syntax where you want a progress bar. The progress far will fill the width of its containing block element.

		<div class="bar_container">
			<div class="bar_mortice">
				<progress style="width: 40%;"></progress>
			</div>
		</div>

3. Change the progress bar's fill level with a percentage:

		<progress style="width: 52%;"></progress>

See example.html for more styles and colors.
