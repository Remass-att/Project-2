<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>React Hello World</title>
  <script src="https://unpkg.com/react@18/umd/react.development.js"></script>
  <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
  <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background-color: #f5f5f5;
    }
    .app-container {
      text-align: center;
      background: white;
      padding: 2rem;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      max-width: 600px;
      width: 90%;
    }
    h1 {
      color: #2d3748;
      margin-bottom: 1rem;
    }
    code {
      background: #f8f9fa;
      padding: 0.2rem 0.4rem;
      border-radius: 4px;
      font-family: 'Courier New', monospace;
      color: #e53e3e;
    }
  </style>
</head>
<body>
  <div id="root"></div>

  <script type="text/babel">
    function App() {
      return (
        <div className="app-container">
          <h1>Hello World!</h1>
          <p></p>
          <p></p>
          <p></p>
          <p><code>App.js</code>.</p>
        </div>
      );
    }

    const root = ReactDOM.createRoot(document.getElementById('root'));
    root.render(<App />);
  </script>
</body>
</html>

