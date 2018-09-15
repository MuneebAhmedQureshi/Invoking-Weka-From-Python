# Invoking-Weka-From-Python
Getting started with Python Weka Wrapper using Python<br>
<br><b>Installing Anaconda for Python</b><br>
Follow this link and download Anaconda<br>
<a>https://www.anaconda.com/download/</a><br>
<br><b>Installing Required Packages</b><br>
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
<b>Installing Javabridge on Windows</b><br><br>
Open <b>Start Menu</b>, search and open <b>Anaconda Prompt</b><br><br>
Run <b>conda --verison</b> to check if Anaconda is properly installed<br><br>
Run <b>pip install javabridge</b><br><br>
If it returns error:
<ul>
<li>Microsoft Visual C++ Version 14.0.0 is required, open Control Panel</li><br>
<b>-->></b>Navigate to <b>Control Panel -> Uninsall A Program</b> and Uninstall all instances of Visual Studio and Microsoft Visual C++ you can find. Then, follow <a href="https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&rel=15#" style="margin: 0px !important">this</a> link it will download the required version of Microsoft Visual C++<br><br>
<li>Could not find a version that satisfies the requirement <package name> (from versions: ) No matching distribution found for <package name> You are using pip version <n>, however version <n++> is available. You should consider upgrading via the 'python -m pip install --upgrade pip' command</li>
<br><b>-->></b>Run and keep running this command <b>python -m pip install --upgrade pip</b> in Anaconda Prompt until this error is resolved. Pip is sometime upgraded in a few steps.<br><br>
</ul>
Now try installing javabridge again, hopefully it will be installed.<br><br>
<b>Installing Python Weka Wrapper</b><br><br>
For Python-2.*<br> <br>
Run pip install python-weka-wrapper<br><br>
For Python-3.*<br><br>
Run pip install python-weka-wrapper3<br><br>
<b>Weka Library and Python are now successfully installed</b><br><br>
<b>Provided Helping Material</b><br><br>
As explained in WekaMOOCS Official channels demonstaration<br><br>
https://www.youtube.com/watch?v=YT72KkkfD3w<br><br>
Jupyter Notebook Files of all codes used in this video are provided.<br><br>
Datasets used in this video are also provided.<br><br>
