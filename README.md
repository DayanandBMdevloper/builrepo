<!Doctype html>
<body>
  <srcipt>
    document.getElementById("display").innerHtml=inname.value
    </srcipt>
  
  <input name="inname" (input)=display() placeholder="enter the name...">
  <p id="display"></p>
  </body>
  </html>
