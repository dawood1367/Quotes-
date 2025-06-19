<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8" /><meta name="viewport" content="width=device-width, initial-scale=1"/>
<title>QuoteVerse - BALKHIS FUN</title><style>
body{margin:0;padding:0;font-family:'Segoe UI',sans-serif;background:linear-gradient(to right,#0f2027,#203a43,#2c5364);color:white;display:flex;flex-direction:column;justify-content:center;align-items:center;height:100vh;text-align:center;}
.quote-box{background:rgba(255,255,255,0.1);border-radius:15px;padding:30px;max-width:600px;box-shadow:0 0 20px rgba(0,0,0,0.3);}
#quote{font-size:24px;margin-bottom:20px;}
button{padding:10px 20px;font-size:16px;background:#00ffaa;border:none;border-radius:8px;cursor:pointer;}
.footer{margin-top:30px;font-size:14px;color:#ccc;}
</style></head><body><div class="quote-box"><div id="quote">Click the button to get a quote</div><button onclick="newQuote()">🔁 New Quote</button></div><div class="footer">Made with ❤️ by Dawood | Powered by BALKHIS FUN</div><script>
const quotes=["Success is not final, failure is not fatal. – Winston Churchill","Believe you can and you're halfway there. – Theodore Roosevelt","The only limit to our realization of tomorrow is our doubts of today. – F. D. Roosevelt","Push yourself, because no one else is going to do it for you.","Dream it. Wish it. Do it.","The harder you work for something, the greater you’ll feel when you achieve it.","Don't watch the clock; do what it does. Keep going. – Sam Levenson"];
function newQuote(){document.getElementById("quote").innerText=quotes[Math.floor(Math.random()*quotes.length)];}
</script></body></html># Quotes-
