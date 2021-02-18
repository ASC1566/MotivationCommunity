# Welcome to Motivation Community webpage!

What does this community do? How can we help you to motivate your during this pandamic ?

### A bit of information

Welcome to our unique server Motivation community ! The creator Christine created this server to help students all across the globe.  Our aim is to help you to get motivated and meet new, nice friends ! These are some basic information about our server!

### We provide: 
- Live study sessions
- Private study sessions
- We can provide you with some practice sheets, ensure if you really completed those.
- Different competitions like Monthly study Challenge!

### Discord Community: 
https://discord.gg/ST5cbBw

### have a peak on inside:

request.open('GET', 'https://discord.com/api/guilds/729915854900428871/widget.json', true);

request.onload = function() {
    if (request) {
        var data = JSON.parse(request.responseText);
        document.getElementById("discord-counter").innerHTML = data.presence_count;
    } else {
    }
};

request.onerror = function() {
};

request.send();
