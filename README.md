# SABERKAS 
Pertubuhan Belia Kebangsaan Bersatu Sarawak
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Button Menu Dropdown</title>
    <style>
        /* Gaya untuk button menu */
        .dropdown {
            position: relative;
            display: inline-block;
        }

        /* Gaya untuk dropdown menu */
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            min-width: 160px;
            box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
            z-index: 1;
            border-radius: 5px;
        }

        /* Gaya untuk butang menu */
        .dropdown button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        /* Gaya untuk item dalam menu dropdown */
        .dropdown-content a {
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }

        /* Gaya apabila hover pada item menu */
        .dropdown-content a:hover {
            background-color: #ddd;
        }

        /* Show the dropdown menu when hovering */
        .dropdown:hover .dropdown-content {
            display: block;
        }
    </style>
</head>
<body>

<div class="dropdown">
  <button class="dropbtn">Menu</button>
  <div class="dropdown-content">
    <a href="#section1">Menu 1</a>
    <a href="#section2">Menu 2</a>
    <a href="#section3">Menu 3</a>
  </div>
</div>

</body>
</html>
