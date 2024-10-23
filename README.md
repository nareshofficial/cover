# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
~~~
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Book Cover Page</title>
        <style>
            body {
                margin: 0;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                background-color: #f0f0f0;
            }

            .bookpage {
                width: 400px;
                height: 600px;
                margin: 20px auto;
                padding: 20px;
                color: #333; /* Dark text color for better readability on light background */
                background-color: #f9f9f9; /* Light background color */
                background-image: url('bookcover.png');
                background-size: cover;
                background-position: center;
                display: flex;
                flex-direction: column;
                justify-content: space-between;
                border: 1px solid #ccc;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            }

            .header, .footer {
                text-align: center;
            }

            .booktitle {
                font-family: 'Courier New', Courier, monospace;
                font-size: 1.5em;
                text-align: center;
                margin-top: 50px;
                color: #333; /* Dark color for contrast */
            }

            .subtitle {
                font-family: Tahoma, Geneva, sans-serif;
                font-size: 1.2em;
                text-align: center;
                margin-top: 10px;
                color: #555; /* Slightly darker text for subtitle */
            }

            .hrstyle {
                margin: 10px 0;
                border: 0;
                height: 2px;
                width: 50%;
                background: #ccc; /* Light horizontal line */
                margin-left: auto;
                margin-right: auto;
            }

            .author {
                font-family: Georgia, 'Times New Roman', Times, serif;
                font-size: 1.2em;
                color: #1a73e8; /* Subtle blue for author's name */
                margin-top: 20px;
                text-align: center;
            }

            .pub {
                font-size: 1.1em;
                text-align: center;
                margin-top: 50px;
                color: #333; /* Dark text for better contrast */
            }

            .ed {
                font-size: 1em;
                color: #1a73e8;
                text-align: center;
            }

            .mypic {
                width: 100px;
                height: 100px;
                border-radius: 50%;
                background: url('authorpic.jpg') no-repeat center;
                background-size: cover;
                margin: 20px auto;
            }

            /* Responsive design */
            @media (max-width: 600px) {
                .bookpage {
                    width: 90%;
                    height: auto;
                    padding: 10px;
                }

                .booktitle {
                    font-size: 1.2em;
                }

                .subtitle {
                    font-size: 1em;
                }

                .author {
                    font-size: 1em;
                }

                .pub {
                    font-size: 1em;
                }

                .ed {
                    font-size: 0.9em;
                }
            }
        </style>
    </head>
    <body>
        <div class="bookpage">
            <!-- Book title and subtitle -->
            <div class="header">
                <div class="booktitle">
                    <h1>FULL STACK WEB DEVELOPMENT</h1>
                </div>
                <div class="subtitle">
                    The Comprehensive Guide
                </div>
                <div class="hrstyle"></div>
            </div>

            <!-- Author's Photo -->
            <div class="mypic" aria-label="Author's Photo"></div>

            <!-- Author's Name and Edition -->
            <div class="author">
                <p><b>Aathi Sakthi</b></p>
            </div>

            <div class="footer">
                <div class="pub">SEC</div>
               
~~~

## OUTPUT:
![image](https://github.com/user-attachments/assets/7fe0010e-a6ba-4831-9155-16d162878f19)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
