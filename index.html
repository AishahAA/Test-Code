<!DOCTYPE html>
<html>
<head>
    <title>Extract XML Data using JavaScript</title>

    <style>
        body {font:17px Vardana;}
        #books {
            width:390px;
            text-align:center;
            border:solid 1px #000;
            overflow:hidden;
        }
        #books div {
            width:180px;
            text-align:left;
            border:solid 1px #000;
            margin:1px;
            padding:2px 5px;
        }
        .col1 {
            float:left;
            clear:both;
        }
        .col2 {
            float:right;
        }
    </style>
</head>
<body>
    <p>Data extracted from an <b>XML</b> file</p>
    <div id="books"></div>
</body>

<script>
  
    
function loadXMLDoc(dname)
{
    if (window.XMLHttpRequest)
    {
        xhttp=new XMLHttpRequest();
    }
    else
    {
        xhttp=new ActiveXObject("Microsoft.XMLHTTP");
    }
    xhttp.open("GET",dname,false);
    xhttp.send();
    return xhttp.responseXML;
} 
function searchXML()
{
    xmlDoc=loadXMLDoc("test.xml");
    x=xmlDoc.getElementsByTagName("place_name");
    input = document.getElementById("input").value;
    size = input.length;
    if (input == null || input == "")
    {
        document.getElementById("results").innerHTML= "Please enter a character or name!";
        return false;
    }
    for (i=0;i<x.length;i++)
    {
        startString = place_name.substring(0,size);
        if (startString.toLowerCase() == input.toLowerCase())
        {
            place_name=xmlDoc.getElementsByTagName("place_name")[i].childNodes[0].nodeValue;
            docAuthor=xmlDoc.getElementsByTagName("docAuthor")[i].childNodes[0].nodeValue;
            docTitle=xmlDoc.getElementsByTagName("docTitle")[i].childNodes[0].nodeValue;
            docDate=xmlDoc.getElementsByTagName("docDate")[i].childNodes[0].nodeValue;
            doc_page_number=xmlDoc.getElementsByTagName("doc_page_number")[i].childNodes[0].nodeValue;
            divText = "<h1>The contact details are:</h1><br /><table border=1><tr><th>Place Name</th><th>Doc Author</th><th>Doc Title</th><th>Doc Date</th><th>Doc Page Number</th></tr>" + "<tr><td>" + place_name + "</td><td>" + docAuthor + "</td><td>" + docTitle + "</td><td>" + docDate + "</td><td>" + doc_page_number + "</td><td>" + "</td></tr>" + "</table>";
            break;
        }
        else
        {
            divText = "<h2>The contact does not exist.</h2>";
        }
    }
    document.getElementById("results").innerHTML= divText;
}

    
    
    
    var oXHR = window.XMLHttpRequest ? new XMLHttpRequest() : new ActiveXObject('Microsoft.XMLHTTP');

    function reportStatus() {
        if (oXHR.readyState == 4)               // REQUEST COMPLETED.
            showTheList(this.responseXML);      // ALL SET. NOW SHOW XML DATA.
    }

    oXHR.onreadystatechange = reportStatus;
    oXHR.open("GET", "test.xml", true);      // true = ASYNCHRONOUS REQUEST (DESIRABLE), false = SYNCHRONOUS REQUEST.
    oXHR.send();

    function showTheList(xml) {

        var divBooks = document.getElementById('books');        // THE PARENT DIV.
        var Book_List = xml.getElementsByTagName('match');       // THE XML TAG NAME.

        for (var i = 0; i < Book_List.length; i++) {

            // CREATE CHILD DIVS INSIDE THE PARENT DIV.
            var divLeft = document.createElement('div');
            divLeft.className = 'col1';
            divLeft.innerHTML = Book_List[i].getElementsByTagName("place_name")[0].childNodes[0].nodeValue;

            var divRight = document.createElement('div');
            divRight.className = 'col2';
            divRight.innerHTML = Book_List[i].getElementsByTagName("snippet")[0].childNodes[0].nodeValue;

            // ADD THE CHILD TO THE PARENT DIV.
            divBooks.appendChild(divLeft);
            divBooks.appendChild(divRight);
        }
    };
</script>
</html>
