# <center>![MathScannerSolver logo](https://i.imgur.com/Y5x0y3P.png)</center>
# <center>User Manual</center>

<details>
  <summary> How to Install (click to expand) </summary>
  
### I. Cloning the Repository


1.  Open the Windows run command, either by pressing the *Windows key + R key* at the same time, or by typing *"Run"* into the Windows search bar and selecting the Run app from the list.
2.  Type *"cmd"* into the run box and then press the *"OK"* button to open the Windows Command Prompt.
3.  Enter the following into the Command prompt and then press the *Enter* key:
>git clone https://github.com/Dylans17/MathScannerSolver.git

### II. Installing npm Dependencies and build React
1. Input each of the following lines into the Windows Command Prompt, press the *Enter* key after each line:
>cd MathScannerSolver/Code  
>npm install  
>npm run build


### III. Installing Node
1. Click [here](https://nodejs.org/en/download/) to download the latest version of Node.
2. Select the installation that is most appropriate for your system. For most users this will be the *64-bit Windows Installer (.msi)* file.
3. Once the download has finished, open the corresponding installation file.
4. Follow the prompts to completion to install Node.js on your machine.

### IV. Running the application
1. Verify that your Command Prompt is in the *"Code"* folder of MathScannerSolver. If it is not, use the cd command followed by the location of the code folder to change to the proper directory.
2. In the Windows Command Prompt enter the following, and then press the *Enter* key:
>node index.js
3. If successful, the command prompt should indicate that it is listening on port 9000.
![Command Prompt listening](https://i.imgur.com/ylGjuVC.png) 

### V. Accessing the website
1. Open your internet browser of choice
2. Enter *"localhost: 9000"* into the browser's navigation bar and press the *Enter* key.
3. If successful, you should see the MathScannerSolver page loaded.

![Home Page](https://i.imgur.com/yuqnVfI.png)
  
</details>


<details>
<summary>How to Use (click to expand)</summary>
  
## Uploading an image

1. On the front page, left click on the *"Upload Your Picture"* button.
2. The page should display a drag 'n' drop box that looks like: ![Drag 'n' Drop your image here](https://i.imgur.com/L6agY9G.png)
3. You can either drag an image over the box and release it, or click on the box and navigate to the desired picture.
4. After a picture has been chosen, it will be displayed.
5. If you wish, press the edit icon above your image to manually edit your input and press the *Set* button when finished. ![](https://i.imgur.com/y65QxRY.png)
6. You will be brought to a screen showing the image you uploaded, above it the result will be displayed.

## Taking a Picture

1. On the home screen, press the *"Take a Picture"* button. 
2. A pop up box may appear asking for permission to use your picture, select *Yes* to enable your camera.
3. A screen showing your camera should appear, with a small circle in the middle of the camera frame.
![Camera Picture](https://i.imgur.com/fw8aHRV.png)
4. Press the small circle and a picture will be taken and uploaded.
5. You can choose to take another picture, or hit the next key to display your results.

## Inputting an Equation

1. At the home screen, press the *"Type an Equation"* to be brough to the input equation page. 
2. In the following screen, input the equation you wish to be solved into the input box.
![](https://i.imgur.com/wdYIFtX.png)
3. You can press the *"Add another Equation"* button at any time to add another equation.
4. Once satisfied with your input, you can press the *"Submit"* button to submit your input.
5. Upon submission, you will be taken to the results page.
![](https://i.imgur.com/UH1VjX2.png)
</details>

<details>
  
  <summary>FAQ (click to expand) </summary>

### What is MathScannerSolver?
>MathScannerSolver creates a webserver which hosts a site inputting math either via text or through uploading images, and provides methods to display and solve a small subset of math problems.

### Who created MathScannerSolver?
>Group 8, consisting of Dylan Strickley, Carlos Garcia Gomez, Jonathan O'Berry, Abigail Beneduce, Pam Viana, and Sarah Baron are the creators of MathScannerSolver.

### How does MathScannerSolver work?
>MathScannerSolver works by using our custom LaTeX parser and solver to resolve the answer to user input. LaTeX strings from image input is found by using the MathPix API to pull LaTeX from uploaded images.

### What languages is MathScannerSolver written in?
>MathScannerSolver is primarily written in REACT for the Frontend and JavaScript for the backend. Additionally, MathScannerSolver uses ANTLR as a parser generator.

### Why was MathScannerSolver created?
>MathScannerSolver was created as a University project as Group 8 found there to be a lack of a proper LaTeX solver written in JavaScript. 
  
</details>
