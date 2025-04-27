<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Balanced Brackets Recognizer</title>
</head>
<body>

  <h1>Balanced Brackets Recognizer</h1>

  <p>
    A simple and efficient program to check if a string contains balanced brackets.
    It supports three types of brackets:
  </p>

  <ul>
    <li>Parentheses <code>()</code></li>
    <li>Curly Braces <code>{}</code></li>
    <li>Square Brackets <code>[]</code></li>
  </ul>

  <p>
    This project is perfect for parsing tasks, compiler design exercises, syntax checkers, and general coding practice.
  </p>

  <hr>

  <h2>Features</h2>
  <ul>
    <li>✅ Supports multiple bracket types</li>
    <li>✅ Handles nested and sequential brackets</li>
    <li>✅ Lightweight and easy to understand</li>
    <li>✅ Fast and efficient algorithm</li>
  </ul>

  <hr>

  <h2>How It Works</h2>
  <p>
    The program uses a <strong>stack</strong> data structure:
  </p>
  <ul>
    <li>Pushes opening brackets onto the stack.</li>
    <li>Pops from the stack when a closing bracket is encountered.</li>
    <li>Ensures the last opened bracket matches the latest closing bracket.</li>
  </ul>
  <p>
    If the stack is empty at the end, the brackets are balanced!
  </p>

  <hr>

  <h2>Installation</h2>
  <p>Clone the repository:</p>
  <pre><code>git clone https://github.com/your-username/balanced-brackets-recognizer.git
cd balanced-brackets-recognizer
</code></pre>

  <p>No extra libraries are needed — just run the script!</p>

  <hr>

  <h2>Usage</h2>
  <p>You can run the program directly:</p>
  <pre><code>python main.py
</code></pre>

  <p><strong>Example:</strong></p>
  <p>Input:</p>
  <pre><code>{ [ ( ) ] }
</code></pre>
  <p>Output:</p>
  <pre><code>Balanced
</code></pre>

  <p>Input:</p>
  <pre><code>( [ { } ] )
</code></pre>
  <p>Output:</p>
  <pre><code>Balanced
</code></pre>

  <p>Input:</p>
  <pre><code>( [ ) ]
</code></pre>
  <p>Output:</p>
  <pre><code>Not Balanced
</code></pre>

  <hr>

  <h2>Contributing</h2>
  <p>
    Contributions are welcome! Feel free to open issues or submit pull requests for new features, bug fixes, or improvements.
  </p>

  <hr>

  <h2>License</h2>
  <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

  <hr>

  <h2>Author</h2>
  <p>Made with ❤️ by <strong>Ayush Sharma</strong></p>

</body>
</html>
