# bCrypt4pm
bCrypt for postman

useage

const Bcrypt = eval(pm.globals.get("bcryptoKit"));

function bcrytResult(bcrytHash){
		 console.log(bcrytHash);
}

Bcrypt.hashpw(pwd, r2, bcrytResult, function() {});





This is a javascript implementation of bCrypt based on https://github.com/nevins-b/javascript-bcrypt
