# net-test-task-general

<h2>Frontend</h2>
<a href="https://github.com/RomanKosmyna/net-test-task-frontend" target="_blank">Frontend</a>

<h2>Backend</h2>
<a href="https://github.com/RomanKosmyna/net-test-task-backend" target="_blank">Backend</a>

<h2>It is necessary to implement the following functionality:</h2>
<ol>
  <li>Login (enter Login, Password and Authorize yourself) - :white_check_mark:</li>
  <li>You need to have Admin and ordinary users - :white_check_mark:</li>
  <li>Short urls page has table with all URLs and their equivalent after shortening, deleting of the
records is possible(only authorized users). You can view details about these URLs by
navigating to Short URL Info view with correct Id - :white_check_mark:</li>
  <li>Also it has "Add new Url" section, which is visible only to authorized users, where you can
enter URL and convert it to a short representation, after that it should be added to the
table automatically - :white_check_mark:</li>
  <li>If such a URL already exists - error message should be shown - :white_check_mark:</li>
  <li>Every authorized user can add new records("Add new Url" section) and view(redirects to
the Short URL Info view), delete records created by themselves (URLs should be unique) - :white_check_mark:</li>
  <li>Admin users can add new records("Add new Url" section) and view(redirects to the Short
URL Info view), delete all existing records. Anonymous users can only see this table - :white_check_mark:</li>
  <li>All changes should be visible right after they are done without reloading the page - :white_check_mark:</li>
  <li>Short URL Info (Anonymous can't access this page) - :white_check_mark:</li>
  <li>This page contains info about URL (CreatedBy, CreatedDate, any other fields) - :white_check_mark:</li>
  <li>About page should contain a description of your Url Shortener algorithm. Visible for
everyone(even not authorize) but can be edited only by admin users - :white_check_mark:</li>
  <li>Unit Tests - </li>
</ol>

<h2>Technologies</h2>
<table>
<tr><th>Frontend</th></tr>
<tr><td>

|Languages| Styling | Library |
|--|--|--|
|HTML, TypeScript| CSS (Tailwind), React-Toastify|React (Vite), TanStack Query, React Hook Form, Joi, Jwt Decode |
</td></tr>
<tr><th>Backend</th></tr>
<tr><td>
  
|Languages|Framework|Packages| 
|--|--|--|
|.NET/C#|ASP .NET Core, Entity Framework|Serilog, ASP .NET Core JWT Bearer, ASP .NET Core Identity|

</td></tr>
</table>

<h4>Patterns</h4>
    <ul>
      <li>DTO Pattern</li>
      <li>Repository Pattern</li>
    </ul>

<h2>Login/Register Page</h2>



    
