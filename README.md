<!DOCTYPE HTML> <html lang="en"> 
<head> <meta charset=utf-8> 
<title>Create a speech bubble shape with CSS3</title> 
<style type="text/css"> #speech-bubble { width: 120px; height: 80px; background: #5ac4ed; position: absolute; left:100px; -moz-border-radius: 10px; -webkit-border-radius: 10px; border-radius: 10px; } #speech-bubble:before { content:""; position: absolute; width: 0; height: 0; border-top: 13px solid transparent; border-right: 26px solid #5ac4ed; border-bottom: 13px solid transparent; margin: 13px 0 0 -25px; } </style> </head> <body> <div id="speech-bubble"></div> </body> </html> 
