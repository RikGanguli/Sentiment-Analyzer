<h1>Sentiment Analysis Web App using IBM Watson NLP</h1>
  
<p>
  Sentiment Analyzer is a Python-based web application that utilizes IBM Watson NLP libraries, powered by BERT (Bidirectional Encoder Representations from Transformers), to perform sentiment analysis on text input. The application is built using the Flask framework, providing a user-friendly interface for analyzing the sentiment of any given text. With its advanced natural language processing capabilities, the app interprets sentiment efficiently and accurately. It also includes error handling and unit testing, ensuring robust and reliable performance.
  </p>
  
  <h2>Features</h2>
  <ul>
   <li><strong>Sentiment Analysis</strong>: Analyze text input and return the sentiment score using the Watson NLP library, which is based on BERT.</li>
    <li><strong>Flask Web Application</strong>: The app is built using the Flask framework to handle HTTP requests and serve the web interface.</li>
    <li><strong>Unit Testing</strong>: Basic unit tests are provided to ensure the functionality of the sentiment analysis logic.</li>
    <li><strong>Error Handling</strong>: Incorporated error handling for smooth application performance.</li>
    <li><strong>Deployed on the Web</strong>: The application is ready for deployment on the web.</li>
  </ul>
  
  <h2>Installation</h2>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/RikGanguli/Sentiment-Analyzer.git</code></pre>
      <pre><code>cd Sentiment-Analyzer</code></pre>
    </li>
    <li>Create and activate a virtual environment:
      <pre><code>python3 -m venv venv</code></pre>
      <pre><code>source venv/bin/activate  # For Windows: venv\Scripts\activate</code></pre>
    </li>
    <li>Run the app:
      <pre><code>python3 server.py</code></pre>
    </li>
  </ol>

  <h2>Running Tests</h2>
  <p>To run unit tests on the sentiment analysis application, use the following command:</p>
  <pre><code>python test_sentiment_analysis.py</code></pre>

  <h2>Deployment</h2>
  <p>The app can be deployed using Flask provided the necessary environment variables are configured for IBM Watson NLP credentials. You will need to install the IBM Watson Library to run the application</p>
  <pre><code>python3 server.py</code></pre>

  <h2>Screenshots:</h2>
  <ol>
    <li><h3> Identifying positive text:</h3>
    <p><image src="./Sentiment Positive.png"</image></p></li>

    <li><h3> Identifying negative text:</h3>
    <p><image src="./Sentiment Negative.png"</image></p></li>

    <li><h3> Identifying neutral text:</h3>
    <p><image src="./Sentiment Neutral.png"</image></p></li>
  </ol>
  

  <h2>Technologies Used</h2>
  <ul>
    <li><strong>Python</strong></li>
    <li><strong>Flask</strong></li>
    <li><strong>IBM Watson NLP Library</strong></li>
    <li><strong>HTML/CSS/JavaScript</strong></li>
    <li><strong>Unit Testing</strong>: <code>unittest</code></li>
  </ul>

  <h2>Credits:</h2>
  <p>Developed by Rik Ganguli Biswas as a part of the IBM AI Developer Professional Certificate on Coursera</p>

