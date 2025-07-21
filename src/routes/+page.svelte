<!DOCTYPE html>
<script lang="ts">
   import { signIn } from "@auth/sveltekit/client"
   import { SignIn } from "@auth/sveltekit/components"
</script>

 
<style>
    h1 {text-align: center;}
    h2 {text-align: center;}
    .footer{
        position: fixed;
        left: 0;
        bottom: 0;
        width: 100%;
        text-align: center;
    }
</style>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="background-color:#90ee90">
    <h1 style="font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;">Welcome To HikeBuddy!</h1>
    <h2 style="font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;">Track your hikes and milage</h2>
    <div>
        <SignIn provider="github" signInPage="signin" />
    </div> 
    
    <div class="footer">
        <p>
            Made with ❤️ by BasicBirdy
        </p>
    </div>
</body>
</html>
