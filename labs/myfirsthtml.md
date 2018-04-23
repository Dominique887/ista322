<!DOCTYPE html>

<html>

  <head>

    <title> My first HTML form </title>

  </head>

  <body>

    <h1>My first html form </h1>

    <form method='post' action = ''>

      First Name: <input id='first' name='first' type='text' />

      <br />

      Last Name: <input id='last' name='last' type='text' />

      <br />

      username: <input id='username' name='username' type='text' />

      <br />

      password: <input id='password' name='password' type='password' />

      <br />

      Gender:

        Male: <input name='gender' id='gender' type='radio' value='male' />

        Female: <input name='gender' id='gender' type = 'radio' value ='female' />

        <br />

        Ethnicity: 

          Asian: <input id='eth' name='eth' type='checkbox' value = 'asian' />

          White: <input id='eth' name='eth' type='checkbox' value = 'white' />

          Black: <input id='eth' name='eth' type='checkbox' value = 'black' />

          Mexican: <input id='eth' name='eth' type='checkbox' value = 'mexican' />

          <br />

          

        <select name = 'pizza' multiple='multiple' size='3' >

          <option value='blackolives'>black olives</option>

          <option value='peperoni'>peperoni</option>

          <option value='anchovies'>anchovies</option>

          <option value='pineapple'>pineapple</option>

          <option value='ham'>ham</option>

        </select>

      

      <input id='submit' name='submit' value='submit' type = 'submit'/>

      <input type = 'reset' value = 'reset' />

    </form>

  </body>

</html>