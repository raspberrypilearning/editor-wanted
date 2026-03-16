<h2 class="c-project-heading--task">Image styling</h2>

--- task ---

Underneath the CSS for `div`, add another CSS style that will apply to images.

--- /task ---


--- task ---

Add this code to set the `width`, add a `border` and some `padding` around the image.

--- /task ---

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


--- task ---

Press **Run** to see the image change.

--- /task ---

<div class="c-project-output">

![An image of a robot with a black border. There is a gap between the robot image and the border.](images/wanted-img-padding.png)

</div>

