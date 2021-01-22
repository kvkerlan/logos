# logos
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="ru">
<head>
<meta http-equiv="Content-Type" content="text/html;charset=UTF-8"/>
<title></title>

<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script type="text/javascript" src="js/jQuizler.js"></script>

<link rel="stylesheet" href="css/bootstrap/css/bootstrap.min.css" />
<link rel="stylesheet" href="css/jQuizler.css" />

<script type="text/javascript">
var questions = [
    {
        type: "choose",
        question: "<h3>вопрос1</h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [1]
    },
	{
        type: "choose",
        question: "<h3>вапрос 2</h3>",
        answers: [
           "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [2]
    },
	{
        type: "choose",
        question: "<h3>вапрс 3</h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [1]
    },
	{
        type: "choose",
        question: "<h3>вапрос 4</h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [2]
    },
	{
        type: "choose",

        question: "<h3>вапрос 5 </h3>",

        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [1]
    },
	{
        type: "choose",
        question: "<h3>вапрос 6</h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",

        ],
        correct: [3]
    },
	{
        type: "choose",
        question: "<h3>вапрос7 </h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [2]
    },
	{
        type: "choose",
        question: "<h3>вапрос8 </h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [3]
    },
	{
        type: "choose",
        question: "<h3>вапро9с </h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [2]
    },
	{
        type: "choose",
        question: "<h3>вапрос 10</h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [4]
    },
	{
        type: "choose",
        question: "<h3>вапрос11 </h3>",
        answers: [
           "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [1]
    },
	{
        type: "choose",
        question: "<h3>вапрос12 </h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [4]
    },
	{
        type: "choose",
        question: "<h3>вапрос 13</h3>",
        answers: [
           "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [2]
    },
	{
        type: "choose",
        question: "<h3>вапрс 14</h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [1]
    },
	{
        type: "choose",
        question: "<h3>вапрос 15</h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [2]
    },
	{
        type: "choose",

        question: "<h3>вапрос16</h3>",

        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [1]
    },
	{
        type: "choose",
        question: "<h3>вапрос 17</h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",

        ],
        correct: [3]
    },
	{
        type: "choose",
        question: "<h3>вапрос18</h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [2]
    },
	{
        type: "choose",
        question: "<h3>вапрос19 </h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [3]
    },
	{
        type: "choose",
        question: "<h3>вапроc20 </h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [2]
    },
	{
        type: "choose",
        question: "<h3>вапрос 21</h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [4]
    },
	{
        type: "choose",
        question: "<h3>вапрос21 </h3>",
        answers: [
           "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [1]
    },
	{
        type: "choose",
        question: "<h3>вапрос22 </h3>",
        answers: [
            "вариант1",
            "вариант2",
            "вариант3",
            "вариант4",
        ],
        correct: [4]
    }
	
];

$("document").ready(function(){
    $("#jQuizler").jQuizler(questions);
});

</script>
</head>

<body>
    <div id="jQuizler" class="main-quiz-holder">
        <h3>Тест на тему: "ЖЕНИЛ АВТО УНАА"</h3>
		<p><img src="images/os.png" /></p>
        <button class="btn btn-large">БАШТОО</button>
    </div>
<body>

<div>

<span class="afss_mins_bv">00</span>&nbsp;мин.&nbsp;
<span class="afss_secs_bv">00&nbsp;</span>&nbsp;сек.
</div>
 
<script type="text/javascript">//<![CDATA[
var remain_bv   = 10;
function parseTime_bv(timestamp){
    if (timestamp < 0) timestamp = 0;
 
    var day = Math.floor( (timestamp/60/60) / 24);
    var hour = Math.floor(timestamp/60/60);
    var mins = Math.floor((timestamp - hour*60*60)/60);
    var secs = Math.floor(timestamp - hour*60*60 - mins*60); 
    var left_hour = Math.floor( (timestamp - day*24*60*60) / 60 / 60 );
 
   
    if(String(mins).length > 1)
        $('span.afss_mins_bv').text(mins);
    else
        $('span.afss_mins_bv').text("0" + mins);
    if(String(secs).length > 1)
        $('span.afss_secs_bv').text(secs);
    else
        $('span.afss_secs_bv').text("0" + secs);
     
}
 
$(document).ready(function(){
    setInterval(function(){
        remain_bv = remain_bv - 1;
        parseTime_bv(remain_bv);
        if(remain_bv <= 0){
            alert('Сдин чектелген убактыныз аяктады');
        }
    }, 1000);
});
//]]>

</script>

<body>

</html>
