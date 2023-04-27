// Velo API Reference: https://www.wix.com/velo/reference/api-overview/introduction

$w.onReady(function () {

const TEXT = "Quantitative Developer.                ML Engineer.                Innovation Enthusiast.                             ";
let typewrittenText = "";

const textArray = Array.from(TEXT);
textArray.forEach((char, index)=>{
	setTimeout(() => {
		if ((index / 2)%2 == 0)
		{
			typewrittenText += char;
		}
		else
		{
			typewrittenText += char + "_";
		}
		$w("#typewriter").text = typewrittenText;
		if ((index / 2)%2 != 0)
		{
			typewrittenText = typewrittenText.substring(0, typewrittenText.length - 1);
		}
	}, 100*index);
})
console.log(textArray)

});

setInterval(function () {

const TEXT = "Quantitative Developer.                ML Engineer.                Innovation Enthusiast.                             ";
let typewrittenText = "";

const textArray = Array.from(TEXT);
textArray.forEach((char, index)=>{
	setTimeout(() => {
		if ((index / 2)%2 == 0)
		{
			typewrittenText += char;
		}
		else
		{
			typewrittenText += char + "_";
		}
		$w("#typewriter").text = typewrittenText;
		if ((index / 2)%2 != 0)
		{
			typewrittenText = typewrittenText.substring(0, typewrittenText.length - 1);
		}
	}, 100*index);
})
console.log(textArray)

}, 12000);
