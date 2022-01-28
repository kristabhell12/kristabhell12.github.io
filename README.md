## personal resume website

### instalation of tools

* make sure you have resume-cli installed from https://github.com/jsonresume/resume-cli
* make sure you have installed elegant and papirus theme installed:

    npm install -g jsonresume-theme-papirus

    npm install -g jsonresume-theme-elegant

* export index.html from elegant theme

    resume export index.html -t elegant

* apply patch to index.html

* to generate resume in pdf, serve your resume with papirus theme

    resume serve -r resume.json -t papirus

* in the browser  print your resume  (adjusting and formatting) and put in the public folder

* git add . and git commit

* to test in the public directory:

    python -m http.server 8000 

