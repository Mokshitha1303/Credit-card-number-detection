<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Credit Card Number Detection in Text Files">
   
</head>
<body>
    <header>
        <h1>Credit Card Number Detection in Text Files</h1>
    </header>

  <div class="container">
        <h2>About the Project</h2>
        <p>
            This project simulates the generation and detection of credit card numbers in text files. It includes the creation of files, 
            zipping and extracting files, and searching for credit card numbers using <strong>regular expressions (regex)</strong>. 
            The primary goal is to demonstrate basic file handling, compression, and pattern matching techniques in Python.
        </p>

   <h2>Key Features</h2>
        <ul>
            <li>Generates 50 text files, some containing randomly generated credit card numbers (Visa, MasterCard, AmEx).</li>
            <li>Compresses the files into a ZIP archive.</li>
            <li>Extracts the ZIP archive to a specified folder.</li>
            <li>Uses regex to detect valid credit card numbers in the files.</li>
            <li>Displays the content of the files in chronological order of their creation.</li>
        </ul>

  <h2>Models and Libraries Used</h2>
        <ul>
            <li><strong>Python Standard Libraries:</strong> <code>os</code>, <code>random</code>, <code>zipfile</code>, <code>re</code>.</li>
            <li><strong>Regular Expressions (Regex):</strong> Used for detecting valid credit card patterns based on industry standards.</li>
        </ul>

  <h2>How It Works</h2>
        <ol>
            <li>
                <strong>File Generation:</strong> 
                Creates 50 text files, with 20% probability of a file containing a credit card number.
            </li>
            <li>
                <strong>Compression:</strong> 
                Zips the generated files into a single archive.
            </li>
            <li>
                <strong>Extraction:</strong> 
                Extracts the files to a specified directory for analysis.
            </li>
            <li>
                <strong>Pattern Matching:</strong> 
                Uses regex to search for valid credit card numbers in the files.
            </li>
            <li>
                <strong>Chronological Output:</strong> 
                Reads and displays file content in the order of their creation time.
            </li>
        </ol>

   <h2>Credit Card Detection</h2>
        <p>
            The regex pattern used for detection identifies the following credit card formats:
        </p>
        <ul>
            <li><strong>Visa:</strong> Starts with 4, followed by 15 digits.</li>
            <li><strong>MasterCard:</strong> Starts with 5, followed by 15 digits.</li>
            <li><strong>AmEx:</strong> Starts with 3, followed by 14 digits.</li>
        </ul>
        <p>Invalid numbers are ignored, ensuring accurate detection.</p>

   <h2>How to Run the Project</h2>
        <ol>
            <li>Clone the repository:</li>
            <pre><code>git clone https://github.com/Mokshitha1303/Credit-card-number-detection/blob/main/Credit_Card_Number_Detection.ipynb</code></pre>
            <li>Navigate to the project directory:</li>
            <pre><code>cd credit-card-detection</code></pre>
            <li>Run the script:</li>
            <pre><code>python main.py</code></pre>
            <li>Check the output for detected credit card numbers and file contents.</li>
        </ol>

<h2>Sample Output</h2>
        <p><strong>Example of detected credit card numbers:</strong></p>
        <pre><code>
Credit card number found in file: test_file_3.txt
['4534567812345678']

Credit card number found in file: test_file_22.txt
['5312345678901234']
        </code></pre>

  <h2>Applications</h2>
        <ul>
            <li>Demonstrating file handling and compression in Python.</li>
            <li>Learning and applying regex for pattern matching.</li>
            <li>Implementing basic data security techniques by detecting sensitive information in text files.</li>
        </ul>



  <h2>Contributing</h2>
        <p>Contributions are welcome! Please fork the repository and submit a pull request with any enhancements or fixes.</p>
    </div>

 <footer>
        <p>&copy; 2024 Mokshitha M. </p>
    </footer>
</body>
</html>
