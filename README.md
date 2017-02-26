# registration-page
html page of registration

I'm Kalpani Ranasinghe. I wanted to add validation part to my registration page.

<script type = "text/javascript" language= "javascript">
		function checkUser(){
			var i = document.forms["register"]["un"].value;
			var j = document.forms["register"]["pass"].value;
			var k = document.forms["register"]["fname"].value;
			var l = document.forms["register"]["lname"].value;
			//if(i == null || i == "") & (j == null || j == ""){
			//	alert("Username or password cannot be empty!!!");
			//	return false;
			//}
			if(k == null || k == ""){
				alert("Enter your first name!!!");
				return false;
			}else if(l == null || l == ""){
				alert("Enter your second name!!!");
				return false;
			}else if (i == null || i == ""){
				alert("Username cannot be empty!!!");
				return false;
			}else if(j == null || j == ""){
				alert("Password cannot be empty!!!");
				return false;
			}
		} 
</script>
