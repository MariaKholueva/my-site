# my-site
html,
body {
  margin: 0;
  font-family: "Arial", sans-serif;
  font-size: 14px;
  line-height: 20px;
}

body {
  min-width: 430px;
  border: 2px dashed #c7e4ff;
}

html::before,
body::before,
header::before,
footer::before,
main::before {
  color: #7fc1ff;
}

main,
header,
footer {
  background-color: #f3faff;
  border: 2px solid #7fc1ff;
}

nav,
section,
article,
aside {
  background-color: #f9f7ff;
  border: 2px solid #9779ec;
}

nav::before,
section::before,
article::before,
aside::before {
  color: #9779ec;
}

h1,
h2,
h3 {
  font-size: 18px;
  background-color: #ffffff;
  border: 2px solid #ff994f;
}

h1::before {
  content: "h1";
  color: #ff994f;
}

h2::before {
  content: "h2";
  color: #ff994f;
}

h3::before {
  content: "h3";
  color: #ff994f;
}

p {
  background-color: #ffffff;
  border: 2px solid #f36dff;
}

p::before {
  color: #f36dff;
  content: "p";
}

* {
  position: relative;
  padding: 25px 25px 20px;
  margin: 0;
  border-radius: 4px;
}

*:not(:last-child) {
  margin-bottom: 20px;
}

*::before {
  position: absolute;
  top: 8px;
  left: 10px;
  font-weight: 700;
  font-size: 11px;
  line-height: 10px;
  letter-spacing: 0.04em;
}

html::before {
  content: "html";
}

body::before {
  content: "body";
}

main::before {
  content: "main";
}

header::before {
  content: "header";
}

footer::before {
  content: "footer";
}

section::before {
  content: "section";
}

article::before {
  content: "article";
}

aside::before {
  content: "aside";
}

nav::before {
  content: "nav";
}
