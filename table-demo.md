---
layout: default
---
  
{{ content }}


<h2> Ryan vs Ryan: Liquid Table Demo </h2>

<table id="ryan-v-ryan">

<thead>
  <tr>
    <th>  <h3>  Ryan Reynolds  </h3>  </th>
    <th>  <h3>  Ryan Gosling  </h3>  </th>
  </tr>
</thead>

<tbody>

<tr>
  
  
  <td>
  
    
    <h4>  Strengths  </h4>
    <ul>
      
      {% for item in page.reynolds.strengths %}
         <li>{{ item }}</li>
      {% endfor %}
      
    </ul>
    
    <br>

    <h4>  Weaknessess  </h4>
    <ul>
      
      {% for item in page.reynolds.weaknesses %}
         <li>{{ item }}</li>
      {% endfor %}
      
    </ul>  
    
    
  </td>
  


  <td>
  
    <h4>  Strengths  </h4>
    <ul>
      
      {% for item in page.gosling.strengths %}
        <li>{{ item }}</li>
      {% endfor %}
      
    </ul>
    
    <br>
    
    <h4>  Weaknessess  </h4>
    <ul>
      
      {% for item in page.gosling.weaknesses %}
         <li>{{ item }}</li>
      {% endfor %}
      
    </ul>

  </td>
</tr> 

</table>


<br>

<hr>

<br>
  
<style>
  pre{
  font-family: Consolas, Menlo, Monaco, Lucida Console, Liberation Mono, DejaVu Sans Mono, Bitstream Vera Sans Mono, Courier New, monospace, serif;
  margin-bottom: 10px;
  padding: 5px;
  background-color: #eee;
  width: 750px!ie7;
  padding-bottom: 20px!ie7;
}

ui {
  padding-inline-start: 10px;
  }
  
table {
  margin-left: 20px;
  }
  
</style>

## Lorem Ipsum

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<hr>
