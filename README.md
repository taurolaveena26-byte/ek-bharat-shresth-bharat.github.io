<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Avalakki Payasa</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    background:#f4f4f4;
    font-family:Georgia, serif;
    color:#333;
    padding:40px;
}

.container{
    max-width:1000px;
    margin:auto;
    background:white;
    padding:35px;
}

header{
    display:flex;
    justify-content:space-between;
    align-items:flex-start;
    border-bottom:2px solid #999;
    padding-bottom:15px;
    margin-bottom:25px;
}

header h1{
    font-size:48px;
    font-weight:400;
}

header h2{
    font-style:italic;
    font-weight:300;
    color:#555;
    margin-top:5px;
}

.info{
    text-align:right;
    margin-top:20px;
    font-size:18px;
}

.main{
    display:grid;
    grid-template-columns:30% 70%;
    gap:30px;
}

.left{
    padding-right:20px;
    border-right:2px solid #999;
}

.right{
    padding-left:10px;
}

.section-title{
    font-size:34px;
    margin-bottom:20px;
    text-align:center;
    letter-spacing:1px;
}

.ingredients ul{
    list-style:none;
    text-align:center;
    line-height:2;
    font-size:20px;
}

.box{
    border:2px solid #888;
    padding:18px;
    margin-top:30px;
}

.box h3{
    text-align:center;
    font-size:30px;
    margin-bottom:10px;
    font-weight:400;
}

.box p{
    font-size:18px;
    line-height:1.6;
    text-align:center;
}

.directions ol{
    padding-left:30px;
    line-height:1.8;
    font-size:20px;
}

.bottom{
    display:grid;
    grid-template-columns:60% 40%;
    gap:30px;
    margin-top:35px;
}

.image img{
    width:100%;
    border-radius:4px;
}

.nutrition{
    border:2px solid #888;
    padding:20px;
}

.nutrition h3{
    text-align:center;
    font-size:32px;
    margin-bottom:15px;
    font-weight:400;
}

.nutrition p{
    line-height:1.8;
    font-size:18px;
    text-align:center;
}

@media(max-width:900px){

.main,
.bottom{
grid-template-columns:1fr;
}

.left{
border-right:none;
padding-right:0;
}

header{
flex-direction:column;
}

.info{
text-align:left;
margin-top:20px;
}

}
</style>

</head>
<body>

<div class="container">

<header>

<div>
<h1>Avalakki Payasa</h1>
<h2>With poha and milk</h2>
</div>

<div class="info">
🍽️ 3 servings<br><br>
🕒 20 minutes
</div>

</header>

<div class="main">

<div class="left">

<div class="ingredients">
<h2 class="section-title">INGREDIENTS</h2>

<ul>
<li>1 cup poha</li>
<li>1 cup jaggery</li>
<li>1 sliced banana</li>
<li>2 cups thick coconut milk</li>
<li>1 cup thin coconut milk</li>
<li>1 tsp cardamom powder</li>
<li>1 tbsp cashew</li>
<li>1 tbsp raisin</li>
<li>1 tbsp almond</li>
</ul>
</div>

<div class="box">
<h3>NOTES</h3>

<p>
Traditionally, jaggery has been used to achieve the true taste of the dish.
However, if not available, substitute it with <strong>1 cup sugar.</strong>
</p>

</div>

</div>

<div class="right">

<div class="directions">

<h2 class="section-title">DIRECTIONS</h2>

<ol>

<li>
Rinse the poha thoroughly in a strainer under cold running water.
Drain all the water and allow it to rest for 5–10 minutes until soft.
</li>

<li>
Transfer the softened poha into a serving bowl.
Mash lightly using a fork if a smoother consistency is desired.
Add the thin coconut milk and sliced banana and stir.
</li>

<li>
Slowly pour in the jaggery while stirring continuously.
Add the thick coconut milk and cardamom powder until well combined.
</li>

<li>
Garnish with cashews, raisins and almonds before serving.
</li>

</ol>

</div>

</div>

</div>

<div class="bottom">

<div class="image">
<img src="payasa.jpg" alt="Avalakki Payasa">
</div>

<div class="nutrition">

<h3>NUTRITIONAL ANALYSIS</h3>

<p>
This dessert is a moderately energy-dense treat providing approximately
250 calories per 100 g. More than half of its energy comes from fat.
The carbohydrates provide quick energy while dietary fibre helps slow
digestion. With only about 3 g of protein, this dessert offers relatively
low satiety and minimal muscle-building value.
</p>

</div>

</div>

</div>

</body>
</html>
