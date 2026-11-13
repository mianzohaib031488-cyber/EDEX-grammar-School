<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edex Grammar School</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #f0f2f5;
            color: #333;
        }
        /* Header & Menu Button */
        header {
            background-color: #1a252f;
            color: white;
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        .header-title h1 {
            font-size: 22px;
            letter-spacing: 0.5px;
        }
        .header-title p {
            font-size: 14px;
            color: #1abc9c;
            font-weight: bold;
            margin-top: 3px;
        }
        .menu-btn {
            background: none;
            border: none;
            color: white;
            font-size: 28px;
            cursor: pointer;
            padding: 5px 10px;
        }
        /* Dropdown Navigation Menu */
        .nav-dropdown {
            display: none;
            flex-direction: column;
            background-color: #2c3e50;
            position: absolute;
            top: 70px;
            right: 20px;
            width: 200px;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.3);
            overflow: hidden;
            z-index: 1001;
        }
        .nav-dropdown.show {
            display: flex;
        }
        .nav-dropdown a {
            color: white;
            padding: 14px 18px;
            text-decoration: none;
            border-bottom: 1px solid #34495e;
            font-size: 16px;
            cursor: pointer;
        }
        .nav-dropdown a:hover {
            background-color: #1abc9c;
        }
        /* Sections */
        .container {
            max-width: 800px;
            margin: 25px auto;
            padding: 0 15px;
        }
        .section {
            display: none;
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,
            
