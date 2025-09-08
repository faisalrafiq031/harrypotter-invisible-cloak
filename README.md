<h1>🧥 Harry Potter Invisibility Cloak</h1>

<p>
Ever wished you could own the magical <b>Invisibility Cloak</b> from Harry Potter? ✨<br>
This project brings that magic to life using <b>Python + OpenCV</b>. 
With just a solid-colored cloth (red, blue, or green), you can make yourself disappear in real time!
</p>

<hr>

<h2>🚀 Features</h2>
<ul>
  <li>🎥 Real-time invisibility effect using webcam.</li>
  <li>🎨 Support for multiple cloak colors (Red, Blue, Green).</li>
  <li>⚙️ Adjustable HSV sliders for fine-tuning color detection.</li>
  <li>⏱️ Smooth background capture for realistic cloak effect.</li>
  <li>🎥 Feels like real Harry Potter magic!</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>
<pre>
harrypotter-invisible-cloak/
│── invisibility_cloak.py   # Main Python code
│── README.md               # Project documentation
│── requirements.txt        # Dependencies
</pre>

<hr>

<h2>🛠️ Installation</h2>

<h3>1. Clone this repository</h3>
<pre>
git clone https://github.com/faisalrafiq031/harrypotter-invisible-cloak.git
cd harrypotter-invisible-cloak
</pre>

<h3>2. Create virtual environment (recommended)</h3>
<pre>
python -m venv venv
.\venv\Scripts\activate   # Windows
source venv/bin/activate  # Mac/Linux
</pre>

<h3>3. Install dependencies</h3>
<pre>
pip install -r requirements.txt
</pre>

<p>
If <code>opencv-python</code> fails on <b>Python 3.13</b>, install <b>Python 3.12 or lower</b>.
</p>

<hr>

<h2>📦 Requirements</h2>
<ul>
  <li>Python <b>3.8 – 3.12</b></li>
  <li>opencv-python</li>
  <li>numpy</li>
</ul>

<pre>
pip install opencv-python numpy
</pre>

<hr>

<h2>▶️ Usage</h2>
<ol>
  <li>Run the program:
    <pre>python invisibility_cloak.py</pre>
  </li>
  <li>Press keys to interact:
    <ul>
      <li><b>b</b> → Capture background (stand away from camera).</li>
      <li><b>1</b> → Select Red cloak.</li>
      <li><b>2</b> → Select Blue cloak.</li>
      <li><b>3</b> → Select Green cloak.</li>
      <li><b>h</b> → Show HSV sliders (fine-tune detection).</li>
      <li><b>q</b> → Quit program.</li>
    </ul>
  </li>
</ol>

<hr>

<h2>🧪 Demo Workflow</h2>
<ol>
  <li>Stand in front of your webcam with <b>no cloak</b> → press <code>b</code> to capture clean background.</li>
  <li>Select your cloak color (<code>1</code>, <code>2</code>, or <code>3</code>).</li>
  <li>Hold the cloak in front of you → the cloak area becomes invisible and shows the background!</li>
  <li>Adjust HSV sliders (<code>h</code>) if detection isn’t smooth.</li>
</ol>

<hr>

<h2>📸 Example Output</h2>
<p>🔴 With Red Cloak: Looks like the cloak area is transparent, and background shows through.</p>
<p>🟢 With Green Cloak: Same effect but using green cloth.</p>

<hr>

<h2>⚡ Future Improvements</h2>
<ul>
  <li>Add support for <b>any custom color cloak</b>.</li>
  <li>Improve <b>edge smoothing</b> for better invisibility effect.</li>
  <li>Option to <b>record video</b> with cloak effect.</li>
</ul>

<hr>

<h2>❤️ Credits</h2>
<p>
Inspired by <b>Harry Potter Invisibility Cloak</b>.<br>
Built with <a href="https://opencv.org/" target="_blank">OpenCV</a> and 
<a href="https://www.python.org/" target="_blank">Python</a>.
</p>

<hr>

<h2>👨‍💻 Author</h2>
<p>
<b>Faisal Rafiq</b><br>
🔗 <a href="https://github.com/faisalrafiq031" target="_blank">GitHub Profile</a>
</p>
