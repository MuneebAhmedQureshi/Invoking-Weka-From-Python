# Using Weka and Python for Data Mining
# Integration of Python and Python-weka-wrapper
Sample Code with explanation for generation and plotaion of <br>
<ul>
  <li>Confusion Matrix using ZeroR</li>
  <li>Classifier Errors using Linear Regression</li>
  <li>False Positive and True Negative using Naive Bayes</li>
</ul>
<br>are given in<br><br>
<ul>
  <li>weka-from-moocs.ipynb</li>
  <li>weka-from-moocs-graphs.ipynb</li>
  <li>weka-from-moocs-curves.ipynb</li>
</ul>

# Installing Anaconda for Python

Follow this link and download Anaconda<br>
<a>https://www.anaconda.com/download/</a><br>
Click on downloaded to anaconda.*.exe file to install<br><br>

# Required Packages

To invoke Weka from Python these packages are required<br>
<ul>
  <li>Pip</li>
  <li>Numpy</li>
  <li>Imaging (Optional)</li>
  <li>Matplotlib</li>
  <li>Pygraphviz(Optional)</li>
  <li>Javabridge</li>
  <li>Python Weka Wrapper</li>
</ul><br>
These packages come preinstalled in Anaconda<br>
<ul>
  <li>Pip</li>
  <li>Numpy</li>
  <li>Matplotlib</li>
</ul><br>
These packages are to be installed by user<br>
<ul>
  <li>Javabridge</li>
  <li>Python-weka-wrapper</li>
</ul><br>

# Installing Javabridge on Windows

Open <b>Start Menu</b>, search and open <b>Anaconda Prompt</b><br><br>
Run <b>conda --verison</b> to check if Anaconda is properly installed<br><br>
Run <b>pip install javabridge</b><br><br>
If it returns error:<br><br>
<ul>
<li>Microsoft Visual C++ Version 14.0.0 is required, open Control Panel</li><br>
<b>-->></b>Navigate to <b>Uninsall A Program</b> and uninstall all instances of Visual Studio and Microsoft Visual C++ you can find. Then, follow <a href="https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&rel=15#" style="margin: 0px !important">this</a> link it will download the required version of Microsoft Visual C++<br><br>
<li>Could not find a version that satisfies the requirement <package name> (from versions: ) No matching distribution found for <package name> You are using pip version <n>, however version <n++> is available. You should consider upgrading via the 'python -m pip install --upgrade pip' command</li>
<br><b>-->></b>Run and keep running this command <b>python -m pip install --upgrade pip</b> in Anaconda Prompt until this error is resolved. Pip is sometime upgraded in a few steps.<br><br>
</ul>
Now try installing javabridge again, hopefully it will be installed.<br><br>

# Installing Python Weka Wrapper

For Python-2.*<br> <br>
Run pip install python-weka-wrapper<br><br>
For Python-3.*<br><br>
Run pip install python-weka-wrapper3<br><br>
Weka Library and Python are now successfully installed<br><br>

# Setting Environment Variable MOOC_DATA on Windows 7

Right Click on My PC<br><br>
Select Properties<br><br>
Click on Advanced System Settings<br><br>
Click on Environment Variables<br><br>
Under System Variables click New<br><br>
Set variable name to MOOC_DATA or whatever you want to use in your program<br><br>
Set variable value to the <b>full path of folder containg weka datasets e.g C:\Users\hp\Documents\WekaDatasets\</b><br><br>
Click OK and OK and OK<br><br>
Now you can check if environment variable is set by running this command in CMD <b>echo %MOOC_DATA% </b><br><br>
<b>Everything is set<b>

# Provided Helping Material 

As explained in WekaMOOCS Official channel's demonstaration<br><br>
https://www.youtube.com/watch?v=YT72KkkfD3w<br><br>
Jupyter Notebook Files of all codes used in this video are provided.<br><br>
Datasets used in this video are also provided.<br><br>

