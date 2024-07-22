<!DOCTYPE html>
<!-- saved from url=(0029)https://50sh.github.io/index/ -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>Ahmed Adel TEAM</title>
	<style>
		body {
			background-color: #000000; /* black background */
            margin: 0;
      padding: 0;
      width: 100%;
      height: 100vh;
      overflow: hidden;
		}
     
   
    
    video {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100vh;
      object-fit: cover;
    }
 
	</style>
</head>
<body>
    <p align="center">
        <img border="0" src="https://cdn.discordapp.com/attachments/1208949632915476521/1250153922514124810/51281-D8B5D988D8B1-D8AFD8A7D8B9D8B4-D98AD8B9D8AFD985-D8A3D8B3D98AD8B1-D8B3D988D8B1D989-2.png?ex=6669e811&is=66689691&hm=ce1ae6436277d2f0ce481972e52b9eb78a77b859f3cd957e0ee5db17c6c27691&" width="device-width" height="200">
    </p>
   

   
    

 
<script>
    var names = [



    var nameIndex = 0;

    function changeNames() {
        var currentName = names[nameIndex];
        document.getElementById("name").textContent = currentName.name;
        document.getElementById("name").style.color = currentName.color;
        nameIndex = (nameIndex + 1) % names.length;
    }

    // Change the names every 1 second
    setInterval(changeNames, 1000);
</script>

<p align="center">
    

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Change Name Every Second with Custom Color</title>
<style>
 
BODY {
    font-family: Arial, sans-serif;
    text-align: center;
    padding-top: 50px;
  }
</style>
</head>
<body>


<h1 id="nameDisplay">CALLME</h1>

<script>
 
  const namesAndColors = [
    { name: "Hacked by [EXE.CALLME]", color: "BLACK" },
    { name: "Hacked by [exe.6.eldokSH]", color: "RED" },
   
  ];
  
  let index = 0;

  // Function to change the name every second
  function changeName() {
    document.getElementById("nameDisplay").textContent = namesAndColors[index].name;
    document.getElementById("nameDisplay").style.color = namesAndColors[index].color;
    index = (index + 1) % namesAndColors.length; // Move to the next name, wrap around if needed
  }

  
  changeName();
  setInterval(changeName, 1000); // Change name every 1 second (1000 milliseconds)
</script>
</p>
</body>
</html>


</font>

    </b>
</p>





    <title>?، </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            color: #000000;
            background-color: #000000;
            overflow: hidden;
        }

        h1, h3 {
            color: #ffffff;
        }

        #ip-address {
            color: rgb(255, 255, 255);
        }

        #ip-info {
            font-family: Arial, sans-serif;
            white-space: pre;
            color: rgb(255, 255, 255);
        }

        .cmd-text-container {
            position: relative;
        }

        .cmd-text {
            color: #000000;
            font-size: 9px;
            font-family: Arial, sans-serif;
            white-space: nowrap;
            position: static;
            animation: scrollText 20s linear infinite;
            transform: translateX(100%);
            -webkit-text-stroke: 1px rgb(255, 255, 255);
            text-stroke: 1px rgb(255, 255, 255);
        }

        .gray-text {
            color: #000000;
            outline: 1px solid #000000;
        }

        .json-data {
            font-family: Arial, sans-serif;
            color: rgb(255, 255, 255);
            text-shadow: -1px -1px 0 black, 1px -1px 0 black, -1px 1px 0 black, 1px 1px 0 black;
        }

        .json-data span {
            color: black;
        }

        @keyframes scrollText {
            0% {
                transform: translateX(100%);
            }
            100% {
                transform: translateX(-100%);
            }
        }

        .cmd-text:hover {
            animation-play-state: paused;
        }

        video {
            position: fixed;
            top: 0;
            left: 0;
            z-index: -1;
            filter: blur(10px);
        }

        /* Hide the audio controls */
        audio {
            display: none;
        }
    </style>


    


    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animated Text</title>
    <style>
        @keyframes lightning {
            0% { color: rgb(255, 0, 0); }
            50% { color: rgb(0, 0, 0); }
            100% { color: white; }
        }

        .animated-text {
            animation: lightning 1s linear infinite;
        }
    </style>


    <h3 class="animated-text">جاهزين تتناكو ؟</h3>


    <p id="ip-address">
        <span style="color: rgb(255, 255, 255);">Your IP Address: </span>
        <span id="ip-address-value" style="color: rgb(255, 255, 255); font-size: 17px;">Unable to fetch IP address.</span>
    </p>

    <h3 style="color: rgb(255, 255, 255); animation: flashing 1s infinite;">Your IP Info :</h3>
    <pre id="ip-info" class="json-data">Unable to fetch IP information.</pre>
    <div class="cmd-text-container" style="position: relative; top: -15px;">
        <div class="cmd-text" style="font-size: 19px; text-stroke: 20px black; color: black;">  تـــــــم النيـــــــك </div>
    </div>

    <!-- Hidden audio element with autoplay -->
   

<video style="width: 100vw; height: 100vh;" controls="" autoplay="" loop="">
    <source src="1307d006ce0455e7.mp4">




    <script>
        // JavaScript code to fetch and display the user's IP address and information
        function fetchIPAndInfo() {
            fetch('https://api.ipify.org/?format=json')
                .then(response => response.json())
                .then(data => {
                    document.getElementById('ip-address-value').textContent = data.ip;
                    return data.ip;
                })
                .then(ip => fetch(`https://ipinfo.io/${ip}/json`))
                .then(response => response.json())
                .then(ipInfoData => {
                    document.getElementById('ip-info').textContent = JSON.stringify(ipInfoData, null, 2);
                })
                .catch(error => {
                    console.error('Error:', error);
                    document.getElementById('ip-address-value').textContent = 'Unable to fetch IP address.';
                    document.getElementById('ip-info').textContent = 'Unable to fetch IP information.';
                });
        }

        // Fetch IP address and information initially
        fetchIPAndInfo();
    </script>


</video>




	


</body></html>
