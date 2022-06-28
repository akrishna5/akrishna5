<!------------------------------------------------------------------------------CSS----------------------------------------------------------------------------------->

$main_font: 'Roboto';
$main_color: #ff6600;

ul {
	font-family: $main_font;
	font-size: 13px;
	line-height: 1.5em;
	margin: 5px 0 15px;
	padding: 0;
	li {
		list-style: none;
		position: relative;
		padding: 0 0 0 20px;
	}
}

ul.arrow {
	li {
		&::before {
			content: "";
			position: absolute;
			left: 0;
			top: 6px;
			height: 5px;
			width: 5px;
			border: 1px solid $main_color;
			border-width: 2px 2px 0 0;
			transform: rotate(45deg);
		}
	}
}

<!------------------------------------------------------------------------------HTML------------------------------------------------------------------------------------>

<h3></h3>
<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Bradley+Hand+ITC&size=35&duration=3000&color=006400&background=FFA21E00&multiline=true&width=500&height=100&lines=Welcome+To+My+Profile...;I+am+Abhishek+Krishna+!!"></a></h1>
I'm a third year undergraduate currently pursuing Bachelors in CSE, from VIT, Vellore.
<br>
Here is my <ul class="arrow">
	<li><code><a href="https://www.instagram.com/akrishna5/" title="Instagram Profile"><img width="22" src="images/instagram.svg"> Instagram</a></code></li>
	<li><code><a href="www.linkedin.com/in/akrishna05/" title="LinkedIn Profile"><img width="22" src="images/linkedin.svg"> LinkedIn</a></code></li>
</ul>
