# Number-system-calculators-


<!DOCTYPE html>
<html lang="en">

<head>

<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.fa {
  padding:5px;
  font-size: 30px;
  width: 30px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
  border-radius: 50%;
}

.fa:hover {
    opacity: 0.7;
}

.fa-facebook {
  background: #3B5998;
  color: white;
}

.fa-twitter {
  background: #55ACEE;
  color: white;
}

.fa-google {
  background: #dd4b39;
  color: white;
}

.fa-linkedin {
  background: #007bb5;
  color: white;
}

.fa-youtube {
  background: #bb0000;
  color: white;
}

.fa-instagram {
  background: #125688;
  color: white;
}

.fa-pinterest {
  background: #cb2027;
  color: white;
}

.fa-snapchat-ghost {
  background: #fffc00;
  color: white;
  text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
}

.fa-skype {
  background: #00aff0;
  color: white;
}

.fa-android {
  background: #a4c639;
  color: white;
}

.fa-dribbble {
  background: #ea4c89;
  color: white;
}

.fa-vimeo {
  background: #45bbff;
  color: white;
}

.fa-tumblr {
  background: #2c4762;
  color: white;
}

.fa-vine {
  background: #00b489;
  color: white;
}

.fa-foursquare {
  background: #45bbff;
  color: white;
}

.fa-stumbleupon {
  background: #eb4924;
  color: white;
}

.fa-flickr {
  background: #f40083;
  color: white;
}

.fa-yahoo {
  background: #430297;
  color: white;
}

.fa-soundcloud {
  background: #ff5500;
  color: white;
}

.fa-reddit {
  background: #ff5700;
  color: white;
}

.fa-rss {
  background: #ff6600;
  color: white;
}
</style>


    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Primary Meta Tags -->
    <meta name="title" content="Number System Converter">
    <meta name="description"
        content="Convert any number system to other, like Decimal, Binary, Octal, Hexadecimal easily. Made with ♥ by alnahian2003">


    <title>Number System Converter</title>

    <style>
        body {
            background-image: url("https://codeactsineducation.files.wordpress.com/2017/06/christiaan-colen.jpg?w=640");

            background-position:bottom;
            background-repeat: no-repeat;
            background-size: cover;
            background-color: #ffffff;
            box-sizing: border-box;
            color: #ffffff ;
            font-family: Arial, Helvetica, sans-serif;
            height: auto;
            margin: 0;
            text-align: center;
            width: auto;
        }

        #container {
            display: flex;
            margin: 50px auto;
            text-align: center;
            flex-flow: column;
            justify-content: center;
        }

        h1 {
            font-size: 3rem;
        }

        label {
            font-size: 1.5rem;
            font-weight: bold;
        }

        input {
            background-color: transparent;
            border-radius: 5px;
            border: 3px solid #ffffff;
            color: #ffffff;
            display: block;
            font-size: 30px;
            font-weight: bold;
            height: 50px;
            margin: 10px auto;
            outline: 1px solid transparent;
            text-align: center;
            text-transform: uppercase;
            transition: .3s ease;
            width: 40%;
        }

        input:focus {
            border: 3px solid #ffffff;
            width: 50%;
        }

        ::placeholder {
            color: #ffffff80;
            font-weight: normal;
        }

        footer {
            padding: 10px;
        }

        @media (max-width: 767px) {
            body {
                height: 100%;
            }

            h1 {
                font-size: 2rem;
            }

            input {
                width: 80%;
            }

            input:focus {
                width: 90%;
            }
        }
        #placeholder{
            background: #000;
            height: 100vh;
            width: 100%;
            position: fixed;
            z-index: 100;
        }
    </style>
</head>

