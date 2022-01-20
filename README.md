I made a basic html website with help of Azure Webapps.
Steps I follow:-
1.login into my account and click on create resources
2.created web app and resource group
3.waited to created Initial Webapp
4.opened bash terminal in Aure cloud.
5.clone my HTML code in cloud storage.
6. maintain that code in git.
7.Apply essential commands in bash terminal.
8. after successful deployment, I browsed my website and it worked as i expected.
My website URL- https://sungrace.azurewebsites.net/


this code I deployed on Azure Web Apps


<!DOCTYPE html>
<html>
  
  <head>
    <meta charset="UTF-8">
    <title>MoL Pizza Store</title>
  </head>

  <body>
    <h1>Month of Pizza Lunches</h1>
    <p>Welcome to a basic static HTML page powered by Azure Web Apps! Here are some of the yummy pizzas you can soon order online!</p>
    
    <table>
      <tr>
        <th>Name</th><th>Cost</th>
      </tr>
      <tr>
        <td>Pepperoni</td><td>$18</td>
      </tr>
      <tr>
        <td>Veggie</td><td>$15</td>
      </tr>
      <tr>
        <td>Hawaiian</td><td>$12</td>
      </tr>
    </table>

  </body>

</html>




