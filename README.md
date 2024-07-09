# WebUI
Home.html
<!doctype html>
<html lang="en">
 <head>
 <link rel="stylesheet" href="Style1.css"></link>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"></link>
  <title>Project</title>
 </head>
 <body>
 <div id="dev">
    <div class="server">
	<a class="home" href><i id="icon"class="fa fa-home"></i>Server Management</a>
	<a class="details" href="Logout.html">Logout</a>
	<a class="details" href="Action.html">Action</a>
	<a class="details"href="Server.html">Server Details</a>
 </div>
     <div class="navibar">
	 <a class="second" href="server.html"><i id="icon"class="fa fa-server"></i>Server Management</a>
	 <a class="second" href="user.html"><i id="icon" class="fa fa-user"></i>User Management</a>
	 </div>
<div class="employee">
   <div class="label">
 <label id="boo"><i id="icon"class="fa fa-id-badge "></i>EmpId</label>
 <br>
 <br>
 <label>Empid:</label>
 <br>
 <label>Name:</label>
 <br>
 <label>Email:</label>
 <br>
 <label>Contact:</label>
 <br>
 <label>Swon:</label>
 <br>
 <label>project:</label>
 <br>
 <label>City:</label>
 <br>
 <label>Country:</label>
 <br>
 <br>
 <label><i id="icon1"class="fa fa-copy"></i>Empid</label>
 <label><i id="icon2" class="fa fa-exclamation-circle"></i>Remote all Access</label>
 </div>


 </body>
</html>


Style.css
.server{background-color:blue;
         height:40px;
		 width:1530px
		 }
.home{color:white;
      text-decoration:none;
	  float:left;
	  margin-left:20px;
	  margin-top:7px;
	  font-weight:bold}
#icon{margin-right:5px}
.details{float:right;
         margin-left:10px;
		 text-decoration:none;
		 padding-right:5px;
		 margin-top:7px;
		 color:white;
		 font-weight:bold}
.navibar{
         height:30px;
		 width:1530px;
		 border-style:groove;
		 }

.second{float:left;
        margin-left:300px;
		margin-right:10px;
		position:inline;
		margin-top:5px;
        color:black;
		text-decoration:none;
	}
.employee{
            margin-top:10px;
			margin-left:20px;

          height:230px;
          width:250px;
		  border-style:groove
		  }
.label{margin-top:5px;
        margin-left:10px}
#boo{font-size:14px;
     font-weight:bold
	 }
#icon1{color:blue;
       margin-right:2px
       }
#icon2{color:red;