<body>
    <div id="preloader"></div>
   
    <div id="container">
        <h1>👉කැල්culator👈 </h1>
        <label for="input1">දශමය:</label>
        <input type="number" name="" id="input1" placeholder="දශමය අගය">

        <label for="input2">ද්වීමය:</label>
        <input type="number" name="" id="input2" placeholder="ද්වීමය අගය">

        <label for="input3">අෂ්ඨමය:</label>
        <input type="number" name="" id="input3" placeholder="අෂ්ඨමය අගය">

        <label for="input4">ෂඩ්දශමය:</label>
        <input type="" name="" id="input4" placeholder="ෂඩ්දශමය අගය">
    </div>
        <a href="https://www.youtube.com/channel/UCBnbCfFIGfMM8qo28ethQ_g" class="fa fa-youtube"></a>
        <a href="https://api.whatsapp.com/send/?phone=0759307059&text=I%27m+interested+in+your+car+for+sale&app_absent=0" class="fa fa-whatsapp"></a>
        <a href="https://www.linkedin.com/in/mr-ranuka-jayesh-474b29217/detail/recent-activity/shares/" class="fa fa-linkedin"></a>
        
    <footer>Made with Ranu ♥ by <a href="https://alnahian2003.github.io/me" target="_blank"></a> RJ COLLECTIONS 2021</footer>

    <script>
        // Global Variables
        let input1 = document.getElementById("input1"),
            input2 = document.getElementById("input2"),
            input3 = document.getElementById("input3"),
            input4 = document.getElementById("input4");

        // Start Converting on Key Up in the decimal input fields

        // Global Functions 

        // Decimal to All Number System
        function deciToAll() {
            // Local Variables for the value of input fields
            let valInput1 = parseInt(input1.value, 10),
                valInput2 = parseInt(input2.value, 2),
                valInput3 = parseInt(input3.value, 8),
                valInput4 = parseInt(input4.value, 16);

            // Generate result
            input2.value = valInput1.toString(2).toUpperCase();
            input3.value = valInput1.toString(8).toUpperCase();
            input4.value = valInput1.toString(16).toUpperCase();
        }

        function octToAll() {
            // Local Variables for the value of input fields
            let valInput1 = parseInt(input1.value, 10),
                valInput2 = parseInt(input2.value, 2),
                valInput3 = parseInt(input3.value, 8),
                valInput4 = parseInt(input4.value, 16);

            // Generate result
            input1.value = valInput3.toString(10).toUpperCase();
            input2.value = valInput3.toString(2).toUpperCase();
            input4.value = valInput3.toString(16).toUpperCase();
        }

        function hexaToAll() {
            // Local Variables for the value of input fields
            let valInput1 = parseInt(input1.value, 10),
                valInput2 = parseInt(input2.value, 2),
                valInput3 = parseInt(input3.value, 8),
                valInput4 = parseInt(input4.value, 16);

            // Generate result
            input1.value = valInput4.toString(10).toUpperCase();
            input2.value = valInput4.toString(2).toUpperCase();
            input3.value = valInput4.toString(8).toUpperCase();
        }
        // End of Global Functions

        // Made changes on key up
        input1.addEventListener("keyup", function () {
            deciToAll();
        });
        // Made changes on any value change
        input1.addEventListener("change", function () {
            deciToAll();
        });

        // Start Converting on Key Up in the binary input fields
        input2.addEventListener("keyup", function () {
            // Local Variables for the value of input fields
            let valInput1 = parseInt(input1.value, 10),
                valInput2 = parseInt(input2.value, 2),
                valInput3 = parseInt(input3.value, 8),
                valInput4 = parseInt(input4.value, 16);

            // Generate result
            input1.value = valInput2.toString(10).toUpperCase();
            input3.value = valInput2.toString(8).toUpperCase();
            input4.value = valInput2.toString(16).toUpperCase();
        });

        // Start Converting on Key Up in the octal input fields

        // Made changes on key up
        input3.addEventListener("keyup", function () {
            octToAll()
        });

        // Made changes on any value change
        input3.addEventListener("change", function () {
            octToAll()
        });

        // Start Converting on Key Up in the hexadecimal input fields

        // Made changes on key up
        input4.addEventListener("keyup", function () {
            hexaToAll();
        });

        // Made changes on any value change
        input4.addEventListener("change", function () {
            hexaToAll();
        });
    </script>
    
</body>

</html>
