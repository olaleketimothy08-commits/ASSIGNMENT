function SendMail(){
    var params = {
        from_name : document.getElementById("fname").value,
         Last_Name: document.getElementById("lname").value,
        Phone_Number: document.getElementById("pnum").value,
         Date: document.getElementById("date").value,
         Message: document.getElementById("message").value
    }
    emailjs.send("service_brk8gcd", "template_5xf6bbf", params).then(function(res){
        alert("Thank you for your message😍 We will get back to you shortly.");
    })
}