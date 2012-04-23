# CSS3 Progress Bars
I made CSS3 progress bars for a display of data inside localized leaderboards for the new platform at G5.

They are light-weight, requiring no javascript. They work on iOS devices, they're incredibly simple to customize, and using them on your site is as easy as linking to the css file and pasting in the markup. No images are used.

## Instructions
1. Include the progress bar stylesheet:

	  <link rel="stylesheet" href="css3-progress-bar.css" />

2. If you need to fully support versions of Internet Explorer prior to 9, include the IE supplemental styles after the above line. Keep in mind that the progress bars will still render well in IE6/7/8 without these styles. These styles use proprietary IE style techniques that are known to not be performant. To keep your site rendering quickly and responding well, consider not including this line and gracefully degrading in older browsers.

    <!--[if lt IE 9]>
      <link rel="stylesheet" href="css3-progress-bar-ie.css" />
    <![endif]-->

3. Paste the following syntax where you want a progress bar. The progress far will fill the width of its containing block element.

		<div class="bar_container">
			<div class="bar_mortice">
				<div class="progress" style="width: 40%;"></div>
			</div>
		</div>

4. Change the progress bar's fill level with a percentage:

		<div class="progress" style="width: 52%;"></div>

See example.html for more styles and colors.
