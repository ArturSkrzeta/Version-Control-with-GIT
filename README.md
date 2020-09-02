<h2>Version Control with Git</h2>
<h3>Repository</h3>
<ul>
  <li>Keeps the full history and source control of a project over time.</li>
  <li>Can be hosted on local computer or on a shared server like GitHub</li>
  <li>Contributors wokring on the project make  copies of the repository on their local mnachines using the push and pull commands.</li>
  <ul>
    <li><b>remote repository</b> --> shared server repository</li>
    <li><b>local repository</b> --> local machine repository</li>
  </ul>
</ul>

<h3>Workflow</h3>
<p>Working directory -- <b>GIT ADD</b> --> Staging Area -- <b>GIT COMMIT</b> --> Repository</p>

<h3>Installation and commands in Ubuntu terminal</h3>
<ul>
  <li><b>sudo apt-get install git -y</b></li>
  <li><b>git --version</b></li>
  <li><b>git init</b></li>
  <li><b>git config --global user.name "ArturSkrzeta"</b></li>
  <li><b>git config --global user.email "arturskrzeta@gmail.com"</b></li>
  
  <li><b>git config --list</b>
  <br>
  - shows all the configuration you provide
  </li>
  
  <li><b>ls -al</b>
  <br>
  - shows all files
  - we can find .gitconfig file that stores all the configuration in home directory.
  </li>
  
  <li><b>gedit .gitconfig</b>
  <br>
  - opens gitconfig file
  </li>
  
  <li><b>mkdir git_workspace</b></li>
  <li><b>cd git_workspace</b></li>
  
  <li><b>git clone https://github.com/ArturSkrzeta/BeautifulSoup-for-Web-Scraping.git</b>
  <br>
  - clones repository from GitHub
  </li>
  
  <li><b>touch script.py</b></li>
  <li><b>gedit script.py</b></li>
  
  <li><b>git status</b>
  <br>
  - gives repository status
  - it shows that one files has to be added to git
  </li>
  
  <li><b>git add script.py</b>
  <br>
  - adding a file to a git
  </li>
  
  <li><b>git status</b>
  <br>
  - it shows there are changes to commit 
  </li>
  
  <li><b>git commit -m "First Python application" script.py</b>
  <br>
  - dash m gives allows to provide command
  - in this case comment to the commit added 
  </li>
  
  <li><b>git push -u origin master</b>
  <br>
  - pushing file into GitHub account
  - it requires your GitHub credentials
  </li>
  
</ul>
