# BirthdayCard
```
Reg No : 212221240015
Name : Harshavardhini M
```
## Aim:
To create a Birthday Card using HTML and CSS

## Program:
```
<!DOCTYPE html>
<html>
<head>
	<title>Happy Birthday!</title>
	<style>
		body {
		    background-image: url("bdaybg.jpg");
            background-repeat: no-repeat ;
			color: #fff;
            height: 100px;
			font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
			text-align: center;
			padding: 50px;
			line-height: 1.5;
            background-size: cover;
		}

		h1 {
			font-size: 72px;
            font-family: cur;
			color: #2fbfc9;
			margin-bottom: 50px;
			text-transform: uppercase;
			letter-spacing: 5px;
			font-weight: 600;
			text-shadow: 1px 2px 2px #ffffff;
		}

		h2 {
			font-size: 36px;
			color: #fff;
			margin-bottom: 20px;
			font-weight: 600;
			text-shadow: 2px 2px 2px #000;
		}

		p {
        
			font-size: 24px;
            outline: #000;
			color: #fff;
			margin-bottom: 30px;
			text-align: justify;
			padding: 0 50px;
            text-shadow: 1.4px 1.4px 1.4px #000;
		}

		.container {
			max-width: 800px;
			margin: 0 auto;
		}

		.card {
			background-color: #5be4ff2e;
			box-shadow: 0px 10px 20px rgba(0,0,0,0.3);
			padding: 50px;
			border-radius: 20px;
			margin-bottom: 50px;
			position: relative;
			overflow: hidden;
		}

		.card:before {
			content: "";
			position: absolute;
			top: 0;
			left: 0;
			width: 100%;
			height: 100%;
			background-image: linear-gradient(to bottom right, #ffc0cb, #ff6666);
			opacity: 0.1;
			z-index: -1;
		}

		.card img {
			max-width: 100%;
			height: auto;
			margin-bottom: 30px;
			filter: drop-shadow(2px 2px 4px rgba(0,0,0,0.3));
		}

		.btn {
			display: inline-block;
			background-color: #2fbfc9;
			color: #fff;
			padding: 10px 20px;
			border-radius: 5px;
			margin-top: 30px;
			text-decoration: none;
			transition: all 0.3s ease-in-out;
			box-shadow: 2px 2px 4px rgba(0,0,0,0.2);
			font-weight: 600;
			text-shadow: 2px 2px 2px #59d5f5;
		}

		.btn:hover {
			transform: translateY(-5px);
			box-shadow: 4px 4px 8px rgba(100, 233, 251, 0.408);
		}
	</style>
</head>
<body>
	<div class="container">
		<div class="card">
			<h1>Happy Birthday!</h1>
			<!-- <img src="https://i.imgur.com/h37KgEj.png" alt="Birthday cake"> -->
			<h2>Congratulations on another year of success!</h2>
			<p>Wishing you an amazing day filled with happiness, laughter, and love. May your year be filled with exciting new opportunities and technological advancements!</p>
			<a href="https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwjY0vrvsp3-AhWKNSsKHUHiBdkYABABGgJzZg&ohost=www.google.com&cid=CAESaOD2QG6r816UkzVzECsAaYilF_xt8TZeXjpQlxMZLFFdzrL0IXWpTgpqSVVRHKD39JsakSUfYYJhacMJQnXDJ-FviLW7vSd3HHSW0amNF_JDXw12BbnQmsMPhyKzPKUWo8ebm0kKVoFX&sig=AOD64_3NOTA8H3guYvdfXdxRMrfhTds5mg&q&adurl&ved=2ahUKEwjKyPPvsp3-AhURTGwGHWp9ACsQ0Qx6BAgJEAE" class="btn">Surprise</a>

```
## Output:

![Screenshot (38)](https://user-images.githubusercontent.com/93427208/230790451-94ae5d92-84a3-4db9-8e3e-0afb6e929852.png)


