<h2 class="c-project-heading--task">Image styling</h2>

Underneath the CSS for `div`, add another CSS style that will apply to images.

<h2 class="c-project-heading--explainer">Follow these instructions</h2>

## Step 1

Add this code to set the `width`, add a `border` and some `padding` around the image.

<div class="c-project-code">

--- code ---
---
language: css
line_numbers: true
line_number_start: 1
line_highlights: 10-14
---

div {
  text-align: center;
  overflow: hidden;
  border: 4px dotted red;
  border-radius: 40px;
  width: 400px;
  background: yellow;
}

img {
	width: 100px;
	border: 1px solid black;
	padding: 10px;
}

--- /code ---

</div>

## Step 2

Press **Run** to see the image change.

<div class="c-project-output">

![An image of a robot with a black border. There is a gap between the robot image and the border.](images/wanted-img-padding.png)

</div>

## Now run your code

Confirm the observable result.
