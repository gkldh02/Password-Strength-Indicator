# Password-Strength-Indicator.
A jQuery / Bootstrap Password Strength Indicator plugin that creates a progress bar below your password field to indicate the password strength and displays error messages to prompt user with correct password parameters/requirements.

# include the jquery.passwordstrength.min.js script after jQuery.
<script src="passwordstrength.js"></script>

# sign up form like this:
<form>
  <div class="form-group">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" placeholder="Email">
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
  </div>
  <button type="submit" class="btn btn-danger">Submit</button>
</form>

# call the function on the password field.
<script>
$('#exampleInputPassword1').passwordStrength();
</script>

# Specify the minimum amount of characters.

<script>
$('#exampleInputPassword1').passwordStrength({
  minimumChars: 8
});
</script>
