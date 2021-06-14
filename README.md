<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    table{
        font-family: 'Courier New', Courier, monospace;
        border-collapse: collapse;
        width: 25%;
    }
    td, th {
        border: 1px solid ;
        text-align: left;
        padding: 8px;
    }

</style>

<body>
        <h1>Alexis Valencia</h1>
    <img src="http://lorempixel.com/100/100/people" alt="an image" height="250"width="250">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc tincidunt augue sit amet quam mollis,
        quis ultrices sem tempus. Quisque luctus eleifend lorem eget cursus. Suspendisse a tortor ex.
        Aenean facilisis neque nec neque viverra, in rutrum erat tempor. Integer dignissim dui non dapibus 
        iaculis. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. 
        Nulla aliquet lacus vel est aliquet posuere. Donec feugiat nisl quis nisi volutpat aliquet. 
        Donec rhoncus elit in nulla molestie sodales. Curabitur interdum vel justo at vestibulum.
        Maecenas purus nunc, sodales vel lobortis in, vehicula sed turpis.</p>
    <table>
        <tr>
            <th>Rank</th>
            <th>Name</th>
            <th>Wins</th>
            <th>Active years</th>
        </tr>
        <tr>
            <td>#1</td>
            <td>Marcus Almeida</td>
            <td>13</td>
            <td>2011-present</td>
        </tr>
        <tr>
            <td>#2</td>
            <td>Roger Gracie</td>
            <td>10</td>
            <td>2006-present</td>
        </tr> 
        <tr>
            <td>#3</td>
            <td>Bernardo Faria</td>
            <td>4</td>
            <td>2003-2017</td>
        </tr> 
        <tr>
            <td>#4</td>
            <td>Marcio Cruz</td>
            <td>3</td>
            <td>2005-present</td>
        </tr>
        <tr>
            <td>#5</td>
            <td>Rafael Lovato Jr.</td>
            <td>1</td>
            <td>2003-2007</td>
        </tr>
    </table>
    <ul>
        <li>Marcus Almeida winning years 2012-2014, 2016-2019</li>
        <li>Roger Gracie winning years 2004-2010</li>
        <li>Bernardo Farias winning years 2010, 2013, 2015</li>
    </ul>
    <p><a href="https://www.youtube.com/watch?v=_L-Ni7bFAHg">Roger Gracie vs Marcus Almeida</a></p>
    <h2>Please fill out this form below</h2>
    <form action="/action_page.php">
        <label for="fname">Email : </label>
        <input type="text" id="fname" value=""><br><br>
    </form>
    <form action="/action_page.php">
        <input type="radio" >
        <label for="">Yes, Send me more emails about BJJ</label>
        <input type="radio" >
        <label for="">No, I'm not cool </label>
    </form>
        <h6>Select a t-shirt size for a chance to win out latest one</h6>
        <select>
            <option vaslue="xs">X-Small</option>
            <option value="S">Small</option>
            <option value="M">Medium</option>
            <option value="L">Large</option>
            <option value="XL">X-Large</option>
    </select>
<h3>How did you find me?</h3>
<form action="/action_page.php">
    <input type="checkbox" >
    <label>Instagram</label><br>
    <input type="checkbox" >
    <label>Snapchat</label><br>
    <input type="checkbox" >
    <label>Facebook</label><br><br>
</form>
<input type="submit">
</body>
